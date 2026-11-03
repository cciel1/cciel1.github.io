# RAMIBLE Studio

Static, bilingual studio and game information website. Studio information and support website, prepared for publication on GitHub Pages.

- Korean: `index.html`
- English: `en.html`
- Website privacy: `privacy.html` and `privacy-en.html`
- Account deletion: `delete-account.html` and `delete-account-en.html`
- AdMob authorized sellers: `/app-ads.txt`

Plain HTML/CSS, native accessible disclosures, no JavaScript or build step. No third-party widgets, game runtime, account system, analytics or embedded payment processing. Images and fonts are hosted locally.

## Local preview

```sh
python3 -m http.server 8891 --bind 127.0.0.1
```

## Assets

`assets/rivet-rumble.png` is the existing RAMIBLE Studio game icon.

The battle and assembly PNGs are complete, unedited development captures from the owner's `Rivet_Rumble_GooglePlay_6screens_20261016.zip`. They were captured on October 16, 2026 in the real Android app, source `a057540015b62f2a65ebcd3ce35656947a19616b`, local capture version `0.2.2-capture-ui1-debug`. They illustrate the game; they are not evidence of the current release UI. The website identifies them as October 2026 development images. No fabricated gameplay or third-party stock imagery is used.

The locally hosted Archivo and IBM Plex Sans KR fonts were copied from the game's existing licensed font bundle. Their SIL Open Font License notices are in `assets/fonts/OFL-Archivo.txt` and `assets/fonts/OFL-Plex.txt`. Upstream notices: [Archivo](https://github.com/google/fonts/blob/main/ofl/archivo/OFL.txt), [IBM Plex Sans KR](https://github.com/google/fonts/blob/main/ofl/ibmplexsanskr/OFL.txt).

## Publication

Public website: https://cciel1.github.io/ . Publication authorized by the owner on November 3, 2026. There is no approved game-download link yet. Keep `app-ads.txt` at the website domain root. The website privacy notice covers this information website; it is separate from the game's own data and consent policy. The deletion resource documents the existing server behavior; it does not authorize deleting any account or claim commercial compliance approval.
