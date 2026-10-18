# 🤽 Ngen H2O

A cartoon water polo game for the web. Play as **Ngen Aquatics** against the computer, run a whole season, or go head-to-head with a real player online.

**Play it:** [ngen-waterpolo-server.onrender.com](https://ngen-waterpolo-server.onrender.com) (also on itch.io)

> The free server naps when nobody is playing. If it says "waking up the server", give it about a minute.

---

## What's in the game

- **5 vs 5 water polo** with real rules: shot clock, exclusions, the 2 m and 5 m lines, and penalty shootouts for ties
- **Season mode:** play 8 rival teams, with standings, stats and league leaders
- **Online 1v1:** press **ONLINE 1v1** and you're matched with the next person in the waiting room
- **Super Shot**, **power-ups** (turbo, mega ball, freeze, rubber duck, octopus) and **Mega Goalie** after a goal against
- **Goal celebrations** for every player, an announcer who calls names, and the team cheer at the end: *"Ngen on me, Ngen on three… one, two, three, NGEN!"*
- **Star challenges** that unlock new pools, balls and caps
- **Learn mode** with quick tips about the rules
- Three levels: **Rookie** (the default), **Club** and **Olympic**

## How to play

| | Keyboard | Phone |
|---|---|---|
| Swim | WASD / arrow keys | Joystick (bottom left) |
| Pass / switch swimmer | J or Space | PASS button |
| Shoot / tackle | K or Enter (hold for power) | SHOOT / TACKLE button |
| Sprint | Shift or L | SPRINT button |
| Pause | Esc or P | ⏸ at the top |

Sprinting uses energy. A tired swimmer slows down, and a tired shooter misses more.

## Online play, kid-safe

- Players get random fun names like *Cosmic Marlin*. There's no typing names and no chat.
- The server runs the match, so both players always see the same game.
- Nothing is saved on the server. Your records stay in your own browser.

---

## Files

| File | What it does |
|---|---|
| `index.html` | The whole game (graphics, sound, AI, everything) in one file |
| `server.js` | The online waiting room and match runner |
| `names.js` | The list of fun random names |
| `package.json` | Tells Render how to start the server |

## Run it on your computer

You need [Node.js](https://nodejs.org) 18 or newer.

```bash
npm install
npm start
```

Then open http://localhost:8787. To test online play, open it in two browser windows and press **ONLINE 1v1** in both.

## Update the live game

1. Replace `index.html` (or any file) here on GitHub.
2. Render sees the change and redeploys by itself in about a minute.
3. For itch.io, upload the new game zip on the project's edit page.

## Hosting

Hosted on [Render](https://render.com) on the free plan:
- Build command: `npm install`
- Start command: `node server.js`
- No environment variables needed

---

Made for Ngen Aquatics. 💙
