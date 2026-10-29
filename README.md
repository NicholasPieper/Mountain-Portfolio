# Nick — Mountain & Expedition Portfolio

Bare-bones portfolio page for the Higher Earth Ecuador expedition photographer/videographer role (Cotopaxi & Cayambe, 12–25 Nov 2026; applications close 5 Nov 2026).

Plain static HTML: no build step, no dependencies. Videos are embedded from YouTube and listed in the `VIDEOS` array at the bottom of `index.html`, so adding, removing or reordering a video is a one-line edit.

## Publish on GitHub Pages

```bash
cd ecuador-expedition-portfolio
git init && git add . && git commit -m "Ecuador expedition portfolio"
git branch -M main
git remote add origin https://github.com/<your-account>/<repo-name>.git
git push -u origin main
```

Then in the repo: **Settings → Pages → Source: Deploy from a branch → main / (root)**. The site will be at `https://<your-account>.github.io/<repo-name>/`.

## Notes

- All embeds are YouTube (long-form and Shorts). YouTube's player doesn't display view, like or follower counts; TikTok and Instagram embeds do, so those platforms are linked rather than embedded.
- The Mt. Whitney Instagram reel is linked under the Whitney long-form video.
- Stills (`assets/stills/`) were converted from the original CR2/HEIC files to JPG, max 2400 px on the long edge.

## Before sending

- The application email also needs one line on climbing/altitude experience and your camera kit; the kit list on the page is copied from the Natural Selection Tour portfolio, so confirm it's current.
