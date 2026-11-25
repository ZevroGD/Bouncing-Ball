# Physics Box

A browser-based bouncing-ball physics demo. A ball moves inside a resizable viewport box using a fixed-step simulation, elastic wall collisions and optional gravity settings in the source.

## Play

Open `index.html` in a modern browser. Drag the ball with a mouse or touch, then release it to throw it. The release velocity is estimated from recent pointer movement and capped to keep extreme flicks under control.

The simulation uses a fixed physics timestep and interpolated rendering so the motion is less dependent on the display's frame rate. The current defaults use zero gravity and perfectly elastic wall bounces.

## Development

There is no build step or external JavaScript dependency. The demo is implemented in `index.html`; edit it and reload the page to test changes.
