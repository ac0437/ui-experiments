# Cube Twister 3D

A 3D Rubik's Cube game that runs in the browser, built with [Three.js](https://threejs.org/).

Open `index.html` in a browser to play. It needs an internet connection, because Three.js, the font and the hint solver load from CDNs.

## Features

- **Drag to turn:** press on a sticker and drag to turn that layer, middle slices included. Drag off the cube to look around, and scroll to zoom.
- **Keyboard:** `U D L R F B` turn the faces (hold Shift for counter-clockwise), `M E S` turn the middle slices, `H` gives a hint, and `Ctrl/⌘+Z` undoes a move.
- **Game:** scramble the cube, then race the timer. The game counts your moves and saves your best time in the browser.
- **💡 Hint:** works out a short solution from the current cube (using [cubejs](https://github.com/ldez/cubejs), a Kociemba two-phase solver running in a web worker), shows the next move, flashes the layer to turn, and offers a "Do it" button.
- **Auto-solve:** rewinds every move to put the cube back together.
