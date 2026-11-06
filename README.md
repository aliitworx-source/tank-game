# Rotor — Air Strike

A dependency-free helicopter arcade game. Open `index.html` directly in a modern browser, or serve this directory:

```sh
python3 -m http.server 3000 --bind 0.0.0.0
```

Fly with WASD or the arrow keys. Hold Space to fire downward. Press P to pause. Touch controls are provided on small screens.

The campaign has three 60-second levels with increasingly fast vehicles and spawns. Select Start Level after each cleared sector; score and armor carry forward. The helicopter faces the last horizontal movement direction. Each tank and roof-mounted Humvee soldier fires an aimed projectile every 10 seconds at 140 pixels/second. The helicopter starts with 10 armor points and dies on the tenth projectile hit. Every hit counts, including hits close together. Pausing freezes gameplay and enemy cooldowns. Armed Humvees take one hit and award 100 points; tanks take two hits and award 150 points. At most 10 vehicles are active. Best scores are stored locally in the browser. Sound is optional.

No install, credentials, build, or external assets are required. To publish online, deploy these static files to any static website host.
