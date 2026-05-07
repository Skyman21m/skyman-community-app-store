# Skyman Umbrel Community App Store

Community app store with custom Umbrel apps.

## Install

Add this repository via the Umbrel UI: **App Store → Community App Stores →
Add Community App Store**, then paste:

```
https://github.com/Skyman21m/skyman-community-app-store
```

## Apps

- **skyman-alby-hub-relay-select** — Fork of [getAlby/hub](https://github.com/getAlby/hub)
  with a "Nostr Relay" section added to Settings. Dropdown of main public relays
  + a Custom wss:// option. Restart required after change.

- **ronin-ronindojo** — [RoninDojo](https://ronindojo.io) Samourai Dojo backend
  for your Umbrel node. Connects to your existing Bitcoin node. Includes Electrum
  server, block explorer, Mempool Space, and Tor support.

- **skyman-mempool-alert** — Sends a Nostr DM (NIP-17) the moment a Bitcoin
  block is mined by a pool you watch (Public Pool, Solo CK, Braiins Solo,
  SoloPool.com, unknown solo miners, or any pool slug from mempool.space).
  Auto-discovers recipient inbox relays (kind 10050), supports NIP-42 auth.
  Web UI for managing recipients, watched pools, and bot profile.
