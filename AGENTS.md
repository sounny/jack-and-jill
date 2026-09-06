# AGENTS.md

## Project

This repository contains the **Jack and Jill** educational reading and nursery rhyme game, built as a standalone Progressive Web App (PWA) deployable on GitHub Pages.

## Structure

- Keep the main game in `index.html` at the repository root.
- Keep PWA configuration in `manifest.json`, offline worker in `sw.js`, and vector/raster icons in `icons/`.
- Keep the project simple, zero-dependency, and suitable for GitHub Pages.
- Do not add external heavy asset packs or third-party tracking scripts.
- The `reference/` folder is reserved for reference notes and conceptual guidance only.

## Game Design & Ergonomics

- The game is child-friendly, touch-friendly, and accessible for early readers.
- Reading, phonics, and rhyming exploration are central to the experience.
- Controls must maintain high contrast and minimum 48px+ touch targets with `touch-action: manipulation`.
- Voice reading, phonics pronunciation, and word-by-word karaoke highlighting are core features.
- Dynamic SVG scenes provide visual storytelling without bloated raster downloads.

## Technical Rules

- **Offline PWA**: Ensure all core assets (`index.html`, `manifest.json`, `sw.js`, and `icons/*`) remain cached and functional offline.
- **Audio Synthesizer**: Use the procedural native Web Audio API for sound effects (chimes, bubbles, fanfare) to avoid external audio file loading issues.
- **Speech Synthesis**: Use `window.speechSynthesis` with boundary checking (`onboundary`) for word tracking.
- Test responsive layouts on desktop, tablet, and mobile screens (including safe-area-insets).
- Preserve working features and commit with clear, concise messages.

## GitHub Pages

The repository uses the `main` branch. The intended Pages source is the repository root, with `index.html` as the entry point.
