# Brick Builders 🧱

A 3D Lego-style puzzle game made for Jacob and Ben. Pick a model, then drag the brick pieces from the parts bin and snap them into place to build it.

## How to run it

**On a computer:** download this repository (green **Code** button, then **Download ZIP**), unzip it, and double-click `index.html`. It opens in your web browser. No internet or installation is needed.

**On a phone or tablet:** copy the whole folder (with `index.html` and the `lib` folder together) to the device and open `index.html` in its browser. You can also put the folder on any simple web host.

Keep `index.html` and the `lib` folder side by side. The 3D engine (Three.js) is in `lib/three.min.js`. If that file is missing, the game tries to load Three.js from the internet instead.

## What's in it

- **16 builds** in four levels: Easy (100 pts), Medium (200), Hard (350) and Expert (500), from Box with a Face (8 pieces) up to the Castle (38 pieces). T-Rex is Jacob's pick, Box with a Face is Ben's pick and Sleeping Cat is Dad's pick.
- **Snap building:** drop a piece near its spot and it snaps in. If you're stuck for 20 seconds, a glowing ghost shows where a piece goes. The Hint button does the same for 10% of the points.
- **Shark bonus round:** the shark's 8 missile teeth are separate pieces. Once it's built, fire them at moving targets.
- **Modes:** Free build, Timer race, Head-to-head (take turns on one device), Handicap (the stronger player gets more, smaller pieces), Best of five tournament, Sudden death (the loser picks the next build) and a Daily challenge, where the fastest time of the day wins the 👑.
- Works with a mouse or touch. Drag empty space to spin the view, and pinch or scroll to zoom.

Scores, names and crowns are saved in the browser on that device only. There is no online scoreboard.

## Files

- `index.html`: the whole game (HTML, CSS and JavaScript in one file)
- `lib/three.min.js`: Three.js r149, the 3D library (MIT licence, see `lib/THREE_LICENSE.txt`)

Needs a browser with WebGL (any modern Chrome, Safari, Edge or Firefox).
