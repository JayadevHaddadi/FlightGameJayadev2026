# Zero-G Flight

A minimal browser flight game made with Three.js. You fly a futuristic plane around a planet with no gravity and no friction. Collect stars between tall neon cities, drift with the brake, and fly around the planet forever.

**Play it:** https://jayadevhaddadi.github.io/FlightGameJayadev2026/

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000 and click to start.

## Controls

| Key | Action |
| --- | --- |
| Mouse | Steer (turn and pitch) |
| W / S | Thrust / reverse |
| Shift | Boost (5 s of fuel, refills in 5 s) |
| Space | Hard brake / drift (uses boost fuel) |
| Q / E | Tip the plane on its side (left / right). Double-tap for a barrel roll |
| M | Music on/off |
| Esc | Release the mouse |

Everything is in `index.html`. Sounds and music are generated in code with the Web Audio API, so there are no asset files.
