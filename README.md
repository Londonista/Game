# Pride, Prejudice & Pestilence 🖤🌹

*A moonlit courtship in five nights.* An atmospheric, cute-goth horror game
where Regency romance meets the Wolfman — with baby zambies. It's one single
web page — nothing to install — and it's made for playing on a phone.

> “It is a truth universally acknowledged, that a single gentleman in
> possession of a dreadful curse must be in want of a wife.”

You are **Miss Lizzy Nightshade**, gathering Mr Darcymoor's scattered love
letters from the gardens of Pemberley by lantern-light. Unfortunately the
parish's infants have risen *peckish* from their naps, your suitor has a
small lunar condition, and each night a new caller arrives — more dreadful
than the last.

## 🌕 How to play

- **Hold or tap** anywhere in the garden to guide Lizzy (arrow keys / WASD on
  a computer).
- 💌 **Gather every love letter** to survive the night. Five nights wins his
  heart.
- 🧟 **Baby zambies** waddle toward you — a nibble costs a heart. You have
  three hearts; lose them all and the night must be attempted again.
- 🌕 When the **moon blushes red** and Mr Darcymoor rears back with a howl —
  **run**. He forgets his manners for a few seconds, then apologises
  profusely.
- 🌳 **Hollow hedges are hiding places.** Slip into an archway and Lizzy dims
  her lantern: pursuers lose her scent and wander off. (Infants close enough
  to sniff her out are not fooled — no camping!)
- 🔔 Tap the bell to mute/unmute the music box and howls.

## 👥 The callers, night by night

Every villain who arrives **stays** for the later nights, so the garden grows
steadily more crowded:

1. **Night the First — the baby zambies** (and Mr Darcymoor's lunar episodes).
2. **Night the Second — Lady Catherine de Bat**, an uninvited patroness who
   circles above and dive-bombs. Watch for her shadow on the lawn.
3. **Night the Third — Miss Graves, the Late Governess**, a ghost who drifts
   toward you without pause or pity. She cannot fathom hiding in a hedge.
4. **Night the Fourth — Captain Wickhead**, a headless officer who charges
   clean across the garden along a flashing red line. Quit his lane.
5. **Night the Fifth — Nurse Rottingham**, a vast zombie nursemaid who
   produces fresh infants as she walks. Everyone attends this one.

Letters, infant numbers, and the wolf's temper all escalate night by night.

## 🎁 Trinkets (power-ups)

One appears in the garden every so often:

- 🌹 **Rose** — a brief *lace veil of protection* (invulnerable a few seconds).
- 🫖 **A cup of tea** — most fortifying: Lizzy walks much faster for a while.
- 🍪 **Biscuits** — every infant on the lawn settles down for a five-second nap.
- ⌚ **Pocket watch** — time, being polite, pauses: all villains freeze briefly.
- 💚 **Smelling salts** — restores one lost heart (only appears when hurt).

## 📱 Playing it on your phone

The game lives in **`index.html`**, so once **GitHub Pages** is switched on
(one-time setup), you get a link you can open in Safari or Chrome:

1. Go to this project on **GitHub.com** (on a computer is easiest).
2. Click the **Settings** tab → **Pages** (left menu).
3. Under **"Build and deployment" → Source**, choose **"Deploy from a branch"**.
4. For **Branch**, pick **`claude/horror-game-prototype-klbb40`** (or `main`
   once merged) and the folder **`/ (root)`**, then click **Save**.
5. Wait about a minute, then open the green link it shows you — something like
   `https://londonista.github.io/game/` — on your phone. 🎉
6. Optional: in Safari, tap **Share → "Add to Home Screen"** so it opens
   full-screen like a real app.

## 🫘 Flappy Beans

The previous game hasn't gone anywhere! It now lives at
**`flappy-beans.html`** — open `https://londonista.github.io/game/flappy-beans.html`
to play it. (Tap to flap; two fingers toggle the secret laser eyes.)

## 🛠️ For the curious

The whole game is one file of HTML, CSS, and JavaScript drawn on a `<canvas>` —
no frameworks, no build step. The music box, howls, and zombie coos are
synthesized live with the Web Audio API, so there are no sound files either.
