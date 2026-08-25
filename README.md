# David + Michelle Strength

Free installable workout PWA for iPhone.

## Publish free with GitHub Pages
1. Create a free GitHub account.
2. Create a new **public** repository, e.g. `strength-tracker`.
3. Upload every file in this folder to the repository root.
4. Go to **Settings → Pages**.
5. Choose **Deploy from a branch**.
6. Choose `main` and `/ (root)`, then Save.
7. Open the HTTPS GitHub Pages URL on your iPhone in Safari.
8. Tap **Share → Add to Home Screen → Add**.

## Data
Workout history is stored locally on the device using IndexedDB. David and Michelle stay separate on the same device, but two different iPhones will not sync automatically.

Use **More → Export backup** periodically. Cloud sync can be added later.

## Local testing on Windows
From this folder:
`python -m http.server 8000`
Then open `http://localhost:8000`
