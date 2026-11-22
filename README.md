# Pranav's Voyage

The personal website of **Pranav Deora**: co-founder of Shazlo, Supply Chain Management student at Ahmedabad University, and Erasmus+ scholar.

You sail a ship across a 3D sea between six islands, and each island tells one part of the story:

| Island | What's there |
|---|---|
| Home Port | About me, education, honours & awards |
| Shazlo | My swipe-based fashion discovery startup |
| Voyage Log | Experience: Forbes Marshall, AAML capstone, Climate Fellows and more |
| Erasmus | My semester at the Universidad de Valladolid, Spain |
| Press & Media | Blog features, podcast, radio, my channels |
| Lighthouse | Contact |

It also has wave sound (made in code, no audio files), a ship's bell and a night-time foghorn, a day/night switch, a sailor who walks ashore at each island, and a plain **text version** for quick reading.

## How it's built

- One file: `index.html`. There is no build step.
- 3D: [three.js](https://threejs.org) r160, loaded from the jsDelivr CDN.
- Fonts: Fraunces, Instrument Sans and IBM Plex Mono from Google Fonts.

## Run it locally

Open `index.html` in Chrome, or serve the folder:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy for free

Live at **https://pranavdeora.github.io**, hosted free on GitHub Pages (Settings → Pages → Deploy from branch → `main` / root).
