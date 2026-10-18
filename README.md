# Steam Showcase Toolkit

Make GIFs and images for Steam showcases. Frame and trim videos, preview loops, and optimize exports to a per-file byte limit.

**[Download the latest Windows release](https://github.com/WitchAtaraxia/Steam-Showcase-Toolkit/releases/latest)**

## Run

Extract the ZIP and double-click `SteamShowcaseToolkit.exe`. Keep the `runtime` folder beside it. Requires Windows and Python 3.10 or newer; the launcher installs the media dependencies when needed. An internet connection is required for that first dependency setup. Media processing runs locally.

## Features

- Artwork: two synchronized GIF cuts.
- Workshop: five synchronized GIF cuts.
- Single GIF: 630px wide, with proportional or custom height.
- Guide exports, GIF optimization, and vertical collages.
- Trim, zoom, pan, fit, loop search, and optional smooth loop transitions.
- Configurable byte limit, including 5,000,000 bytes per GIF.
- Correct display proportions for videos with non-square pixels.

GIF quality depends on dimensions, motion, duration, frame rate, and the byte limit. Shorter clips leave more room for color and detail.

## Saved projects

Collage projects are stored in `%LOCALAPPDATA%\SteamShowcaseToolkit\projects`, shared across versions. Existing project files in older local installations are copied without overwriting different saves.

## Bundled components

The Windows ZIP includes Gifsicle 1.95, its license, and upstream source. Pillow and imageio-ffmpeg are installed by the launcher. Do not remove the runtime files.
