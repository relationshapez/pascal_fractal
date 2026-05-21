# Relationshapez: Pascal Triangle

This project is a single-file HTML exploration of Pascal's Triangle. Each entry of the triangle is represented by a circle:

- Odd entries are filled in.
- Even entries are left clear.

As more rows are displayed, the odd/even pattern begins to resemble the Sierpiński triangle.

<https://relationshapez.github.io/pascalfractal/>

## Files

- `index.html` — the main interactive browser tool
- `README.md` — repository overview and usage guide
- `LICENSE` — MIT license text

## How to Use

Open `index.html` in a web browser, or use the hosted link above after the project is published.

The controls are designed to work on both desktop and mobile devices.

### Controls

- **Animate**: Builds the triangle one row at a time.
- **Pause**: Stops the animation at the current row.
- **Reset**: Returns the display to 2 rows and resets the view.
- **◀ / ▶**: Step backward or forward one row when the animation is paused.
- **Rows**: Sets the maximum number of rows to display. The smallest value is 2.
- **Speed**: Adjusts the animation speed.

At the slowest speed, each new row first appears as numbers from Pascal's Triangle. The numbers then fade into the odd/even circle coloring.

## Zoom and Pan

The display supports zooming and panning:

- On a desktop, use the mouse wheel or trackpad to zoom.
- Click and drag to pan.
- On a touch screen, drag to pan and pinch to zoom.

The triangle is automatically scaled so that the total displayed triangle stays a fixed size as the number of rows changes.

## Classroom Notes

This activity is useful for connecting Pascal's Triangle, parity, modular arithmetic, and fractal patterns.

A natural student question is:

> Why does coloring the odd entries in Pascal's Triangle begin to form the Sierpiński triangle?

This can lead to a discussion of how each entry in Pascal's Triangle is built from the two entries above it, and how odd/even addition follows a simple pattern.

## License

Copyright (c) 2026 Alan Miller.

This project is released under the **MIT License**.

See the [`LICENSE`](LICENSE) file for the full license text.
