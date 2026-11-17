# FunKid Games 🎮

A small multi-game website. The landing page (`index.html`) lets players pick a game, and each game lives in its own folder under `games/`.

| Game | Folder | What it is |
|------|--------|------------|
| 👻 Lights Out Sleepover | `games/lights-out-sleepover/` | A spooky action game. Escape the goo monsters, save Sam from the underworld, and beat the Devil King, the Devil Prince and the Candy Man. 1–2 players. |
| ♟ Chess | `games/chess/` | Full-rules chess (castling, en passant, promotion, checkmate, stalemate and draws). Play a friend on the same screen, or the computer on Easy, Medium or Hard. |
| 🌰 Oakville Quest | `games/oakville-quest/` | A side-scrolling platformer about the history of Oakville, Ontario. Walk the town map, clear 7 history worlds, find the History Scrolls and defeat the Fog of Forgetting. Progress is saved in the browser. |
| 🏀 Rise to the Rim | `games/rise-to-the-rim/` | A basketball career game. Create a player, play 3-on-3 games with your team, train in drills, spend skill points and climb from Rookie to the max ranking, Legend. Then keep playing seasons and win championships. Progress is saved in the browser. |
| 🧇 Upside Down Merge | `games/upside-down-merge/` | A drop-and-merge puzzle with a Stranger Things character ladder (Will up to Eleven), drawn as original neon circles with emoji icons. Making Eleven shows a thank-you to Alessandro and Chiara. Best score is saved in the browser (localStorage key `upsideDownMergeBest`). |
| 🐍 Gobble King | `games/gobble-king/` | An arena snake game against computer snakes. Gobble food, trap snakes (a snake pops when its head hits another snake's body) and stay King (the biggest snake) as long as you can. Gobbling a snake gives a 20-second power-up: Turbo, Shield, Magnet or Double Food. Easy, Normal and Hard. Best reign is saved in the browser (localStorage key `gobbleKing`). |
| 🥋 Karate Bot Clash | `games/karate-bot-clash/` | A 1-on-1 karate fighting game against 6 computer bots (Tin Trainee up to Grand Master Gear). Hits charge a special meter; winning a fight (best of 3 rounds) gives 1 Fight Token to spend on moves, specials, skills and skins. Beating a new bot unlocks the next one and a new belt color. Progress is saved in the browser (localStorage key `karateBotClash`). |

Every game is a single self-contained `index.html`. Graphics, music and sound are drawn and synthesized in code.
There is no build step and there are no dependencies.

## Add a new game

1. Create `games/<your-game>/index.html`.
2. Add a card for it in the root `index.html`, linking to `/games/<your-game>/`.
3. Add a "⬅ All games" link back to `/` inside the game.

## Run locally

Serve the folder with any static server so the `/games/...` links work, for example:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy to Vercel

1. In Vercel, choose **Add New → Project** and import this repository.
2. Leave **Framework Preset** as **Other**, with no build command and no output directory, then click **Deploy**.

Or from a terminal: `npx vercel --prod`.

## Notes

Online invite-only rooms in Lights Out Sleepover only work when the game is opened on claude.ai.
Solo and 2-player work everywhere, including on Vercel.
