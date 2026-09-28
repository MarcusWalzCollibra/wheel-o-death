# 💀 Wheel of Death

**World 8-4: The On-Call Castle.** A spooky, Super Mario–style castle-and-battleship level that decides **who is on call for the sprint**.

The Koopa King's battleship has docked at your production castle. Enter the names of the heroes, spin the helm, and accept your fate. No warp pipes. No continues.

## Features

- 🎬 Intro: a "WORLD 8-4" title card, the battleship sailing in over the castle, a typewriter letter from the Koopa King, and an iris wipe into the level (skippable with **Skip** or `Esc`)
- 🎡 The wheel is a battleship helm, with a Boo watching the top, weighted easing and a nice slow-down
- 🗿 Cruel twist: half the time a Thwomp slams down and knocks the wheel one more name along
- 🏰 Castle brick walls, flickering torches, rising lava, Podoboos jumping out of it, shy Boos that hide their faces when your cursor gets close, and Bullet Bills fired across the screen (toggleable)
- 🪙 A coin shower and a HUD (heroes, coins, world, time) in the classic style
- 🎵 Original synthesized chiptune (castle music, jump, coin, fanfare and Thwomp thud) via WebAudio. Nothing is sampled, and sound effects and music have separate toggles
- 🔥 Toss the chosen hero into the lava to take them off the list
- ⚰️ Shuffle the order before the ritual
- 💾 Remembers your list of names between visits (localStorage)
- 📱 Responsive, respects `prefers-reduced-motion`, no build step and no dependencies: it's a single `index.html`

## Run locally

Just open `index.html` in a browser, or serve it:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy to GitHub Pages

1. Create a repo and push this folder.
2. In the repo: **Settings → Pages → Build and deployment**.
3. Set **Source** to *Deploy from a branch*, branch `main`, folder `/ (root)`.
4. Save. Your wheel will be live at `https://<user>.github.io/<repo>/` in a minute or two.

(Since the site is a single static `index.html`, no build is required.)
