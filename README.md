# LOA-Patch-A

Release data for the Legends of Azeroth launcher.

- `manifest.json` lists every client patch file with its size and SHA-256, the download pack that holds it, and the
  byte patch the launcher applies to a player's own clean `Wow.exe`. The launcher reads it from the `main` branch:
  `https://raw.githubusercontent.com/hughinell/LOA-Patch-A/main/manifest.json`
- The download packs (`full-<version>.zip`, `update-<version>.zip`) are attached to the GitHub releases of this repository
  (tag `v<version>`), because they are larger than git allows in a normal push.

No game client is stored here, only the custom patch files and a byte delta for the exe.
