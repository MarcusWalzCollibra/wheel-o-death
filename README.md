# 💀 Wheel of Death

A doom-laden, Black Sabbath–styled spinning wheel that decides **who is on call for the sprint**.

Enter the names of the damned, spin the wheel, and accept your fate. A bell tolls when the wheel chooses.

## Features

- 🎡 Canvas spinning wheel with weighted easing and a satisfying slow-down
- 🩸 Black Sabbath aesthetic — blood red, ash black, gothic type, flickering glow and drifting fog
- 🔔 WebAudio tolling bell (a nod to the opening of *Black Sabbath*) — toggleable
- ⚰️ Shuffle the order before the ritual
- 💾 Remembers your list of names between visits (localStorage)
- 📱 Responsive, no build step, no dependencies — a single `index.html`

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
