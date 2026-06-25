# Monday Night Simulator 🌙

A cozy little hangout for three friends — **Jas, Aqsa, and Adam** — to tend
together every Monday night over a video call. One person screen-shares; the
call is the social layer, the game is the shared focus you all react to and
decide on together.

There are **no scores to lose and no way to fail**. The only goal is keeping
the cozy going, week after week — and because the game remembers everything,
months in it becomes a little **scrapbook of your Mondays**.

## ▶️ How to play

1. **Open `index.html`** in any browser (or run `npx serve` in this folder).
   One host opens it and shares their screen on the call. No install, no
   accounts, no internet needed.
2. Tap **🌙 Start Monday Night** to begin a night. You'll get a warm welcome,
   a callback to last week, and a few coins just for showing up.
3. Play a **🎲 mini-game** or two together to earn **cosiness coins 🪙**.
4. Spend coins in the **🛍️ Shop** on décor, then **drag items** anywhere in the
   room to make it yours. The room fills up and cosies over the weeks.
5. **🌱 Tend** your plant so it grows over the months.
6. **📖 Add a memory** — one real moment from the call becomes a postcard on
   the wall.
7. Tap **✨ Sign off** for an end-of-night card. Everything **auto-saves**.

## 🎲 Mini-games (co-op, low-stress, 2–5 min)

- **🔍 Spot the Cozy Object** — twinkling things are hidden around the room;
  everyone calls out where they are.
- **🃏 Memory Match** — flip-card pairs of your stuff.
- **🧹 Tidy the Room** — a light timed clean-up (unlocks on week 6).

More unlock as your Monday count climbs.

## 🌱 Growth & unlocks

New item sets, mini-games, and room areas unlock as you play more Mondays
(weeks 3, 6, 10, 15…). There's always a reason to come back next week.

## 💾 The save system (the heart of it)

Continuity is the whole point, so the save is solid:

- **Auto-saves** to your browser after everything you do.
- **💾 Save → Export** downloads your whole game as a JSON file — back it up so
  you never lose months of Mondays, move it to a new machine, or hand hosting
  to someone else.
- **💾 Save → Import** loads a save file back in.

What's saved: room layout & owned items, cosiness coins, total Mondays played,
unlocks reached, plant growth, and your memory wall.

## 💛 Make it yours

The code is seeded with the three of you and has clearly-marked
`TODO(personalise)` comments so it's easy to fill in later:

- Avatar names, colours and faces (top of the `<script>`).
- In-joke shop items (the **In-Jokes** set in the catalogue) — swap the
  placeholders for your real references, favourite snacks, that one poster.
- Warm, personal opening callbacks and end-of-night copy.

## 🛠️ For the curious

The whole game is in **`index.html`** — just HTML, CSS, and JavaScript using
DOM elements for the room. No frameworks, no build step. Open it and go.

> Handy while tinkering: the browser console exposes `MNS.state` (the live
> save), `MNS.save()`, and `MNS.reset()` (wipes the save and reloads).
