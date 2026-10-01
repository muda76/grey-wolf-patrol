# Grey Wolf Patrol

A WWII U-boat simulation that runs in the browser, in the style of *Silent Hunter*. It's one self-contained HTML file with no build step and no dependencies apart from Google Fonts.

## Play

Open `index.html` in a browser, or serve the folder with any static host (GitHub Pages works).

## What's in it

- **Nav chart.** Pan, zoom, and click to steer. It shows convoy reports from headquarters, hydrophone bearings and torpedo tracks.
- **Periscope and bridge binoculars.** Ship silhouettes are drawn to scale by range and angle on the bow, with day and night lighting, smoke, fires and sinking ships.
- **Torpedo data computer.** Lock a target and the solution (range, AOB, speed, gyro angle, run time) gets more accurate the longer you observe.
- **Torpedoes.** G7a steam torpedoes are fast but leave a wake. G7e electric ones are slower with no wake. You set run depth and salvo size, and there are 4 bow tubes and 1 stern tube with reload timers. Duds and arming distance are modelled.
- **Boat model.** Diesel and battery propulsion, dive and crash dive, crush depth, flooding, damaged systems with repair timers, and silent running.
- **Escort AI.** Escorts find you by ASDIC pings, hydrophones and lookouts. They attack with depth-charge patterns and gunfire, and will ram. Going deep and quiet is how you shake them.
- **Campaign.** Successive convoys get larger and better escorted. The game ends with a patrol tonnage report, or with the loss of the boat.
- **Modes.** Recruit and Veteran.

## Controls

| Key | Action | Key | Action |
|---|---|---|---|
| W / S | Engine telegraph | A / D | Helm ±5° (Shift ±1°) |
| P | Periscope depth | B | Surface |
| C | Crash dive | R / F | Depth ∓10 m |
| U | Raise/lower scope | V | Chart ↔ periscope |
| ← / → | Rotate scope | Z | Scope zoom |
| L | Lock target | Space | Fire |
| 1–4 | Salvo size | X | Silent running |
| [ / ] | Time compression | Esc | Pause |

An original fan-made game. Not affiliated with or using assets from the Silent Hunter series.
