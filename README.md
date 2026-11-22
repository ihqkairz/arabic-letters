# Arabic Letters

A practice site for reading the Arabic alphabet.

Two modes:

- **Learn** — all 28 letters. Tap one to see how its shape changes depending on where it sits in a word.
- **Drill** — a shape appears, you pick which letter it is. Keyboard 1–4 to answer, space for the next one.

The gold strokes in a letter are the *joins*, not the letter itself. Separating those
two things in your eye is the whole point.

## Running it

Open `index.html` in a browser. There is nothing to install.

## Editing it

Everything lives in that one file.

- **Colours** — the `:root` block at the top. Change a value, refresh, see it everywhere.
- **Content** — the `LETTERS` array. The only place the app stores what it knows.
- **Behaviour** — the functions below it.

## To do

- [ ] Save the score so it survives a page reload (`localStorage`)
- [ ] Add the short vowel marks (fatha, kasra, damma)
