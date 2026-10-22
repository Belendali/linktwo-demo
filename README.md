# LinkTwo — clickable prototype

LinkTwo is a tiny app for two people — your partner or your best friend. Snap a photo and it lands on their home-screen widget, answer one question a day together, and see each other's status and distance at a glance.

**Live demo:** https://belendali.github.io/linktwo-demo/

Everything inside the phone is tappable:

- **Onboarding** — welcome → account → name → photo → birthday → partner / best friend → invite → permissions → widget → Couple Plan
- **Home** — anniversary counter, Daily Quiz (shuffle, answer with a photo, reveal, past questions), map, status with backgrounds, Evan's status, special days, add-widget guide
- **Camera → Log** — take a photo, add a caption, send; snap back within 10 minutes for a *same moment*; react with the emoji "pump" animation; calendar and past days
- **Me** — partner settings, unlink → invite → enter code → connected, Couple Plan paywall (one person buys, both get Pro), widgets

The left panel has jump links and "Pretend Evan…" buttons that simulate the other person (snap, answer, pause location, anniversary).

Built from the "setlog version" section of the LIVE STATUS Figma file. `app.html` is the source fragment; run `./build.sh` to regenerate `index.html`.
