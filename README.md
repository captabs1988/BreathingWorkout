# Breathe 🫁

A lightweight, no-dependency breathing timer app built with vanilla HTML, CSS, and JavaScript. Works in any modern browser and installs as a home screen app on iPhone and Android.

---

## Features

- Animated breathing orb that expands and contracts with each phase
- Full-duration audio cues for inhale and exhale — meditate eyes-closed
- Customisable timings for all 4 phases: **Inhale / Hold / Exhale / Relax**
- Sound options per phase: rising tone, falling tone, singing bowl, white noise, or silence
- Adjustable cycle count
- 10 famous breathing patterns pre-loaded as presets
- Save your own custom templates
- Export & import templates as `.json` — shareable and portable
- iPhone home screen ready (no browser chrome when added to home screen)
- Dark mode, mobile-first design

---

## Presets included

| Pattern | Timing (In-Hold-Ex-Relax) | Best for |
|---|---|---|
| 4-7-8 (Dr. Weil) | 4-7-8-0 | Sleep, anxiety relief |
| Box Breathing (Navy SEAL) | 4-4-4-4 | Focus, stress control |
| Coherent / Resonant | 5-0-5-0 | Heart rate variability |
| Physiological Sigh | 4-2-8-0 | Quick calm |
| Wim Hof Power Breath | 2-0-2-0 × 30 | Energy, cold exposure |
| Alternate Nostril | 4-4-4-4 | Balance, yoga |
| 2-1-4-1 Relaxation | 2-1-4-1 | General relaxation |
| Tummo | 4-0-8-0 | Deep meditation |
| Sitali Cooling Breath | 6-4-6-2 | Cooling, hot climates |
| Equal Breathing | 4-0-4-0 | Beginner, daily calm |

---

## Usage

### Run locally
Just open `index.html` in any browser. No server needed.

### Host on GitHub Pages
1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, root folder
4. Your app will be live at `https://yourusername.github.io/breathe-app`

### Add to iPhone home screen
1. Open the GitHub Pages URL in Safari
2. Tap the **Share** button
3. Tap **Add to Home Screen**
4. It will launch full-screen like a native app

---

## Template export / import

- Tap **Templates → Export All** to download a `breathe-templates.json` file
- Tap **Import JSON** to load templates on any device
- Custom templates are saved to `localStorage` in the browser

---

## Tech stack

| Layer | Tech |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (CSS variables, dark mode) |
| Logic | Vanilla JavaScript |
| Audio | Web Audio API |
| Storage | localStorage |
| Dependencies | None |

---

## Browser compatibility

| Browser | Status |
|---|---|
| Safari iOS (iPhone 13+) | ✅ Full support |
| Chrome Android | ✅ Full support |
| Chrome Desktop | ✅ Full support |
| Firefox | ✅ Full support |
| Safari macOS | ✅ Full support |

---

## License

MIT — free to use, modify, and share.

---

Made with focus and a few deep breaths.
