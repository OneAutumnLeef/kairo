# Kairo: every image has a job

**Live:** https://derajyojith.dev/kairo/

Kairo is an AI gallery that remembers *why* you saved a screenshot, helps you finish the job, and lets the image go only with proof the job is done. This is the interactive prototype for Wire Wars ’26 ("The Digital Gallery Graveyard").

## Open it like an app

- **Android (Chrome):** open the link, then tap **⋮ → Install app** (or **Add to Home screen**).
- **iPhone (Safari):** open the link, then tap **Share → Add to Home Screen**.

After the first visit it also works offline.

On a phone the app fills the screen. The strip on top runs the guided tour: **☰** lists the eight journeys, **ⓘ** shows the design notes for the current screen, and **Next** moves through the steps. On a laptop the journeys and notes sit on either side of the phone.

## What's inside

A single self-contained `index.html` (no build step, no tracking, no backend), a web app manifest, a service worker for offline use, and icons. Every image in the prototype is an illustrated stand-in, and the phone's date is fixed at Sun 15 Nov 2026, 4:10 PM.
