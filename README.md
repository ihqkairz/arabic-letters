# Arabic Letters

A practice site for reading the Arabic alphabet.

Live at: https://ihqkairz.github.io/arabic-letters

Three tabs, meant to be used in order:

- **Reference** — all 28 letters with their names. Tap one to hear it and see all four of its shapes.
- **Recall** — a letter with no name attached. Say it out loud, then tap to check yourself.
- **Drill** — multiple choice. Wrong answers come from letters with the same skeleton, so you have to look at the dots.

The gold strokes in a letter are the *joins*, not the letter itself. Separating those
two things in your eye is the whole point.

## Audio

Pronunciation is recorded by a native Egyptian Arabic speaker. The clips live in `audio/`,
one per letter, named after the letter: `audio/qaf.mp3`, `audio/ayn.mp3` and so on.

If a clip is missing, the page falls back to the device's own Arabic voice. Many phones
have no Arabic voice installed, which is why the recordings matter.

## Running it

Open `index.html` in a browser. There is nothing to install.

## Editing it

Everything except the audio lives in that one file.

- **Colours** — the `:root` block at the top. Change a value, refresh, see it everywhere.
- **Content** — the `LETTERS` array. The only place the app stores what it knows.
- **Behaviour** — the functions below it.

## To do

- [ ] Save the score so it survives a page reload (`localStorage`)
- [ ] Add the short vowel marks (fatha, kasra, damma)
