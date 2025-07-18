# Simple Depthy

This project contains a single-page web application for generating short parallax videos using an image and its depth map.

## Usage

1. Open `simple-depthy.html` in a modern web browser.
2. Upload a main image and a grayscale depth map.
3. Adjust the strength, speed and radius sliders to tune the 3D effect.

4. The page now relies on PixiJS with the `DepthPerspectiveFilter` from the
   original Depthy project. The filter deforms the image according to the depth
   map and inpaints gaps for smoother parallax.

5. Use the **Export Video** panel to record the animation.

Export relies on the `MediaRecorder` API, so recent versions of Chrome, Firefox or Edge are recommended.


PixiJS 1.5 is loaded from a CDN along with the Depthy filter script.

## License

This project is released under the MIT License. See [LICENSE](LICENSE) for details.
