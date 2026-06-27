# 🐴 Ring Ready

A pocket coach that helps a young Hunter/Equitation rider **find her way around the show ring** — learn courses, build spatial awareness, judge distances, and master the terminology.

Built as an **installable, offline-first PWA**: a single `index.html` (HTML + CSS + JS) with no build step and no dependencies. All data (her name, saved courses) stays on the device in `localStorage` — no accounts, no backend, no tracking.

## Sections

- **Courses** — pick a course, then **Study** it (numbered jumps, the riding path drawn out, step-by-step "ride it like this"), **Trace** the whole track with your finger to learn the route and direction, or **Order**-quiz by tapping the jumps from memory. Ships with realistic starter courses.
- **Spatial Skills** — the heart of the app:
  - *Which Way?* — orientation drills: which rein you're on, which side is the inside, near rail vs far rail, all anchored to a fixed **in-gate**.
  - *Stride Counter* — judge how many strides are in a line, with the 12‑ft canter strides drawn out so distance becomes a felt thing.
- **Build** — tap the ring to drop jumps in order, name it, pick a level, and save it. Saved courses are studyable, traceable, and quizzable like the built-ins.
- **Ring** — a labeled diagram of the rail, centerline, quarter lines, and diagonals, plus a tap-the-line quiz.
- **Terms** — flip-flashcards and a multiple-choice quiz for the core hunter terminology.
- **Patterns** — the common course shapes (outside line, diagonal line, single, bending line, opening/closing circle) with a mini diagram and a riding cue.

## Add to your iPhone Home Screen

1. Open the site in **Safari** on the iPhone.
2. Tap the **Share** button (the square with the up-arrow).
3. Scroll down and tap **Add to Home Screen**, then **Add**.
4. Launch it from the new horseshoe icon — it runs full-screen and works offline.

## Files

```
index.html                 the whole app
manifest.json              PWA manifest
sw.js                      service worker (offline app shell)
icons/                     horseshoe app icons (192, 512, maskable, apple-touch)
```
