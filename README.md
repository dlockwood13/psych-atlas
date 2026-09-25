# Psych Atlas

A single place to learn and keep everything from a BSc Psychology and an MSc Forensic Psychology: 5 areas, 25 modules, 289 topics and 3,421 retrieval cards, built from the author's own lecture slides, notes, readings and coursework.

Live app: https://dlockwood13.github.io/psych-atlas/

## How it teaches

- **Retrieval practice**: every card makes you recall before you see the answer (Yang et al., 2021).
- **Spacing and successive relearning**: an FSRS-6 scheduler brings each card back when recall is predicted to fall to your target, 90% by default (Carpenter et al., 2022; Rawson and Dunlosky, 2022; Ye et al., 2022).
- **Interleaving**: reviews mix modules so similar concepts are told apart (Sana and Yan, 2022).
- **Read, then retrieve**: new cards come from the modules you choose, in taught order; *Up next to learn* points to the next topic's notes.
- **Teach-back (Feynman)**: explain a topic from memory, then compare with the notes and rate your gaps (Lachner et al., 2022).

Full references are on the in-app page *How this app teaches*.

## Install

- **iPhone or iPad**: open the link in Safari, tap Share, then *Add to Home Screen*.
- **Android**: open the link in Chrome and tap *Install app*.
- **Mac or PC**: open it in Chrome or Edge and use the install icon in the address bar.

It works offline after the first visit.

## Your data

Progress is stored only in the browser on each device, under keys starting `psyatlas.v2.`. Nothing is sent anywhere. Use **Settings, Export backup** before clearing browser data or switching devices, then **Import backup** on the new device.

## About the content

Topics, notes, cards and citations were generated from the source files listed on each topic page, then checked automatically: every cited author and year was matched against the source text, and every figure was compared with the sources. Some sources were cut short or were image-only slides, so a few lectures are thinner than others. If a card looks wrong, use **Flag card** on the answer side; it is suspended until restored in Settings.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole app (React 18, htm and marked are inlined; no build step to run) |
| `kb.js` | The knowledge base |
| `sw.js` | Service worker for offline use |
| `manifest.webmanifest`, `*.png` | Install metadata and icons |
