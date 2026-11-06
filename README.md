# Rotor — Air Strike

A dependency-free helicopter arcade game. Open `index.html` directly in a modern browser, or serve this directory:

```sh
python3 -m http.server 3000 --bind 0.0.0.0
```

Fly with WASD or the arrow keys. Hold Space to fire downward. Press P to pause. Touch controls are provided on small screens.

Rounds last 60 seconds. Cars take one hit and award 100 points; tanks take two hits and award 150 points. At most 10 vehicles are active. Best scores are stored locally in the browser. Sound is optional.

No install, credentials, build, or external assets are required. To publish online, deploy these static files to any static website host.
