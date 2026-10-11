# Spatial Notes updates

Downloadable app update artifacts only. Application source and build jobs are maintained separately in a private repository. GitHub download access does not grant access to application source.

**99.0.3 is an isolated updater QA prerelease, not a customer release.** It uses a separate application identity and QA signing key. Analytics and connected services are disabled. It is not notarized or approved for general installation.

New customer build configuration uses the stable feed at https://github.com/ethaenall/spatial-notes-updates/releases/latest/download/latest.json. This URL has no customer feed until the first accepted stable release is published. QA prereleases are excluded from it. Existing Spatial Notes 0.1.0 installations require a manual first update to an updater-enabled customer release.

Published archives and installers remain immutable. Each update is verified against the application's signing public key before installation. GitHub credentials and private signing keys are never shipped in the app.
