# Stylish V1 — Test Prototype

Stylish V1 is a mobile-first, installable web app (PWA) implementing the locked V1 product direction:

- Digital wardrobe / closet
- Manual clothing attributes
- Manual outfit builder
- Rule-based outfit matching (no AI)
- Saved looks
- 7-day outfit planner
- Profile/preferences
- Optional clothing photos
- Local device persistence with localStorage
- Installable from Android Chrome as a standalone app

## Run on a computer

Use any local server from this folder. With Node.js:

```bash
npx serve .
```

Open the local URL shown by the command.

## Test on Android

1. Put this folder on a public URL, or run a LAN server on the same Wi-Fi network.
2. Open the URL in Chrome on Android.
3. Use Chrome's menu and choose **Add to Home screen** / **Install app**.
4. Launch Stylish from the new home-screen icon.

## Prototype storage

Data is stored locally in the browser on the test device. It is intentionally a prototype, not a production cloud account system yet.

## V1 boundaries

This prototype does **not** include ChatGPT, AI styling, AI image generation, AI clothing recognition, or LLM recommendations. Matching is deterministic and based on user-selected category, color, style, occasion and weather attributes.
