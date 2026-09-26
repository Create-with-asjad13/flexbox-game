# Flip & Reveal — a Flexbox memory game

A small memory-style flip-card game built with pure HTML and CSS — no JavaScript.

## What it demonstrates

- **Flexbox** — the board is a `flex-wrap` row of cards that reflows naturally
  at any screen size
- **Box model** — card sizing, spacing and borders
- **Backgrounds** — gradient card fronts
- **3D transforms** — each card flips with `transform: rotateY()` and
  `backface-visibility: hidden`
- **Transitions** — the flip and the hover lift are both eased transitions
- **Pure CSS interactivity** — flipping uses the checkbox hack
  (`:checked + label`); the "Reset cards" button uses a native
  `<button type="reset">` inside a `<form>` to uncheck every card, so no
  JavaScript is needed at all

## How to run

Open `index.html` in any browser. Click a card to flip it, click "Reset
cards" to flip them all back.

## Technologies

- HTML
- CSS

## Author

Mohammad Aszad — https://github.com/Create-with-asjad13
