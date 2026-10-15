# Voxel Atlas — four little worlds

Four handcrafted procedural voxel scenes in a single offline HTML file.

**[Explore the worlds](https://luckye1120.github.io/hanami-voxel-garden/)**

| Scene | Details | Direct link |
| --- | --- | --- |
| Hanami · 樱花庭园 | Pagoda, cherry blossoms, koi pond, bamboo and stone lanterns | [Visit](https://luckye1120.github.io/hanami-voxel-garden/#hanami) |
| Alpine · 雪山木屋 | Snow peaks, wooden chalets, frozen lake, snowman and falling snow | [Visit](https://luckye1120.github.io/hanami-voxel-garden/#alpine) |
| Riviera · 灯塔港湾 | Striped lighthouse, pastel village, sailboats, palms and beach umbrellas | [Visit](https://luckye1120.github.io/hanami-voxel-garden/#riviera) |
| Neon · 霓虹都市 | Neon towers, skybridge, rooftop landing pad, taxis and rain | [Visit](https://luckye1120.github.io/hanami-voxel-garden/#neon) |

![Voxel Atlas](preview.png)

## Run

Open `index.html` directly in a modern browser. All geometry, styling, JavaScript and Three.js are embedded. No installation, build step or network connection is required. Browser WebGL support is required.

## Controls

- Click the scene selector, or press **1–4**, to switch worlds.
- Drag to orbit; scroll or pinch to zoom. Arrow keys rotate; `+` / `-` zoom.
- **O** toggles automatic orbit; **P** toggles scene animation.
- **L** cycles daylight, golden hour and moonlight.
- **R** resets the camera; **H** hides the interface.
- The camera button saves the current scene as a PNG.

Worlds are generated on first use and cached. Only the selected world is rendered. Animation preferences persist across scene switches, and reduced-motion preferences are respected. Each world starts with its curated lighting; Neon opens in moonlight. Scene URLs preserve the selected world on reload.

## Deploy

GitHub Pages serves the repository root on `main`. Push an updated `index.html` to publish a new version.

## Credits

The embedded Three.js r160 library is MIT-licensed; its license notice is included in `index.html`.
