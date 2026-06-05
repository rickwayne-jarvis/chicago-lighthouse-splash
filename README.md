# The Chicago Lighthouse — Splash

Single-page splash. Entry point into chicagolighthouse.org via three doorways: Care, Donor, Enterprise.

Hand-written HTML + CSS, no framework. Plays three Vimeo films (hero 1198599538, donor 1198599536, enterprise 1198599537). Native accessibility toolbar (text size, high contrast, motion). WCAG 2.2 AA target, AAA where possible.

## Local

```sh
cd $(pwd)
python3 -m http.server 7641
# open http://127.0.0.1:7641
```

## Deploy

GitHub Pages from `main` / `/`. Every push to main publishes.

## Brand source

Creative-review deck, May 2026. Voice rules:
- Care: "We Light Up Human Potential."
- Donor: "You Can Light Up Human Potential."
- Enterprise: "Lighting Up Your Contact Center Experience."
- Tagline: "Make an Impact Today."

## Open items

- Transcripts for the three films are placeholder text. Replace once finalized.
- Drive-folder assets (logo / photos) were not accessible to the agent at build time. Photos in `/assets` were pulled from `chicagolighthouse.org` as stand-ins; replace with the new brand library when available.
- The donate buttons currently link to the existing `chicagolighthouse.org/donate/` flow. Swap to Donorbox / Stripe / Classy when a processor is wired.
