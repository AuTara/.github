# Autara Chrome Extension – Privacy Policy

Effective date: 2025-01-01

## Overview
Autara is a wellness companion that provides breathing, eye breaks, walk prompts, a focus timer, and simple local insights. We designed Autara to work without sending personal data to our servers.

## Data we collect and where it’s stored
- Preferences and settings (e.g., theme, intervals, focus options) are stored locally using `chrome.storage.local`.
- Local insights (daily active minutes and per-domain minute totals by hostname only) are stored locally using `chrome.storage.local`.
- We do not collect or transmit page content, browsing history, or personal identifiers.
- No analytics, tracking pixels, or third‑party SDKs are used.

## What we share
- We do not sell, rent, or share user data.
- No data leaves the user’s device, except when a user voluntarily opens our Google Feedback Form to submit comments directly to us.

## Permissions we use and why
- `storage`: Save settings and local-only insights.
- `alarms`: Schedule break/eye reminders and a once-per-minute insights tick.
- `notifications`: Display reminder notifications.
- `idle`: Avoid counting inactive minutes and pause reminders when the user is away.
- `sidePanel`: Host the Autara side panel UI.
- `tabs`: Open/focus the panel or feedback form and target the active tab for overlay messages.
- `offscreen`: Play short audio cues for breathing guidance without a visible page.
- Host permissions (`<all_urls>`): Render optional overlays on pages. We do not collect or transmit page content.

## Remote code and network use
- No remote code is loaded. The extension ships fully packaged.
- Network access occurs only when the user opens our Google Feedback Form: https://forms.gle/YHyUweqVH7kq5Kks5

## Data retention and control
- All data is on-device. Users can remove it at any time by uninstalling the extension or clearing extension storage.
- We do not maintain server-side copies.

## Children’s privacy
Autara is not directed to children under 13.

## Changes
We may update this policy and will indicate the effective date above.

## Contact
Email: support@autara.app
