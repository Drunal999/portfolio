# Portfolio

Personal portfolio site — [runaldevarshi.com](#) (Vercel).

One file, no build step. `index.html` holds the markup, the CSS and the WebGL scene.
The only external dependency is Three.js (r128) from cdnjs; everything else is inline.

## The background

A live 3D city rendered with Three.js. Buildings are a single `InstancedMesh` with a
custom shader that draws window grids procedurally and lights a building from the
ground up when a "run" passes through it. Scroll position drives the camera along a
set of keyframes; the mouse adds parallax. Honours `prefers-reduced-motion`.

## Local

Open `index.html` in a browser. That's it.

## Deploy

Pushed to `main` — Vercel builds and deploys automatically.
