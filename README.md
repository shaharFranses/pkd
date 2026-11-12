# PKD

The PKD games site: a plain HTML/CSS portfolio of browser games, served by GitHub Pages at
https://shaharfranses.github.io/pkd/

Each game lives in its own repo and publishes itself to GitHub Pages; this site only links to and embeds them.

| Game | Repo | Live build |
|---|---|---|
| Flick Freight | [flick-freight](https://github.com/shaharFranses/flick-freight) | https://shaharfranses.github.io/flick-freight/ |
| Bakery Logic Puzzle | [tea-bakery](https://github.com/shaharFranses/tea-bakery) | https://shaharfranses.github.io/tea-bakery/ |

## Layout
- `index.html` — home page with a card per game
- `games/<slug>/index.html` — a play page per game (embedded on desktop, full-screen button on phones)
- `assets/style.css` — styles; tokens follow the PKD Design System
- `assets/img/` — card art, taken from each game's cover art

## Adding a game
1. Make sure the game's repo publishes to `https://shaharfranses.github.io/<repo>/`.
2. Add a 960×540 cover to `assets/img/<slug>.jpg`.
3. Copy a card in `index.html` and a folder in `games/`, then change the name, text and URL.

## Design rules
- **NO YELLOW** anywhere in the site UI.
- The logo is a tilted pill with an ink outline, a hard shadow and lowercase "pkd"; only its fill and colors change per game.
- Fonts: Bagel Fat One (display), Nunito (body). All links are relative, so the site keeps working if it moves to a custom domain.
