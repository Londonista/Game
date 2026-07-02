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

## 🛠️ For the curious

Each game is a single self-contained HTML file drawn on a `<canvas>` (the
parlour menu is plain HTML/CSS). No frameworks, no build step, no assets.
