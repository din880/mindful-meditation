# Mindful — iPhone 11 meditation app

## Files
- `index.html`: app interface and features
- `manifest.webmanifest`: installable web-app metadata
- `sw.js`: offline cache
- `icons/`: iPhone/Home Screen icons

## Install on iPhone 11
This is an installable web app (PWA), not a signed native iOS `.ipa`.
1. Upload the contents of this folder to an HTTPS web host (for example, your own website or a static hosting service).
2. On your iPhone 11, open the hosted URL in **Safari**.
3. Tap **Share** → **Add to Home Screen** → **Add**.
4. Open Mindful from the Home Screen. Visit once while online so the offline cache can be installed.

## Notes
- Male voice uses iOS/browser speech synthesis and selects a male-sounding English voice if one is available. iOS may not expose voice gender consistently; you can manage downloaded voices in iPhone Settings → Accessibility → Spoken Content → Voices.
- Nature soundscapes are synthesized locally with Web Audio; they are not recordings.
- No account, analytics, or external audio service is included.
