# The Games Parlour 🕯️

One little website, all the games. Open the link on your phone and a menu
appears — pick a game and play. Everything is plain HTML/CSS/JavaScript,
one file per game, nothing to install.

| Game | File | In one line |
|---|---|---|
| 🖤 **Pride, Prejudice & Pestilence** | `pestilence.html` | A cute-goth horror courtship in five nights — gather love letters, dodge baby zambies, a wolfish suitor, a vampire patroness, a ghost governess, a headless captain, and a monstrous nursemaid. Hide in hedges; trust in tea. |
| 🌙 **Monday Night Simulator** | `monday-night-simulator.html` | A cozy hangout for three — Jas · Aqsa · Adam — with rooms to potter about in and mini-games (Star Catcher, Aqsa's Laundromat). |
| 🫘 **Flappy Beans** | `flappy-beans.html` | Tap to flap through the stalks. Two fingers toggle the secret laser eyes. |

The menu lives in **`index.html`**, so the main link always opens the parlour.

## 📱 Getting the link (GitHub Pages, one-time setup)

1. On **GitHub.com**, open this project → **Settings** → **Pages**.
2. Under **"Build and deployment" → Source**, choose **"Deploy from a branch"**.
3. Pick the branch — **`main`** is the tidy choice — folder **/ (root)**, and **Save**.
4. After a minute, open the green link it shows (something like
   `https://londonista.github.io/Game/`) on your phone. 🎉
5. In Safari: **Share → "Add to Home Screen"** to make it feel like a real app.

If you ever update the games and the phone still shows an old version, pull
down to refresh or open the link once in a private tab.

---

## 🖤 Pride, Prejudice & Pestilence — how to play

- **Hold or tap** the garden to guide Miss Lizzy Nightshade (WASD/arrows on a
  computer). Gather every **love letter** 💌; five nights wins Mr Darcymoor's
  heart. Three hearts per night.
- When the **moon blushes red**, he howls and forgets his manners — *run*.
- **Hollow hedges are hiding places** 🌳: slip into an archway and pursuers
  lose your scent (infants right beside you are not fooled).
- A new caller arrives each night and stays: **Lady Catherine de Bat** 🦇
  (dodge her shadow), **the Late Governess** 👻 (she never stops; hedges
  baffle her), **Captain Wickhead** ⚔️ (quit his red charging lane), and
  **Nurse Rottingham** 🍼 (slow, vast, endlessly producing infants).
- Trinkets help: 🌹 lace-veil shield · 🫖 fortifying speed · 🍪 infant
  naptime · ⌚ time politely pauses · 💚 restores a heart.
- 🔔 mutes the music box, howls, and coos (all synthesized live — no sound
  files anywhere).

---

## 🌙 Monday Night Simulator — the full guide

A cozy little hangout for three friends — **Jas, Aqsa, and Adam** — to tend
together every Monday night over a video call. One person screen-shares; the
call is the social layer, the game is the shared focus you all react to and
decide on together.

There are **no scores to lose and no way to fail**. The only goal is keeping
the cozy going, week after week — and because the game remembers everything,
months in it becomes a little **scrapbook of your Mondays**.

### How a Monday night works

1. **Open `monday-night-simulator.html`** (tap it in the parlour menu, or open
   the file in any browser). One host opens it and shares their screen on the
   call. No install, no accounts, no internet needed.
2. Tap **🌙 Start Monday Night** to begin a night. You'll get a warm welcome,
   a callback to last week, and a few coins just for showing up.
3. Play a **🎲 mini-game** or two together to earn **cosiness coins 🪙**.
4. Spend coins in the **🛍️ Shop** on décor, then **drag items** anywhere in the
   room to make it yours. The room fills up and cosies over the weeks.
5. **🌱 Tend** your plant so it grows over the months.
6. **📖 Add a memory** — one real moment from the call becomes a postcard on
   the wall.
7. Tap **✨ Sign off** for an end-of-night card. Everything **auto-saves**.

### 🎲 Mini-games (co-op, low-stress, 2–5 min)

- **🔍 Spot the Cozy Object** — twinkling things are hidden around the room;
  everyone calls out where they are.
- **🃏 Memory Match** — flip-card pairs of your stuff.
- **🧹 Tidy the Room** — a light timed clean-up (unlocks on week 6).

More unlock as your Monday count climbs.

### 🌱 Growth & unlocks

New item sets, mini-games, and room areas unlock as you play more Mondays
(weeks 3, 6, 10, 15…). There's always a reason to come back next week.

### 💾 The save system (the heart of it)

Continuity is the whole point, so the save is solid:

- **Auto-saves** to your browser after everything you do.
- **💾 Save → Export** downloads your whole game as a JSON file — back it up so
  you never lose months of Mondays, move it to a new machine, or hand hosting
  to someone else.
- **💾 Save → Import** loads a save file back in.

What's saved: room layout & owned items, cosiness coins, total Mondays played,
unlocks reached, plant growth, and your memory wall.

### 💛 Make it yours

The code is seeded with the three of you and has clearly-marked
`TODO(personalise)` comments so it's easy to fill in later:

- Avatar names, colours and faces (top of the `<script>`).
- In-joke shop items (the **In-Jokes** set in the catalogue) — swap the
  placeholders for your real references, favourite snacks, that one poster.
- Warm, personal opening callbacks and end-of-night copy.

> Handy while tinkering: the browser console exposes `MNS.state` (the live
> save), `MNS.save()`, and `MNS.reset()` (wipes the save and reloads).

---

## 🛠️ For the curious

Each game is a single self-contained HTML file (the horror game and Flappy
Beans draw on a `<canvas>`; Monday Night Simulator uses DOM elements; the
parlour menu is plain HTML/CSS). No frameworks, no build step, no assets.
