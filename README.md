# Flappy Bird (HTML5 Canvas)

A lightweight Flappy Bird style game in a single `index.html` file — no images, no libraries, no build step.

## Play
- Open `index.html` in any modern browser.
- **Desktop:** Space / ↑ / mouse click to flap.
- **Mobile:** tap the screen (page scrolling and zoom are blocked during play).

## Features
- Gravity + flap physics (frame-rate independent)
- Endless pipes with random gap heights
- Collision with pipes, ground and ceiling
- Score, best score (saved in localStorage) and medals
- Start screen, Game Over screen, Restart button
- Responsive canvas that scales to any screen, sharp on high-DPI displays

## Host on GitHub Pages
1. Push this folder to a GitHub repository.
2. Settings → Pages → Deploy from branch → `main` / root.
3. Open `https://<your-username>.github.io/<repo-name>/`.

## Android packaging (later)
The game is fully client-side, so it can be wrapped with Capacitor, Cordova or a Trusted Web Activity (Bubblewrap) by pointing the web root at this folder.
