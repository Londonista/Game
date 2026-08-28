# Nine Blooms 🌸

A quiet game set in the nine circles of hell. There is nobody down there — no
demons, no lost souls, nothing to fight. Just nine hostile places: ash, storm,
mire, crushing weights, boiling water, fire, thorns, tar, and ice.

You are a small mote of light. As you drift through each circle and **tap the
dead things you find**, they bloom — and as more of them bloom, hell turns into
heaven around you. The sky lifts, the ground goes green, the hazards wither into
flowers, and the way down opens.

It's one single web page — nothing to install — and it works great in Safari on
an iPhone.

## ▶️ How to play

- **Drag your finger** to steer the light. It follows you, and glides on when
  you let go.
- **Tap** to send out a ring of light. Anything dead inside the ring blooms.
- Dark, twisted things with a faint glow are what you're looking for. When one
  is close enough to tap, a little circle appears around it.
- Blooming gives you back some light, and **each bloom becomes a safe spot** —
  falling cinders go out near it, tar pools shrink, thorns turn into roses.
- Bloom **three quarters of a circle** and the arch at the far end opens. Bloom
  *all* of it and the circle is wholly redeemed.
- The little arrow at the edge of the screen points to whatever is nearest:
  the next dark thing, or the way down once it's open.

Your **light meter** is at the top. Hell drains it slowly, hazards drain it
fast, and standing in the glow of something you bloomed fills it back up. If it
runs out, your light gutters and reforms at the start of the circle — **but
everything you bloomed stays bloomed.** You can't really lose, only take longer.

Your progress is saved on your phone, so you can put it down and come back.

On a computer: **Space** does the same as a tap, and **M** mutes the sound.

## 🔥 The nine circles

| | | what's trying to put your light out |
|---|---|---|
| I | Limbo | falling ash, slow wind |
| II | Lust | whirling gusts that shove you around |
| III | Gluttony | endless acid rain, sludge pools |
| IV | Greed | swinging and rolling weights |
| V | Wrath | geysers of boiling water |
| VI | Heresy | flame jets from the tombs |
| VII | Violence | thorn vines that lash at you, rain of fire |
| VIII | Fraud | pitch pools, tar geysers |
| IX | Treachery | ice shards, and a cold that drains you unless you stay near a bloom |

## 📱 How to put it on your iPhone (one-time setup)

The game lives in this GitHub project. To get a link you can open on your
phone, you turn on a free feature called **GitHub Pages**. You only do this
once:

1. Go to this project on **GitHub.com** (on a computer is easiest).
2. Click the **Settings** tab (top right of the project).
3. In the left menu, click **Pages**.
4. Under **"Build and deployment" → Source**, choose **"Deploy from a branch"**.
5. For **Branch**, pick **`claude/hell-circles-heaven-blooms-1b04gm`** and the
   folder **`/ (root)`**, then click **Save**.
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
4. Now there's a Nine Blooms icon you can tap any time — it opens full-screen
   with no browser bars.

## 🫘 Flappy Beans is still here

The older game moved over to **`flappy.html`**, so it's one step away:

```
https://londonista.github.io/game/flappy.html
```

## 🛠️ For the curious

The whole game is in **`index.html`** — just HTML, CSS, and JavaScript drawn on
a `<canvas>`. No frameworks, no build step, no internet needed once it's loaded.
Every flower, rock, geyser and sunrise is drawn with code rather than pictures,
and the nine circles are generated from a fixed seed, so a circle looks the same
each time you visit it. The sound is generated too: a low drone that opens up
into chimes as the world blooms.

> Tip: Later, if these changes get merged into the project's `main` branch, you
> can switch GitHub Pages (step 5 above) to use `main` instead for a tidier setup.
