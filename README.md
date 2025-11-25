Fullscreen image demo

Open `index.html` in a browser (double-click the file or use a local server) to see `img/niklas.jpg` displayed full-screen and cropped as needed.

Notes:

- The page uses CSS `object-fit: cover` so the image fills the viewport while preserving aspect ratio.
- If `img/niklas.jpg` is missing, the background color (#111) will be visible as a fallback.
- For best results on mobile, serve the files over a local server (e.g., `python -m http.server`) to avoid certain file:// restrictions.
