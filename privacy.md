# Privacy Policy

**Stackflow**
Last Updated: May 2026

## Overview

Stackflow is an AI-powered poker night assistant developed by Ben Callahan. The AI runs entirely on your device using Apple Intelligence — your conversations, prompts, and game state stay private. This policy explains the data the app stores, the limited cases where data is transmitted, and what we never collect.

## What We Don't Collect

- No account or login required
- No personal information collected
- No usage analytics or behavioral tracking
- No third-party advertising
- No data sold or shared with marketers

## On-Device AI (Apple Intelligence)

Stackflow's AI features — tournament generation, voice control, poker math, hand evaluation, payout splits — run entirely on your device using Apple's Foundation Models framework, the same AI that powers Apple Intelligence. **No prompt, voice transcription, response, or game state ever leaves your device for AI processing.**

- No network requests are made for AI features
- No third-party AI provider is involved
- No chat content, prompts, or responses are transmitted to any server
- No usage tracking or rate limiting (none is needed; there's no remote cost)

Speech recognition for voice input also runs on-device. No audio leaves your phone.

Apple Intelligence requires a compatible device (iPhone 15 Pro and later, iPad with M1 or newer, Mac with M1 or newer) running iOS 26 or later. On devices without Apple Intelligence, the app falls back to a basic on-device command parser for timer control.

## Local Data Storage

All app data is stored locally on your device, including:

- Tournament presets and structures you create
- Player roster, buy-ins, rebuys, and eliminations
- App settings and preferences
- Timer state and history

This data is not transmitted to us or to any third party.

## Live Activity

The Lock Screen Timer feature uses Apple's Live Activity framework to display timer information on your Lock Screen. This feature operates entirely on your device and does not transmit any data.

## Cross-Device Sync (Optional)

Stackflow includes an optional Share & Join feature that lets you sync the timer across your own Apple devices (iPhone, iPad, Apple TV, Apple Watch) during a tournament. This feature is opt-in: it activates only when you explicitly create or join a room.

When using cross-device sync, the following non-personal data is transmitted to Firebase Realtime Database, scoped to a user-generated room code:

- An anonymous device identifier (a locally generated UUID, not tied to your Apple ID, email, name, or any user-supplied identifier)
- Timer state (current blind level, time remaining, paused/running, break state)
- The room code itself (which you generate and share)

This data is used solely to keep the participating devices in sync for one tournament session. It is not used for analytics, advertising, profiling, or any other purpose. Room data is temporary and is automatically cleaned up.

If you do not use the Share & Join feature, no data is transmitted to Firebase or anywhere else.

## In-App Purchases

Stackflow includes optional Tip the Dealer purchases (small, medium, and large) for users who want to support development. Apple processes these transactions; no purchase data is shared with us beyond Apple's standard receipt validation. Tipping is entirely optional and unlocks no app functionality.

## Children's Privacy

Stackflow does not collect any personal information from anyone, including children under 13.

## Changes to This Policy

We may update this Privacy Policy from time to time. Any changes will be reflected in the "Last Updated" date above.

## Contact

If you have questions about this Privacy Policy, contact:
callahanapps@gmail.com

Ben Callahan
USA
