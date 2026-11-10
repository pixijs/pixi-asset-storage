# pixi-asset-storage

Models, textures, audio and video that PixiJS projects load at runtime, kept here so they stay out of the code
repositories. pixi-3d lists each file's raw URL in its asset mirror (`examples/assets/manifest.ts`), which downloads
it once and serves it locally to its examples, tests and playground.

## Contents

### `kenney/starter-kit-racing/`

The track pieces, decorations, trucks, sounds and smoke sprite from Kenney's
[Starter Kit Racing](https://github.com/KenneyNL/Starter-Kit-Racing), used by pixi-3d's racing demo. The `.glb`
files read their texture from `Textures/colormap.png` beside them, so keep the folder's layout.

- Made by [Kenney](https://kenney.nl). The skid sound is by [Landeplage](https://github.com/Landeplage).
- License: [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/), as the kit states. Credit isn't required;
  this note gives it anyway. Kenney's other free assets are at [kenney.nl/assets](https://kenney.nl/assets).

### `pixijs/`

Files made for PixiJS's own examples:

- `pixijs-logo.glb`: the PixiJS logo as a 3D model.
- `shared_video_motion.mp4`: a short silent clip that pixi-3d's video texture example plays.
- `diorama.gltf`: a stand of three toys with two scenes, three cameras and punctual lights, for pixi-3d's glTF
  scenes example.

The PixiJS name and logo belong to PixiJS.

## Adding a file

Put it in a folder named after where it comes from, and add a line here with its source and license. A file from
another author needs a license that allows redistribution.
