# ReefShape Flatpak repository

Signed Flatpak repository for [ReefShape](https://www.tobiasfischer.info/reef-metrics/) on Linux, so
`flatpak update` brings new versions. The App workflow of
[reef-metrics](https://github.com/Tobias-Fischer/reef-metrics) adds each release; nothing here is edited by hand.

```bash
flatpak install --user https://www.tobiasfischer.info/reefshape-flatpak/reefshape-stable.flatpakref
# with an NVIDIA GPU instead: .../reefshape-cuda.flatpakref
flatpak update   # later: new ReefShape versions
```

Signing key: `reefshape-flatpak.asc` (fingerprint E701 48A7 233D EE5D ACD3  FB9A 3C92 F598 9242 5426).
