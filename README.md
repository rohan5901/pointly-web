# pointly.in

The website for Pointly, the iPhone app that tells you which of your credit cards to use before you pay.

Plain HTML and CSS, no build step. GitHub Pages publishes the `main` branch as it is, at [pointly.in](https://pointly.in).

- `index.html`: the home page
- `privacy/`, `support/`: the pages App Store Connect links to
- `style.css`: shared styles, the app's own theme (light and dark follow the device)
- `assets/`: app icons, Apple's App Store badge, and Inter subset to woff2 (SIL Open Font License)

Preview locally with `python3 -m http.server --bind 127.0.0.1 8766` in this folder, then open http://127.0.0.1:8766.
The App Store link is a placeholder until the app is live: search `TODO` in `index.html`.
