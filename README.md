# FunKid Games 🎮

A small multi-game website. The landing page (`index.html`) lets players pick a game, and each game lives in its own folder under `games/`.

| Game | Folder | What it is |
|------|--------|------------|
| 👻 Lights Out Sleepover | `games/lights-out-sleepover/` | A spooky action game. Escape the goo monsters, save Sam from the underworld, and beat the Devil King, the Devil Prince and the Candy Man. 1–2 players. |
| ♟ Chess | `games/chess/` | Full-rules chess (castling, en passant, promotion, checkmate, stalemate and draws). Play a friend on the same screen, or the computer on Easy, Medium or Hard. |
| 🌰 Oakville Quest | `games/oakville-quest/` | A side-scrolling platformer about the history of Oakville, Ontario. Walk the town map, clear 7 history worlds, find the History Scrolls and defeat the Fog of Forgetting. Progress is saved in the browser. |
| 🏀 Rise to the Rim | `games/rise-to-the-rim/` | A basketball career game. Create a player, play 3-on-3 games with your team, train in drills, spend skill points and climb from Rookie to the max ranking, Legend. Then keep playing seasons and win championships. Progress is saved in the browser. |
| 🧇 Upside Down Merge | `games/upside-down-merge/` | A drop-and-merge puzzle with a Stranger Things character ladder (Will up to Eleven), drawn as original neon circles with emoji icons. Making Eleven shows a thank-you to Alessandro and Chiara. Best score is saved in the browser (localStorage key `upsideDownMergeBest`). |
| 🐍 Gobble King | `games/gobble-king/` | An arena snake game against computer snakes. Gobble food, trap snakes (a snake pops when its head hits another snake's body) and stay King (the biggest snake) as long as you can. Gobbling a snake gives a 20-second power-up: Turbo, Shield, Magnet or Double Food. Gobbling the King gives tokens (10/15/20 by difficulty, 1 for other snakes) to spend in the Skin Shop on 12 original skins. Easy, Normal and Hard. Best reign is saved in the browser (localStorage key `gobbleKing`). |
| 🥋 Karate Bot Clash | `games/karate-bot-clash/` | A 1-on-1 karate fighting game against 6 computer bots (Tin Trainee up to Grand Master Gear). Hits charge a special meter; winning a fight (best of 3 rounds) gives 1 Fight Token to spend on moves, specials, skills and skins. Beating a new bot unlocks the next one and a new belt color. Progress is saved in the browser (localStorage key `karateBotClash`). |
| ❌ Tic-Tac-Toe Party | `games/tic-tac-toe/` | Tic-tac-toe with neon X and O, 2 players on the same screen or vs the computer (Easy, Medium, or Hard, which never loses). Win line, confetti and sound effects. Scores, mode and level are saved in the browser (localStorage key `ticTacToeParty`). |
| ⚽ Goal Rush Soccer | `games/goal-rush/` | Arcade 4-a-side soccer with 6 original teams. Play the computer (Easy, Normal, Hard) or 2 players on one device. Pass, power shots, slide tackles, keepers, golden goal. Phone joystick + buttons or keyboard. Record vs the computer is saved in the browser (localStorage key `goalRushSoccer`). |
| 🎲 Monster Board | `games/monster-board/` | A survival game. Your family wins a one-of-a-kind board game and gets sucked inside. Race on the board in the story intro, then fight ghosts, zombies and 3 bosses (the Crocosquid, the Rhinorilla and Brewella the Bad Barista of the made-up Bean Scream Café) from 12 AM until dawn. Open weapon crates on the board for a bow, sword, throwing axe, spear or hammer, and level weapons up to Lv 5 with power gems, a second crate of the same weapon, or a weapon card. Pick an upgrade card each hour. Phone joystick or keyboard. Saves in localStorage key `monsterBoard`. |
| 🐍 Slither Storm | `games/slither-storm/` | An original snake battle royale. 25 snakes (you + 24 bots) jump from the Sky Balloon onto an island, open different chests (wicker baskets, silver chests, golden coil chests, snack crates and sky drops that float down later), grab spit-themed gear (Venom Spitter, Bubble Blaster, Stinger Sprayer, Long Fang, Egg Lobber) and stay inside the shrinking Hiss Storm. Last snake left is TOP SNAKE. Phone joystick with auto-aim, or keyboard and mouse. Stats saved in localStorage key `slitherStorm`. |
| 🎯 The Shot | `games/the-shot/` | A cartoon sniper rescue game. Look through a swaying scope, hold your breath to steady it, and BONK the masked Grabber Gang without hitting the hostages (hands up, tied with rope). 8 missions with walkers, window peekers, bad guys hiding behind hostages, bobbing boats, wind, a night-vision level and a 3-hit boss. Easy, Normal, Hard (x1, x2, x3 coins). Coins buy 6 snipers and 8 skins. Phone drag + buttons or mouse. Saves in localStorage key `theShot`. |
| 💦 Last Splash | `games/last-splash/` | A falling-floor party game. Stacked layers of cubes over a pool: a cube drops if you stand on it too long (it comes back 10 seconds later, until Crumble Time), so keep running and jumping. Fall through to the next layer, and the last player out of the water wins. Play vs 3, 5 or 7 bots (Easy, Normal, Hard), or 2 players on one keyboard with split screen. Crumble Time after 75 seconds. Phone joystick + JUMP. Saves in localStorage key `lastSplash`. |
| 🤼 Sumo Smarts | `games/sumo-smarts/` | A quiz sumo game. Each turn a math or trivia question pops up: a right answer pushes your opponent toward the edge of the ring (fast answers give a Lightning Push, 3 in a row a Super Shove), a wrong answer lets them push you. Push them out to win. 8 original wrestlers from Little Mochi to Grand Champ Kaboom, Mix/Math/Trivia/Logos & Famous and Easy/Normal/Hard. Stars and progress are saved in localStorage key `sumoSmarts`. |
| 🎮 Mini Mayhem | `games/mini-mayhem/` | A collection of 5 mini games. Forest Showdown (knock out every look-alike twin wearing your outfit with a sword, spear, bow or axe, find the very rare Diamond Sword, one life only), Tug of War (1 or 2 players), Snowball Showdown (reaction duel, 1 or 2 players), Hot Potato (with Alessandro, Chiara and Chris) and Sky Hop (cloud jumper). Winning gives coins to buy 12 animal skins in the Animal Shop. Saves in localStorage key `miniMayhem`. |
| 🛠️ Make Your Own Game Center | `games/game-center/` | A game maker. Type the game you want (for example "a ninja fighting zombies with a sword in a haunted castle") and it builds a personal game from 8 kinds (Runner, Jump Adventure, Blaster, Battle Arena, Catcher, Maze, Flyer, Racer) with your hero, bad guys, goodies, world, weapon, power-ups, difficulty and color. When the AI Game Maker is turned on (see below), kids can type anything and an AI writes a brand-new game for them; otherwise the instant template maker is used. Games are saved in localStorage key `funkidGameCenter`, and share links (`#g=...`) let friends play them. Test hooks on `window.GC`. |

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

## AI Game Maker (optional)

`api/make-game.js` is a Vercel serverless function that lets the Game Center build any game a kid types, using the Claude API.
It stays off (the Game Center uses its free instant maker) until an API key is added.

1. Create an API key at https://platform.claude.com and set a **monthly spend limit** there (this is the real cost guard).
2. In Vercel: Project → Settings → Environment Variables, add:
   - `ANTHROPIC_API_KEY` (required)
   - `GAME_MAKER_CODE` (optional) a family code kids must type before the AI maker works, so strangers can't spend your money
   - `GAME_MODEL` (optional, default `claude-opus-5-5`), `GAME_EFFORT` (optional `low`/`medium`/`high`, default `medium`), `HOURLY_LIMIT` (optional, default 6 games per visitor per hour)
3. Redeploy.

Kid safety: every idea is checked first (blocks unsafe topics, turns copyrighted characters into original ones), the game is written under strict kid-safe rules, then the finished game is checked again before it is shown. Games run in a sandboxed iframe with a Content-Security-Policy that blocks all network access.
AI games are saved on the device (up to 12) and can be changed with "Change it". They can't be shared by link yet.
