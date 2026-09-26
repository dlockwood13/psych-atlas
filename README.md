# Psych Atlas

A single place to learn and keep everything from a BSc Psychology and an MSc Forensic Psychology, extended to cover the rest of the discipline: 8 areas, 45 modules, 465 topics and 5,106 retrieval cards.

Live app: https://dlockwood13.github.io/psych-atlas/

## What is in it

- **25 course modules** built from the author's own lecture slides, notes, readings and coursework (MSc, BSc Years 1 to 3, and practice and pathway material). Each topic lists the files it came from.
- **20 extension modules** written from current published evidence to fill the gaps a coverage review found against BPS core knowledge, the seven HCPC practitioner titles and UK practice essentials: clinical psychology and mental health, the specialities the degree did not cover (health, counselling, educational, sport and exercise, wider fields), core areas it touched lightly, and UK ethics, law and forensic practice as of 2026. Each topic lists its references in APA 7 style.
- **Key learnings** at the top of every module: a five-to-eight point teaching snapshot of what to carry forward.
- **Coverage map** (`#/coverage` in the app): the gap analysis, area by area, before and after, with the areas that are still thin.

## How it teaches

- **Retrieval practice**: every card makes you recall before you see the answer (Yang et al., 2021).
- **Spacing and successive relearning**: an FSRS-6 scheduler brings each card back when recall is predicted to fall to your target, 90% by default (Carpenter et al., 2022; Rawson & Dunlosky, 2022; Ye et al., 2022).
- **Interleaving**: reviews mix modules so similar concepts are told apart (Sana & Yan, 2022).
- **Read, then retrieve**: new cards come from the modules you choose, in taught order; *Up next to learn* points to the next topic's notes.
- **Teach-back (Feynman)**: explain a topic from memory, then compare with the notes and rate your gaps (Lachner et al., 2022).

Full references are on the in-app page *How this app teaches*.

## Install

- **iPhone or iPad**: open the link in Safari, tap Share, then *Add to Home Screen*.
- **Android**: open the link in Chrome and tap *Install app*.
- **Mac or PC**: open it in Chrome or Edge and use the install icon in the address bar.

It works offline after the first visit.

## Your data

Progress is stored only in the browser on each device, under keys starting `psyatlas.v2.`. Nothing is sent anywhere. Use **Settings, Export backup** before clearing browser data or switching devices, then **Import backup** on the new device. Updating to a new version keeps your progress; new modules are added to your module list automatically.

## About the content

Course topics, notes, cards and citations were generated from the source files listed on each topic page, then checked automatically: every cited author and year was matched against the source text, and every figure was compared with the sources. Some sources were cut short or were image-only slides, so a few lectures are thinner than others.

Extension topics were written from published research, guidelines and legislation. Every reference was checked in September 2026: 1,675 of 1,831 matched a Crossref record by title, author and year (DOIs were added or corrected for 759), 54 books were found in a library catalogue, 92 are official documents such as NICE guidance and legislation, and 10 classic books and chapters were confirmed by hand. None had to be removed. UK law, guidance and service facts are correct as of September 2026 and will date, so re-check anything time-sensitive before relying on it in practice.

If a card looks wrong, use **Flag card** on the answer side; it is suspended until restored in Settings.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole app (React 18, htm and marked are inlined; no build step to run) |
| `kb.js` | The knowledge base |
| `sw.js` | Service worker for offline use |
| `manifest.webmanifest`, `*.png` | Install metadata and icons |
