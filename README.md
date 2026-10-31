# tembohq.com

The public website for Tembo, the Android money app by Terra Softworks Limited. Plain HTML + CSS,
no build step, no trackers, no cookies. Hosted on GitHub Pages with the custom domain `tembohq.com`.

Source of the words and claims: `marketing/00-positioning.md` §5a in the (private) app repo.
Colours, fonts and Tembo come from the app (`marketing/brand/`).

## Preview

    python3 -m http.server 8765    # then open http://localhost:8765/

## Launch

Done 31 Oct 2026: the three Play buttons in `index.html` link to the live listing, tagged
`utm_source=website&utm_medium=button&utm_campaign=launch`.

## Files

- `index.html`, `assets/style.css` — the page
- `assets/fonts/` — Figtree, Geist Mono (OFL, licences inside)
- `assets/img/` — Tembo art, app screens (made-up data), `og.png` (link preview, source `og.html`)
- `assets/video/` — the "Where did it go?" film (muted on the page)
- `CNAME` — the custom domain

The privacy policy still lives at `https://matnyaga.github.io/tembo-app/privacy.html` (Google Play
points there; don't move it during Google's review).
