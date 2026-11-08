# William's Learning Practice

A simple, low-pressure learning app for a 10-year-old with dyslexia. It covers times tables, long division, basic algebra and shape recognition in one self-contained web page.

**Live site:** https://cmsdroff.github.io/William/

## What's inside

| Section | What it does |
|---|---|
| **Times tables** | Tables 3, 4, 6, 7, 8, 12 and Mix. Dot arrays split into two colours (build from easier facts), a "Show the trick" button, big multiple-choice answers, read-aloud, a colour-coded chart, and missed facts that come back more often. No timers. |
| **Long division** | Guided one step at a time using Divide, Multiply, Subtract, Bring down, Repeat (Dad, Mum, Sister, Brother, Rover). "Watch me" and "Your turn" modes, 2 or 3 digits, optional remainders, and a times-table strip for the divisor. |
| **Algebra** | Missing-number puzzles in three levels: add and take away, times and divide, and two-step. Bar-model visuals, "Show the trick" hints, and a switch between a "?" box and the letter x. |
| **Shapes** | Flash cards and a quiz for 15 flat shapes, from circle and oval to triangle, square, rhombus, parallelogram, trapezium, kite, and pentagon up to decagon. Each has a memory tip, the number of sides and corners, and read-aloud. |

## Learning approach

- Multisensory: see it, hear it, tap it.
- Patterns and strategies instead of rote memorising.
- Build from known facts and one idea at a time.
- Short, frequent practice with no timers and no penalty for wrong answers.
- Stars celebrate effort; missed items are repeated gently.

## Dyslexia-friendly design

Lexend font, soft off-white background, wide letter spacing, no italics, large tap targets, colour-coded steps, and a light/dark toggle.

## Technical notes

- Everything is in `index.html`. There is no build step and no dependencies, apart from the Lexend font from Google Fonts (the page still works with a fallback font if it can't load).
- Progress (stars and missed items) is saved in the browser's local storage, so it is separate on each device and browser.
- Hosted with GitHub Pages: Settings, Pages, Deploy from a branch, `main`, `/(root)`.
- To update, replace `index.html`, commit, and the site refreshes in a minute or two.

## Ideas for next steps

3D shapes (cube, sphere, cone, pyramid), 9 and 11 times tables, a mastered-facts tracker, 2-digit divisors, fractions, and printable practice sheets.
