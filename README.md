# Birthday story

An Arabic birthday website in progress. This first version includes:

- A birthday cake with animated candle flames.
- Floating balloons that pop when tapped or activated with the keyboard.
- Falling confetti and a confetti burst when a balloon pops.
- A lamp icon that switches the room between light and dark.
- White stars that enter from outside the scene and gather to form the portrait.
- Replay and reduced-motion support.

Open `index.html` in a browser. The page is self-contained and has no external library or image requests.

## Still to build

The cartoon character and board scene, yarn transition and memories gallery are not included in this version. They will be added after the remaining references, photos, text and scene details are ready.

## Portrait and privacy

The portrait is made from star coordinates derived from a supplied photograph. No original JPEG is included. These coordinates can reconstruct the portrait, so they should still be treated as an image of the person. The portrait uses a small rigid rotation and proportional scaling, without generating a new face, changing the smile or inventing unseen anatomy.

This version uses 2D illustration and Canvas particles. It is not a finished 3D experience. Phone performance still needs to be checked on the intended devices.
