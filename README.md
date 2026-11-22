# Birthday story

An Arabic birthday website in progress.

## Current opening

- A custom Three.js cake model with frosting, decorations and numeral 2 and 3 candles.
- Twelve floating 3D balloons that pop on touch. Popped objects are removed from rendering and hit-testing.
- Confetti and a clickable lamp that changes the scene from day to night.
- White stars entering from all four screen edges and gathering into the approved upright portrait.
- Balloon-pop, lamp-click and star-shimmer sounds, started by a user gesture, with a mute control.
- Star replay and reduced-motion support.

Serve this directory as a static website. Runtime dependencies and portrait star data are bundled locally. There are no external library, image, audio or font requests. A recent browser with WebGL2 is required for the 3D scene. The model is stylized, not a photograph. Performance still needs checking on the intended phones.

## Still to build

The cartoon character and board interaction, crochet message, yarn transition and memories gallery are not included yet.

## Portrait and privacy

The bundle contains coordinates and brightness values derived from the approved upright portrait, not its source image file. These data can reconstruct the person's likeness, so they should still be treated as a portrait. The original photos and edited portrait PNGs are not included.

## Third-party software

Three.js is used under its MIT license. See `THIRD_PARTY_NOTICES.txt` and the bundled license notice.
