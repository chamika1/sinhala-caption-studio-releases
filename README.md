# Sinhala Caption Studio — Windows releases

This **public repository contains only Windows installer releases and the update manifest**. The application source code is private.

- Download installers from [Releases](https://github.com/chamika1/sinhala-caption-studio-releases/releases).
- `latest.json` is used by installed Windows apps to announce newer releases. The app downloads an installer only after user confirmation, verifies its size and SHA-256 against this manifest, and requires another confirmation before opening it.
- The manifest and installer are hosted by the same GitHub repository. SHA-256 checks consistency; it is **not** an independent publisher signature. Installers are currently not code-signed, so Windows may show an unknown-publisher warning.
- An existing v1.0.0 installation does **not** have the in-app updater: install v1.0.1 manually once; subsequent releases can appear inside the app.

Report issues privately to AutoCaptionsLK. Do not upload license keys or customer media to this repository.
