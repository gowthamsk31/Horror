IRAVU 3:33 — The Night Ward v12

This is an update of the existing Three.js game, not a new game.

RUN ON DESKTOP:
1. Extract the ZIP.
2. Open a terminal in this folder.
3. Run: python -m http.server 8000
4. Visit http://localhost:8000

ANDROID:
Use an HTTPS host or local web-server app. Do not open index.html from Downloads (content://); Chrome may block the Three.js module and render a black scene.

CONTROLS: WASD + mouse look, E interact, F torch, Shift sprint, C crouch, Esc pause. Mobile landscape: left joystick moves, right joystick looks, action buttons interact/torch/run/hide. Map opens only when tapped.

Assets: storyboard-reference.png is the supplied exact storyboard image. ghost-whisper.mp3 is the supplied ambience recording. Three.js loads from jsDelivr, so an internet connection is required.

Checks performed: JavaScript module syntax check; HTML parsing; duplicate-ID scan. A full interactive desktop/Android gameplay pass has not been completed.
