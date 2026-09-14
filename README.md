# Aryan & Shreya Accountability League

A polished, mobile-first accountability dashboard with:

- Daily missions for Aryan and Shreya
- Difficulty-based XP
- Coin rewards
- Custom rewards shop
- Daily reset behavior
- Offline-friendly PWA support

## Run it

Open `index.html` locally, or enable **GitHub Pages** for the repository.

## Add to an iPhone Home Screen

1. Open the deployed GitHub Pages URL in **Safari**.
2. Tap **Share**.
3. Tap **Add to Home Screen**.
4. Confirm the app name and tap **Add**.

This installs a Home Screen app shortcut/PWA. A true iOS widget in the widget panel requires a native SwiftUI/WidgetKit companion app.

## Shared progress note

The current version stores progress in the browser's local storage. That works on one device/browser. Live synchronization between two separate phones requires connecting the app to a shared backend such as Supabase or Firebase; the UI is intentionally kept dependency-free so that integration can be added cleanly later.
