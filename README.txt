BADR LIFT V5 — ANIMATED EXERCISE EDITION

Files: index.html, manifest.webmanifest, sw.js, app icons.

Features:
- Original offline animated schematic movement guides with pause/replay and speed control
- Technique tips and primary muscle labels; representative patterns flagged as such
- Full V4 personalized four-day program plus optional cardio/mobility
- Workout logging, rest timers, progress, routine editing, PR history, measurements
- Recovery dashboard compatible with an optional native iPhone HealthKit bridge

HOSTING
Upload all files to one HTTPS site (GitHub Pages, Netlify, etc). Then open in Safari → Share → Add to Home Screen. The PWA caches these files for offline use after installation.

UPGRADING
Export your JSON backup first. Hosting V5 on the same site/origin preserves localStorage key badr_lift_v1. Opening a different domain or native iOS WKWebView requires importing the backup. No cloud sync is provided.

APPLE HEALTH
The web/PWA version cannot access HealthKit directly. Use the separately provided native iPhone wrapper source (requires Xcode on a Mac).

DISCLAIMER
Animated illustrations are original schematic motion guides, not professional biomechanical or 3D motion-capture instruction. Seek coaching for unfamiliar lifts.
