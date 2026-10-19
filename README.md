# Steam Showcase Toolkit

Create GIFs and images for Steam showcases. Trim videos, adjust the framing, preview loops, and export each file within your chosen size limit.

**[Download for Windows](https://github.com/WitchAtaraxia/Steam-Showcase-Toolkit/releases/latest)**

<img width="1070" height="1250" alt="image" src="https://github.com/user-attachments/assets/7c5e8be1-1187-4e22-95c7-d7b4e42f57cc" />

## Getting started

1. Install Python 3.10 or newer if you do not already have it.
2. Download and extract the Windows ZIP from [Releases](https://github.com/WitchAtaraxia/Steam-Showcase-Toolkit/releases/latest).
3. Run `SteamShowcaseToolkit.exe`. Keep the `runtime` folder beside it.

The launcher installs media dependencies on first use, which requires an internet connection. Media processing runs locally.

## Features

- Artwork Showcase: two synchronized GIF cuts.
- Workshop Showcase: five synchronized GIF cuts.
- Single GIF: 630px wide, with proportional or custom height.
- Guide exports, GIF optimization, and vertical collages.
- Trim, zoom, pan, fit, loop search, and optional smooth loop transitions.
- Adjustable size limit for each output GIF.
- Correct proportions for videos with non-square pixels.

GIF quality depends on the clip's dimensions, motion, duration, frame rate, and size limit. Shorter clips leave more room for color and detail.

## Saved projects

Collage projects are saved in `%LOCALAPPDATA%\SteamShowcaseToolkit\projects`, so they remain available across versions. The toolkit also copies projects from older local installations without overwriting different saves.

## More from Witch

- [Ataraxia Reviews](https://store.steampowered.com/curator/44868341-Ataraxia-Reviews/) — game reviews on Steam.
- [Witch Steam Enhancer](https://chromewebstore.google.com/detail/witch-steam-enhancer/lapofldlccnjjcddngfkaedinbhcmnag) — browser tools for Steam uploads, profiles, and showcases.

## Third-party components

The Windows download includes Gifsicle 1.95 with its GPL license and upstream source. The launcher installs Pillow and imageio-ffmpeg. These components retain their own licenses.

## License

The original application source is licensed under [GNU GPLv3](LICENSE). Logos and branding artwork are excluded. Third-party components keep their own licenses.

The legacy EXE launcher's source and licensing provenance are still being checked; it is outside this license grant. See [LICENSING.md](LICENSING.md) for the scope and component details.
