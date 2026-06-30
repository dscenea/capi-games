# 🎮 Capi Games

Juego web para jugar con amigos: adivina futbolistas y baloncestistas con pistas progresivas, gira la ruleta de equipos/países, y compite por puntos en un marcador compartido.

## Modos de juego

- **🧠 Adivina** — Pistas progresivas sobre futbolistas o baloncestistas (90s, 2000s y 2010s). Sistema de turnos: si fallas pierdes 10 puntos y pasa al siguiente; si pasas, no hay penalización.
- **🎰 Ruleta** — Gira y obtén un equipo o país al azar (fútbol o baloncesto) para que cada jugador piense un futbolista/jugador de ese resultado.
- **🎬 Películas** — Adivina la película con pistas progresivas.

## Cómo publicarlo en GitHub Pages

1. Crea un repositorio nuevo en GitHub (puede ser público o privado, pero Pages gratis requiere que sea público salvo plan de pago).
2. Sube el archivo `index.html` de este proyecto a la raíz del repositorio (puedes arrastrarlo directamente desde la web de GitHub con "Add file → Upload files").
3. Ve a **Settings → Pages** en el repositorio.
4. En "Source", selecciona la rama `main` (o `master`) y la carpeta `/ (root)`.
5. Guarda. GitHub te dará una URL del tipo:
   `https://tu-usuario.github.io/nombre-del-repo/`
6. Espera 1-2 minutos y entra en esa URL — ¡listo para jugar!

## Estructura del proyecto

```
capi-games-repo/
├── index.html   ← todo el juego (HTML + CSS + JS en un solo archivo)
└── README.md    ← este archivo
```

No requiere build, dependencias ni backend. Es 100% estático y funciona directamente en el navegador.

## Notas técnicas

- Sin almacenamiento persistente: el marcador se reinicia al recargar la página (ideal para partidas puntuales con amigos).
- Pensado para móvil y escritorio (diseño responsive).
- Compatible con cualquier navegador moderno (usa emojis nativos para banderas e iconos, sin imágenes externas).
