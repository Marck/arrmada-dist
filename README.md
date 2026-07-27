# Arrmada — release channel

Public download channel for **Arrmada**, a native SwiftUI remote for the
self-hosted *arr media stack (Sonarr · Radarr · Lidarr · Bazarr), installed via
**SideStore / AltStore**.

This repo holds **only the built app** — unsigned `.ipa` files published under
[Releases](../../releases) plus the app `icon.png`. The source code lives in a
separate private repository; SideStore re-signs the IPA on-device with your own
Apple ID.

Releases here are produced automatically by the source repo's CI on each version
tag. A self-hosted SideStore source lists Arrmada and tracks the newest release,
so there's nothing to download by hand — add the source in SideStore and install.

MIT-licensed binary. Not affiliated with the Sonarr/Radarr/Lidarr/Bazarr projects.
