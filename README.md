# DSP Interactive

Interactive demos for a graduate course in **Digital Signal Processing**.

**Live site:** <https://lovejump.github.io/dsp-interactive/>

## What is here

- **Nine chapter demos** — `CH-00.html` … `CH-08.html`. Each one asks a single question
  (for example, *does zero-padding improve resolution?*) and lets you move the controls
  until the answer becomes visible.
- **Eleven toys** — `toys/`. Small, playful experiments: see your voice as a spectrogram,
  watch an FFT pipeline, draw a filter and hear music run through it, read a motor's current,
  and more. The toy wall at `toys/` links them all.

Every page is a **self-contained HTML file**: all scripts and styles are inlined, there are
no network requests, no build step, and no tracking. You can copy a single `.html` file to a
USB stick and it still works.

## Run it locally

Open `index.html` directly, or serve the folder (recommended, because microphone and camera
access require `localhost` or HTTPS):

```bash
python -m http.server 8000
```

Then open <http://localhost:8000/>.

## License

MIT — see [LICENSE](LICENSE).
