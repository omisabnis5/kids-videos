# 🎈 Kids Videos — Little Learners

A cheerful little library of playful, video-style learning pages for toddlers.
The homepage shows a **tile grid**; tapping a tile opens that lesson full-screen.

**Live site:** https://omisabnis5.github.io/kids-videos/

## Lessons

| Tile | Page | Path |
|------|------|------|
| 🔤 ABC Alphabets | Watch a friendly crayon draw every capital letter A–Z | [`/alphabets/`](alphabets/) |
| 🔢 123 Numbers | Draw & count numbers over a range you choose (1–10, 1–20, 1–30, 1–50, or custom) | [`/numbers/`](numbers/) |
| 🔺 Shapes | _coming soon_ | — |
| 🌈 Colors | _coming soon_ | — |

## ABC Tracing Time!

An auto-playing alphabet show for ~3-year-olds. A googly-eyed crayon draws every
**capital letter A–Z** stroke by stroke on real kindergarten writing lines, with:

- 🗣️ a cheerful, kid-friendly voice that changes what it says each letter
- 🎵 the ABC song, slide-whistle "wheee!"s, crayon-scribble sounds and boing-pops
- ✨ sparkle trails, dancing letters, and confetti-star celebrations
- 🍎 "A is for Apple!" picture words for every letter
- ⏮️ ⏯️ ⏭️ 🔁 big toddler-friendly controls, plus an A–Z picker
- 🌗 light & dark themes, and Voice / Sounds toggles for quiet time
- 🏠 a Home button back to the tile grid

### For grown-ups
The numbered dots show stroke order. Pause on any letter and let your child trace
it in the air, on your palm, or on paper with a chunky crayon.

> Tip: the voice sounds friendliest in Chrome or Edge on a phone/tablet, which have
> higher-quality built-in voices.

## Structure

```
index.html            → homepage tile grid
alphabets/index.html  → the ABC tracing lesson
```

Every page is a single self-contained HTML file — no build step, no dependencies.
To add a new lesson: create `mylesson/index.html` and add a matching tile on the homepage.
