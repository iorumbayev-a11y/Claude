# Flow Kaleidoscope

A tiny, dependency-free generative art toy. Particles drift through a 2D noise field and are drawn with kaleidoscope symmetry, leaving glowing trails behind.

Everything — rendering, the noise function, and even the GIF encoder — lives in a single `index.html` file. No build step, no dependencies.

## Running it

Just open `index.html` in a browser.

## Controls

| Control | Effect |
| --- | --- |
| Symmetry | Number of mirrored kaleidoscope segments |
| Particles | How many particles are simulated at once |
| Speed | Particle movement speed |
| Trail length | How slowly trails fade out |
| Field scale | Zoom level of the underlying noise field |
| Mouse pull | How strongly particles are attracted to the cursor |
| Hue drift | How fast colors shift over time |

- Drag the mouse to steer particles, click to repel them
- Press **H** to hide the control panel
- **New palette** picks a new random color scheme
- **Clear** wipes the canvas
- **Save PNG** downloads the current frame
- **Pause** freezes the simulation
- **Record GIF** captures a short animated GIF of the current scene
