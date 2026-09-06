# Jack and Jill - Read & Learn Storybook (PWA)

An interactive, illustrated reading game and nursery rhyme storybook based on the classic nursery rhyme **Jack and Jill**.

Live GitHub Pages App: **[https://sounny.github.io/jack-and-jill/](https://sounny.github.io/jack-and-jill/)**

## ✨ Features

- **📱 Full Progressive Web App (PWA)**:
  - Installable directly to mobile/tablet home screen or desktop.
  - 100% offline capability powered by a Cache-First Service Worker (`sw.js`).
  - Standalone app mode with custom theme colors and icons.
- **📖 5-Act Extended Nursery Rhyme Narrative**:
  - Act 1: *Up the Hill* (The Ascent & The Well)
  - Act 2: *The Tumble & Spill* (Jack's broken crown & Jill's tumble)
  - Act 3: *Trotting Home* (Jack capering back)
  - Act 4: *Old Dame Dob* (Vinegar & brown paper plaster)
  - Act 5: *Smiles & Cured Spills* (Jill's recovery & joyful resolution)
- **🎨 Dynamic Illustrated SVG Storybook Stage**:
  - Interactive landscape: smiling sun, rolling hills, cobblestone path, rustic stone well, cottage, and bucket.
  - Animated character postures for Jack and Jill matching each act of the story.
  - Tap-to-explore interactive touch hotspots.
- **🔊 Zero-Dependency Audio & Speech Engine**:
  - Karaoke-style word-by-word synchronized highlighting with the Web Speech API.
  - Tap any word to isolate pronunciation and view phonics syllable breakdowns (`wa · ter`, `tum · bling`).
  - Native Web Audio API procedural sound synthesizer (bright chimes, splash pops, cartoon tumble whistles, victory fanfare) with 0KB external audio downloads.
- **⭐ Gamified Learning & Star Rewards**:
  - 5 collectible golden stars across the story acts.
  - Rhyme family visual explorer tags (*hill / Jill*, *down / crown*, *caper / paper*).
  - Comprehension mini-tasks with instant feedback and a grand celebratory confetti finale.

## 🛠️ Tech Stack & Philosophy

- **Zero External Dependencies**: Pure HTML5, modern CSS3, vanilla JavaScript, and inline SVG.
- **Native Web Standards**:
  - W3C Web App Manifest (`manifest.json`)
  - Service Worker API (`sw.js`)
  - Web Audio API (Oscillators & Gain nodes)
  - Web Speech API (`speechSynthesis`)
- **Responsive Ergonomics**: Mobile-first design with `touch-action: manipulation`, safe-area-inset padding, and scalable fluid typography.

## 📄 License

MIT