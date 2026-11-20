# E-Farmer visual guides

Offline packs of images and short silent clips for the E-Farmer apps (one pack per livestock production or crop, e.g. broilers, tomato).

This repository only holds the published files. Each pack version is a GitHub release (tag `<pack>-<version>`, e.g. `tomato-1.0.0`) with:

- `manifest.json`: the pack manifest (format and checks in `@frank14b/farm-science`, `src/media`);
- the images (`.webp`) and clips (`.mp4`) it lists, each checked by the app with its SHA-256 after download.

The apps download the packs a farm needs; nothing here is code.

## Credits and licences

Drawings of practices are AI illustrations made for E-Farmer. Disease photos come from open-licence sources; each asset's author, licence and source link are in its pack manifest (`source`), and photos under CC BY-SA stay under CC BY-SA.
