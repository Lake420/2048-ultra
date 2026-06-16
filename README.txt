2048 ULTRA — PAQUETE COMPLETO
==============================

NOVEDADES DE ESTA VERSIÓN
--------------------------
✅ Estilo DARK + ROJO NEÓN (glassmorphism, glows, grid animado)
✅ Tipografía gaming (Orbitron)
✅ Música electrónica procedural (Web Audio API, sintetizada en tiempo real)
✅ Efectos de sonido reactivos (slide, merge, win, game over, spawn)
✅ Sistema de partículas al fusionar fichas
✅ Pantalla que vibra en merges grandes (≥128)
✅ Modo DIFÍCIL (💀) — solo fichas de valor 4 y 8
✅ Estadísticas: movimientos, tiempo, ficha máxima
✅ Combo multiplier visual
✅ Puntuación flotante al puntuar
✅ Animaciones de fichas mejoradas con rotación
✅ PWA mejorada — funciona 100% offline

QUÉ HAY EN ESTE ZIP
--------------------
- index.html    → el juego completo (HTML+CSS+JS en un solo archivo)
- manifest.json → hace que el juego se pueda instalar como app
- sw.js         → service worker mejorado, offline completo
- icon-192.png  → icono de la app (resolución pequeña)
- icon-512.png  → icono de la app (resolución grande)
- README.txt    → este archivo

OPCIÓN 1 — JUGAR DIRECTO, SIN INSTALAR NADA
--------------------------------------------
1. Abre index.html directamente con doble clic.
2. Se abre en Chrome/Firefox/Safari y ya puedes jugar.
   NOTA: La música se activa al hacer tu primer movimiento o al
   hacer clic en el tablero (restricción del navegador).

OPCIÓN 2 — INSTALARLO COMO APP (PWA REAL, RECOMENDADO)
-------------------------------------------------------
Para que funcione offline al 100% y como app instalada:

  A) EN TU ORDENADOR (rápido, local)
     1. Abre una terminal en la carpeta del juego.
     2. Ejecuta: python3 -m http.server 8080
        (o si prefieres: npx -y serve .)
     3. Abre en el navegador: http://localhost:8080
     4. En Chrome: menú ⋮ → "Instalar aplicación" → ¡listo!

  B) EN MÓVIL
     1. Sirve desde el ordenador como arriba.
     2. Conecta el móvil a la misma WiFi.
     3. Entra a http://IP_LOCAL:8080
     4. Chrome/Safari → "Añadir a pantalla de inicio"

  C) EN INTERNET (hosting gratuito)
     Sube los 5 archivos a:
     - GitHub Pages
     - Netlify (arrastra la carpeta)
     - Vercel

CONTROLES
---------
- Teclado: Flechas ↑↓←→ o W/A/S/D
- Móvil/Táctil: Desliza en cualquier dirección sobre el tablero
- ↺ NUEVA: reinicia la partida
- ↩ DESHACER: hasta 10 movimientos atrás
- 💀: activa/desactiva Modo Difícil
- 🎵/🔇: activa/desactiva música electrónica

CÓMO JUGAR
-----------
- Mueve todas las fichas en una dirección.
- Las fichas con el mismo número se fusionan al colisionar.
- ¡Llega al 2048 para ganar! (puedes continuar después).
- La mejor puntuación se guarda en el navegador.

MODO DIFÍCIL (💀)
-----------------
- Solo aparecen fichas de valor 4 o 8 (nunca 2).
- Más difícil de fusionar, requiere más estrategia.
- Guarda su propio record separado del modo normal.

SOBRE LA MÚSICA
---------------
La música electrónica es 100% generada en tiempo real por el
navegador usando la Web Audio API — sin descargar archivos de audio.
Incluye: kick drum, hi-hats, bassline y pads con reverb.
BPM: 128 (house electrónico).
La música se activa automáticamente en tu primer movimiento.

PERSONALIZACIÓN
---------------
Las variables de color están en :root al inicio del <style>:
  --ac     → color de acento (actualmente rojo neón #ff1744)
  --bg     → fondo general
  --neon-r → shadow del glow neón
Cambiándolas se actualiza todo el tema visual.
