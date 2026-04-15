# Privacy Policy

**Stackflow**
Last Updated: April 2026

## Overview

Stackflow is a poker night toolkit developed by Ben Callahan. Your privacy is important to us. This policy explains what information is processed and how.

## Information We Collect

Stackflow does not collect, store, or transmit personal information about you. Specifically:

- No account or login required
- No personal data collected
- No usage analytics or tracking
- No third-party advertising
- No data shared with third parties for marketing

## Local Data Storage

All app data is stored locally on your device, including:
- Tournament presets you create
- Player roster, buy-ins, rebuys, and eliminations
- App settings and preferences
- Timer state

This data never leaves your device and is not accessible to us.

## AI Assistant

When using the AI assistant, your typed or spoken message is sent to our server proxy (hosted on Cloudflare) and forwarded to Anthropic's Claude API to generate a response. To make this work:

- The message text you send to the AI is transmitted to the AI provider
- Game state relevant to your question (current blind level, stack sizes, player count) is included so the assistant can give grounded answers
- An anonymous device identifier is used solely for rate limiting
- Messages are not stored server-side beyond what's needed to return a response
- No personal identifying information is attached to these requests

Speech recognition for voice input runs **on-device** (no audio leaves your phone). Only the resulting text is sent to the AI when you submit it.

If you don't use the AI assistant, no data is transmitted by the app.

## Live Activity

The Lock Screen Timer feature uses Apple's Live Activity framework to display timer information on your Lock Screen. This feature operates entirely on your device and does not transmit any data.

## Firebase

The app includes Firebase for optional multiplayer timer synchronization across iPhone, iPad, Apple TV, and Apple Watch. When using room-based sync:
- Only timer state data is transmitted (blind levels, time remaining)
- No personal information is collected or stored
- Room data is temporary and automatically deleted

If you do not use multiplayer sync, no data is transmitted through Firebase.

## Children's Privacy

Stackflow does not collect personal information from anyone, including children under 13.

## Changes to This Policy

This Privacy Policy may be updated from time to time. Any changes will be reflected in the "Last Updated" date above.

## Contact

If you have questions about this Privacy Policy, contact:
callahanapps@gmail.com

Ben Callahan
USA
