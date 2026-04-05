# Heart Nebula Gallery

A static interactive showcase page built with Three.js and MediaPipe hand gestures.

## Features

- 3D heart / nebula particle transitions
- Gesture controls for scatter, gather, and photo focus
- Built-in gallery photos (no manual upload required)
- Built-in background music
- Fullscreen-ready display mode for exhibitions
- One-key presentation shortcut: Shift+F enters fullscreen and hides UI panels

## Keyboard Shortcuts

- Shift+F: enter fullscreen and hide the UI at the same time

## Run Locally

Use any static server. Example:

```bash
npx http-server . -p 5500 -c-1
```

Then open:

```text
http://127.0.0.1:5500/index.html
```

## Entry Files

- Main source: index.html
- Legacy entry links heart.html and 爱心.html now redirect to index.html

## Deploy to GitHub Pages

1. Push this project to a GitHub repository.
2. In repository settings, enable **Pages**.
3. Set source to **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`.
5. Save, then wait for Pages build to finish.

Your site will be available at:

```text
https://<your-github-username>.github.io/<repo-name>/
```

## License

MIT
