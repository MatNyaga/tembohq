# tembohq.com

The public website for Tembo, the Android money app by Terra Softworks Limited. Plain HTML + CSS,
no build step, no trackers, no cookies. Hosted on GitHub Pages with the custom domain `tembohq.com`.

Source of the words and claims: `marketing/00-positioning.md` §5a in the (private) app repo.
Colours, fonts and Tembo come from the app (`marketing/brand/`).

## Preview

    python3 -m http.server 8765    # then open http://localhost:8765/

## On launch day

Replace each of the three `<span class="play soon">…</span>` (marked `LAUNCH:` in `index.html`) with:

    <a class="play" href="https://play.google.com/store/apps/details?id=dev.pesa.mymoney&referrer=utm_source%3Dwebsite%26utm_medium%3Dbutton%26utm_campaign%3Dlaunch">Get it on Google Play</a>

(or Google's official "Get it on Google Play" badge image, following Google's badge guidelines).

## Files

- `index.html`, `assets/style.css` — the page
- `assets/fonts/` — Figtree, Geist Mono (OFL, licences inside)
- `assets/img/` — Tembo art, app screens (made-up data), `og.png` (link preview, source `og.html`)
- `assets/video/` — the "Where did it go?" film (muted on the page)
- `CNAME` — the custom domain

The privacy policy still lives at `https://matnyaga.github.io/tembo-app/privacy.html` (Google Play
points there; don't move it during Google's review).
