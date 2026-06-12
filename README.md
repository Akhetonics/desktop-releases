# desktop-releases

Public release manifest for [**Akhetonics Desktop**](https://github.com/Akhetonics/akhetonics-desktop) — **no source code, no binaries.**

This repo holds a single file, [`latest.json`](latest.json), describing the latest published
desktop version:

```json
{
  "version": "0.7.0",
  "releaseUrl": "https://github.com/Akhetonics/akhetonics-desktop/releases",
  "publishedAt": "2026-06-12T00:00:00Z"
}
```

The desktop app fetches this manifest at startup and shows an in-app update banner when a
newer version is available. The installer itself stays on the private app repo's GitHub
Releases — only the version number is public here.

`latest.json` is updated automatically by the app repo's release CI; it is not meant to be
edited by hand.
