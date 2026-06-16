# 🎮 2048 ULTRA

<div align="center">

![2048 ULTRA](https://img.shields.io/badge/2048-ULTRA-ff1744?style=for-the-badge&logo=gamepad&logoColor=white)
![PWA](https://img.shields.io/badge/PWA-Instalable-ff1744?style=for-the-badge&logo=pwa&logoColor=white)
![Offline](https://img.shields.io/badge/Offline-100%25-ff1744?style=for-the-badge&logo=wifi&logoColor=white)

### 🔗 [JUGAR AHORA → lake420.github.io/2048-ultra](https://lake420.github.io/2048-ultra/)

*Experiencia gaming premium: Dark Red + Música Electrónica + Power-ups + Logros*

</div>

---

## 🚀 Acceso Rápido

| Qué | Link |
|---|---|
| 🎮 **Jugar online** | **https://lake420.github.io/2048-ultra/** |
| 💻 **Código fuente** | https://github.com/Lake420/2048-ultra |
| 📁 **Descargar ZIP** | https://github.com/Lake420/2048-ultra/archive/refs/heads/main.zip |

> ✅ Funciona en **cualquier dispositivo** con navegador: PC, Mac, iPhone, Android, tablet.
> No necesitas instalar nada. Solo abres el link y juegas.

---

## ✨ Características

### 🎨 Visual
- Tema **Dark Red Neón** con glassmorphism y scanlines CRT
- Tipografía **Orbitron** (fuente gaming)
- Logo con **glow neón** animado
- Tiles con **efecto lava** y box-shadows reactivos
- **Efecto Glitch** en victoria/derrota
- Grid de fondo animado que **pulsa con el BPM** de la música

### 🎵 Audio
- **Música electrónica procedural** — sintetizada en tiempo real (Web Audio API)
  - Kick drum, hi-hats, bassline sawtooth, pads con reverb
  - BPM: 128 (house electrónico)
- **Visualizador de espectro** de audio en tiempo real
- **Efectos de sonido** reactivos: slide, merge, win, game over, spawn, power-up

### ⚡ Power-ups *(se ganan cada 15 movimientos)*
| Icono | Nombre | Efecto |
|---|---|---|
| 💣 | **Bomba** | Elimina cualquier ficha con explosión de partículas |
| 🔀 | **Mezcla** | Redistribuye todas las fichas aleatoriamente |
| ❄️ | **Frío** | Congela el timer del Modo Tiempo 10 segundos |

### 🏆 Logros (10 achievements)
Primera fusión · Ficha 128/512/1024/2048 · Combo x3 · 100 movimientos · Usar bomba · Ganar sin deshacer · 10,000 puntos

### 📊 Leaderboard Local
Top 10 puntuaciones guardadas en el dispositivo. Click en **📊 TOP** para ver.

### 🎮 Modos de Juego
- **Normal** — clásico 2048
- **Difícil 💀** — solo fichas de valor 4/8
- **Tiempo ⏱** — 90 segundos para la mayor puntuación posible

### 📐 Tamaños de tablero
3×3 · 4×4 · 5×5 · 6×6

---

## 🕹️ Controles

| Dispositivo | Control |
|---|---|
| ⌨️ Teclado | Flechas `↑↓←→` o `W A S D` |
| 📱 Táctil | Deslizar el dedo sobre el tablero |
| `ESC` | Cancelar power-up activo |

---

## 📱 Instalar como App (PWA)

El juego es una **PWA (Progressive Web App)** — se instala en cualquier dispositivo como app nativa, sin pasar por ninguna tienda de apps.

**En Chrome (Mac/PC/Android):**
1. Abre https://lake420.github.io/2048-ultra/
2. Menú `⋮` → **"Instalar aplicación"**
3. Aparece en el escritorio/inicio como app real

**En iPhone/iPad (Safari):**
1. Abre el link en Safari
2. Botón compartir `⬆` → **"En el inicio"**

**Funciona 100% offline** una vez instalada (Service Worker activo).

---

## 🔧 Usar / Modificar localmente

```bash
# Opción 1 — Doble clic en index.html (más sencillo)
# El juego funciona directamente en el navegador

# Opción 2 — Servidor local (para PWA completa + service worker)
python3 -m http.server 8080
# Luego abre: http://localhost:8080

# Opción 3 — Con npx
npx -y serve .
```

---

## 🚀 Actualizar el juego online

Si modificas `index.html` y quieres que el cambio aparezca en el link online:

```bash
cd /Users/danielavaldez/Desktop/2048-game
git add -A
git commit -m "descripción del cambio"
git push
```
GitHub Pages se actualiza solo en **~1 minuto**.

---

## 🗂️ Estructura del proyecto

```
2048-ultra/
├── index.html      ← Todo el juego (HTML + CSS + JS en un solo archivo)
├── manifest.json   ← Configuración PWA (nombre, colores, iconos)
├── sw.js           ← Service Worker (modo offline)
├── icon-192.png    ← Icono de la app (pequeño)
├── icon-512.png    ← Icono de la app (grande)
└── README.md       ← Este archivo
```

---

## 🛠️ Tecnologías

- **HTML5 + CSS3 + JavaScript** — sin frameworks, sin dependencias
- **Web Audio API** — música y efectos de sonido sintetizados en tiempo real
- **Canvas API** — partículas y visualizador de audio
- **Service Worker** — modo offline completo
- **PWA Manifest** — instalación como app nativa
- **localStorage** — puntuaciones y logros persistentes

---

## 📈 Historial de versiones

| Versión | Fecha | Cambios |
|---|---|---|
| v1.0 | Jun 2026 | Juego base funcional, PWA básica |
| v1.5 | Jun 2026 | Dark Red theme, música electrónica, partículas |
| v2.0 | Jun 2026 | Visualizador audio, Power-ups, Logros, Leaderboard, Modo Tiempo, Glitch |

---

<div align="center">

**Creado con ❤️ y mucho neón rojo**

🔗 **[lake420.github.io/2048-ultra](https://lake420.github.io/2048-ultra/)**

</div>
