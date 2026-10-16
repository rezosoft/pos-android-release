# RezoSoft POS — Android

Signed builds of the native RezoSoft POS app for Android (package `pos.rezosoft.ro`), for devices without Google Play (BlueCash, iMin). Each release carries `RezoSoft-POS-<version>.apk`, signed with the production certificate (SHA-256 `BA8F34C1…4A67`).

- **Pre-releases** are the canary ring: install them only on the canary devices.
- The **latest release** is the one for every sideload device.

Releases are published by `scripts/release.sh` and promoted by `scripts/promote.sh` in `rezosoft/pos-android` (`docs/runbooks/release.md`). The Windows (Electron) app and the older Capacitor builds are in `rezosoft/pos-release`.
