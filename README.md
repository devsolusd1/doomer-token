# $DOOMER - Official Website

The most melancholic token on Solana.

## Setup

### Images
Place the following images in the `img/` folder:

| File | Description |
|------|------------|
| `doomer-pfp.png` | Profile picture (the classic doomer face) |
| `doomer-banner.png` | Banner for hero background (smoking under stars) |
| `doomer-tinder.png` | Tinder scene |
| `doomer-gaming.png` | Gaming with panda scene |
| `doomer-smoking.png` | Smoking under the stars |
| `doomer-bed.png` | Lying in bed scene |
| `doomer-boombox.png` | Boombox outside window scene |
| `doomer-trading.png` | Looking at phone/trading scene |

### Music (Doomer FM)
Place your MP3 tracks in the `audio/` folder, named:
- `audio/track01.mp3`
- `audio/track02.mp3`
- `audio/track03.mp3`
- `audio/track04.mp3`
- `audio/track05.mp3`

To customize track names/artists, edit the `playlist` array in `index.html`:
```js
const playlist = [
    { title: "Song Name", artist: "Artist Name", src: "audio/track01.mp3" },
    // ...
];
```

## Deploy to GitHub Pages

```bash
git init
git add .
git commit -m "initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/doomer-token.git
git push -u origin main
```

Then enable GitHub Pages in repo Settings > Pages > Source: main branch.

## Links
- **Printr:** https://app.printr.money/token/9UuQsZ6TtETELDvpHSUZBdbVC4dVfUDwUnPP4cTjbrrr
- **Dexscreener:** https://dexscreener.com/solana/9UuQsZ6TtETELDvpHSUZBdbVC4dVfUDwUnPP4cTjbrrr
