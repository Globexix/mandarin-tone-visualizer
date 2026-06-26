# mandarin-tone-visualizer

Simple client-side Mandarin tone trainer and pitch visualizer built with the Web Audio API.

The live chart is a short delayed preview. Final scoring uses an offline pitch pass over the recorded or uploaded audio: it extracts voiced pitch candidates, selects the strongest vowel segment, smooths likely octave-tracking errors, and compares the resulting contour with the selected Mandarin tone target.

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