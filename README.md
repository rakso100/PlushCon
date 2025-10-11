PlushCon Web App (Frontend Only)

Features

- Countdown to a customizable date/time (saved in `localStorage`).
- Simple, touch-friendly plushy game (tablet and laptop friendly).
- Upload videos and .txt files and display them nicely, stored locally in your browser using IndexedDB.

Run Locally

- Open `public/index.html` directly in a modern browser, or serve the `public/` folder with any static server.
- No backend or Node server required.

Structure

- `public/` — single-page app with countdown, game, and media gallery.

Notes

- Media uploads are saved to your browser’s IndexedDB storage on that device.
- Supported: videos (mp4/webm/mov) and `.txt` files.
- You can delete items from the gallery; files never leave your device.
