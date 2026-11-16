# Lights Out Sleepover 🔦👹

A spooky browser game about a sleepover where the lights go out and the monsters come in.
Find your friends, escape the goo monsters, dive into the underworld to save Sam,
then battle the Devil King, the Devil Prince and the Candy Man.

Everything (graphics, music and sound) is drawn and synthesized in code, in one `index.html` file.
There is no build step and there are no dependencies.

## Play locally

Open `index.html` in any modern browser.

## Controls

| Mode | Move | Flash / Shoot |
|------|------|---------------|
| Solo | Arrows or WASD | Space |
| 2 players, same keyboard | P1: WASD / P2: Arrows | P1: Space / P2: Enter |
| Phone or tablet | Drag on screen | On-screen button |

Online invite-only rooms only work when the game is opened on claude.ai, because they use claude.ai's
room service. Solo and 2-player work everywhere, including on Vercel.

## Deploy to Vercel

1. Push this repository to GitHub.
2. In Vercel, choose **Add New → Project** and import the repository.
3. Leave **Framework Preset** as **Other**, with no build command and no output directory, then click **Deploy**.

Or from a terminal: `npx vercel --prod`.
