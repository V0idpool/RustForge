# RustForge
<img width="1536" height="1024" alt="rustforge" src="https://github.com/user-attachments/assets/fa5b40f0-7387-49a5-95a1-47e23ddbaaa1" />

RustForge takes any image, automatically converts it to the closest Rust color palette, and paints it directly onto a sign in-game. It’s perfect for adding custom, high-quality art to your base without spending hours on it.

### Support Development
☕ BuyMeACoffee: [https://buymeacoffee.com/rustforgedev](https://buymeacoffee.com/rustforgedev)

---

## Features

### Multiple Painting Methods
Choose from several methods to transfer your image to the canvas, each with a unique style:

* **VoidWeave Algorithm**: The default and most advanced method. It's designed for complex, detailed images and provides the most accurate color representation and highest quality final image.
* **Scanline**: A methodical, line-by-line painting method.
* **Crayon Eater**: A distinct painting style that adds character to your final image.

### Image Filters
Prepare your images with a variety of built-in filters to enhance them before painting.

* **None**: Applies no artistic filter, using the original image as a base.
* **Comic Filter**: A specialized filter for a cartoon-like appearance.
* **Oil Paint**: Applies a painterly effect, simulating an oil painting.
* **Pixel Art / Mosaic**: Converts your image into a simplified mosaic of larger, distinct pixels, giving it a pixelated look.
* **Charcoal Sketch**: Transforms the image into a black and white sketch, mimicking a charcoal drawing.
* **Dithering**: Reduces the number of colors in the image while creating the illusion of more colors by scattering pixels.
* **Sepia Tone**: Applies a reddish-brown tint to the image, giving it an antique, vintage look.
* **Emboss**: Adds a raised, three-dimensional effect to your image.

### Smoothing & Sharpening Filters
Fine-tune your image with smoothing filters to adjust its clarity and smoothness. Options include:

* **None**: Applies no smoothing or sharpening.
* **Gaussian**: Blurs the image to reduce noise and detail, creating a smooth, soft effect. Available sizes include: `3x3`, `5x5`, `7x7`.
* **Median**: A non-linear digital filter that is particularly effective at removing "salt and pepper" noise from images while preserving edges. Available sizes include: `3x3`, `5x5`, `7x7`, `9x9`.
* **Mean**: A simple averaging filter that smooths an image by replacing each pixel with the average value of its neighbors. Available sizes include: `3x3`, `5x5`.
* **LowPass**: A filter that smooths an image by reducing high-frequency details (like noise and sharp edges). Available sizes include: `3x3`, `5x5`.
* **Sharpen**: Enhances the edges of an image, making it appear sharper and more defined. The available size is: `3x3`.

### Configurable Hotkeys
Customize hotkeys for key actions directly from the user settings window, including starting, pausing, and stopping the painting process.

### Accurate Painting Time Estimation
A dedicated form that displays an accurate estimated painting time before it even begins.
---

## How to Use

1.  **Load an Image**: Use the main RustForge window to load the image you wish to paint by clicking "Load Image...".
2.  **Capture Your Regions**:
    * **Palette**: Use the hotkey for "Capture Palette" to draw a box around the in-game color palette. This allows the application to sample the available colors. (ONLY CAPTURE THE COLOR PALETTE AREA)
    * **Canvas**: Use the hotkey for "Capture Canvas" to draw a box around the in-game canvas. This defines the area where the painting will take place.
3.  **Configure Settings**: In the settings window, you can select your preferred paint method, apply various filters, and adjust the paint speed.
4.  **Start Painting**: Once the image is processed and regions are defined, press the "Start" hotkey to begin the painting process.
5.  **Pause and Stop**: Use the assigned hotkeys to pause or stop the painting process at any time.

---

## Hotkeys

| Action | Default Hotkey | Description |
| :--- | :--- | :--- |
| **CanvasOverlayToggle** | `F9` | Toggles the canvas selection overlay to define the painting area. |
| **PaletteOverlayToggle** | `F10` | Toggles the palette selection overlay to define the color palette area. |
| **Start/Pause** | `F11` | Starts or pauses the painting process. |
| **Stop** | `Escape` | Immediately stops the painting process. |

Hotkeys are configurable in the settings window.
