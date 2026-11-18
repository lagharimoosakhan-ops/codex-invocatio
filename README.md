# Codex Invocatio

*Invocatio — M. Laghari, MMXXVI*

A single HTML file that is the artwork itself.

A Renaissance mage, inspired by Invoker from Dota 2, calls on his elemental spells on a page from an imagined Leonardo da Vinci notebook, set in the age of AI.

**▶ https://lagharimoosakhan-ops.github.io/codex-invocatio/**

## The idea

How far can one idea go with AI?

I described the vision: a mage, da Vinci's notebook, the age of AI, built entirely in HTML. I directed the result through a handful of prompts with Microsoft Copilot, and I didn't write any of the code by hand.

## How it's made

- **No images and no canvas.** Everything is HTML, CSS and inline SVG.
- **Pixel by pixel.** The mage is made of **3,804 individual `<div>` elements**, one for each pixel.
- **Hand-drawn feel.** The ink strokes draw themselves, with a slight tremor added to each line.
- **One file.** A small amount of JavaScript times the spells. The only external resource is Google Fonts.

## The sequence

1. **Sketch:** ink draws ruins, a shrine, a blossom tree and Vitruvian geometry.
2. **Printing:** the mage is printed row by row.
3. **Awakening:** colour returns, circuits light up, a neural network fires, and three spheres appear: *Glacies* (ice), *Fulmen* (storm) and *Ignis* (fire).
4. **Invocations:**
   - **Columna Solis:** a column of sunlight
   - **Stella Cadens:** a falling, rolling meteor
   - **Turbo Venti:** a whirlwind
   - **Pulsus Fulminis:** a lightning pulse
5. **Settle:** the page fades back to ink, and the loop starts again.

## Controls

| Key | Action |
|---|---|
| `Space` | Replay from the start |
| `1`–`4` | Cast a spell |

Works best in Chrome or Edge with hardware acceleration turned on.

## Disclaimer

This is a non-commercial fan tribute. The mage is an original character inspired by Invoker. Dota 2 and Invoker are trademarks of Valve Corporation. This project is not affiliated with or endorsed by Valve.
