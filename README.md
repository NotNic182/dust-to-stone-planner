# Dust to Stone Planner

An unofficial fan-made planner for **Moon Sweepers**. It isn't made by or connected to the game's developers.

**Open it:** https://notnic182.github.io/dust-to-stone-planner/

Sketch a production line with dust sources, pressure chambers, stone presses, belts, splitters, mergers and bridges. Then press **Run test** to watch dust turn into sand and stone and see where belts back up.

- The **2:5 block** preset shows a balanced line: 2 pressure chambers feeding 5 stone presses.
- **Share / load code** gives a short code for your layout that you can paste into a comment. Anyone can load it from the same box, or open the "Copy link to this layout" link.

## Numbers used

These were read from the game's code at patch 1.0.5 and haven't been timed in play.

| Thing | Value |
| --- | --- |
| Belt | 1.1 m/s, canisters at least 0.75 m apart (88 a minute at most) |
| Pressure chamber | 5 kg dust → 5 kg sand in 12 s; holds 20 kg dust and 10 kg sand |
| Stone press | 1 kg dust + 1 kg sand → one 2 kg stone in 6 s; holds 12 kg of each input and 10 kg of stone |

Not modelled: power, night-time, vehicles, and each machine's exact port positions.

The whole tool is the single file `index.html`, with no build step.
