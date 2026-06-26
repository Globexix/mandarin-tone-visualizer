# mandarin-tone-visualizer

Simple client-side Mandarin tone trainer and pitch visualizer built with the Web Audio API.

It uses an autocorrelation algorithm to detect vocal-fold frequency in real-time and plots your voice directly against the target tone contour.

## Usage

Simply open `index.html` directly in your browser. If your browser restricts microphone access from local files, you can serve the file using a local server:

### Python 3:
```bash
python3 -m http.server 8000
```

### Node.js:
```bash
npx serve -l 8000
```

Then open `http://localhost:8000` in your browser.