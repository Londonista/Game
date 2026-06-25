# Flappy Beans 🫘

A little Flappy Bird–style game, but you play as a bean! Tap the screen to make
the bean flap and fly through the gaps. It's one single web page — nothing to
install — and it works great in Safari on an iPhone.

## ▶️ How to play

- **Tap the screen** (or press the **Space bar** on a computer) to flap.
- Fly through the gaps between the green stalks.
- Each gap you pass = **+1 point**. Don't hit the stalks or the ground!
- Your **best score is saved** on your phone automatically.

### 🔴 Laser Eyes (secret power!)

- **Touch the screen with two fingers** to switch the bean's laser eyes on or off.
  (One finger still flaps as normal.) A little "LASER ON" badge shows at the top
  when they're active, and the setting is remembered next time.
- When the lasers are on, beams shoot from the bean's eye in the direction it's
  looking. **Hold the beam steady on a green stalk for about 2 seconds** and it
  heats up and **vaporizes** — clearing a path to fly through!
- It takes focus: aim through the gap and nothing happens, so the lasers don't
  make the game too easy.
- On a computer, press the **L** key to toggle the lasers.

## 📱 How to put it on your iPhone (one-time setup)

The game lives in this GitHub project. To get a link you can open on your
phone, you turn on a free feature called **GitHub Pages**. You only do this
once:

1. Go to this project on **GitHub.com** (on a computer is easiest).
2. Click the **Settings** tab (top right of the project).
3. In the left menu, click **Pages**.
4. Under **"Build and deployment" → Source**, choose **"Deploy from a branch"**.
5. For **Branch**, pick **`claude/flappy-beans-game-52erwe`** and the folder
   **`/ (root)`**, then click **Save**.
6. Wait about a minute. GitHub will show a green link near the top of that page,
   something like:

   ```
   https://londonista.github.io/game/
   ```

7. **Open that link on your iPhone** in Safari. 🎉

### 💡 Add it to your home screen (so it feels like a real app)

1. Open the link in **Safari** on your iPhone.
2. Tap the **Share** button (the square with an arrow at the bottom).
3. Tap **"Add to Home Screen"**.
4. Now there's a Flappy Beans icon you can tap any time — it opens full-screen
   with no browser bars.

## 🛠️ For the curious

The whole game is in **`index.html`** — just HTML, CSS, and JavaScript drawn on
a `<canvas>`. No frameworks, no build step, no internet needed once it's loaded.

> Tip: Later, if these changes get merged into the project's `main` branch, you
> can switch GitHub Pages (step 5 above) to use `main` instead for a tidier setup.
