# Canyon Slide

A 3D dirt-buggy racer in one HTML file, in the style of 1990s buggy racers like Powerslide (1998). The art and track are original.

- Two tracks: Red Canyon (day) and Night Canyon (lanterns, stars, headlights)
- Turbo: powersliding and the glowing arrow pads fill the meter (blue ring on the speedometer); press Shift to fire it
- 8 buggies, 3 or 5 laps, start lights, position, lap, timer, gear and speedometer HUD
- Slidey arcade handling: throttle, brake/reverse and a handbrake for powerslides
- A desert canyon track with a jump, a rock arch and a rope bridge, plus skid marks and dust
- Engine, skid and wind sound made in the browser (no audio files)
- Touch controls on phones

## Play

Open `index.html` in a browser through a local web server (three.js loads from the jsDelivr CDN), for example:

```
python3 -m http.server 8000
```

then visit http://localhost:8000.

## Controls

| Key | Action |
| --- | --- |
| Up / W | Gas |
| Down / S | Brake, then reverse |
| Left Right / A D | Steer |
| Space | Handbrake slide |
| Shift / X | Turbo |
| R | Put the car back on the track |
| C | Change camera |
| M | Sound on/off |
| P / Esc | Pause |

The file is written without `<!doctype>`/`<head>`/`<body>` so it can be published as a claude.ai artifact, which adds them.
