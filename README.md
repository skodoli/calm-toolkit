# Calm Toolkit

A single self-contained page (`index.html`, no external libraries, no tracking) with:

- Breathing timer with Start/Stop: cyclic sigh, box breathing 4-4-4-4, slow breathing 4-6; optional tones and vibration; an "I'm panicking now" button that starts a 3-minute cyclic sigh
- 5-4-3-2-1 grounding stepper, muscle release, worry time, behavioural activation
- Four CBT diagrams (five areas, panic cycle, behavioural activation, worry tree), thinking traps, a downloadable thought record
- Evidence summaries: NICE stepped care, exercise, newer treatments (TMS, home tDCS, esketamine, ECT, psilocybin, digital CBT), supplements, medicines
- UK (Scotland and England) and US help lines, plus a full reference list

## Add to skodoli.github.io

1. In your `skodoli.github.io` repo, create a folder `toolkit/` and put `index.html` in it.
2. Commit and push. The page will be live at `https://skodoli.github.io/toolkit/`.
3. Optionally add a link in your main page's nav: `<a href="/toolkit/">Wellbeing toolkit</a>`.

If the site uses Jekyll and the page renders oddly, add an empty `.nojekyll` file to the repo root, or put this at the top of `index.html`:

```
---
layout: null
---
```

## Keep it accurate

Review the content every 6–12 months (crisis numbers, NICE guidance, approval status of new treatments), and update the "Last reviewed" date in the footer.
