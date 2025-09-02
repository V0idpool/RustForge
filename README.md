# RustForge: Advanced Paint-by-Number Automation

RustForge is an application designed to automate the process of painting digital images onto a canvas, specifically for use in games like Rust. It provides advanced features for image processing, filtering, and multiple painting algorithms to give you full control over the final result.

---

## Features

### Multiple Painting Algorithms
Choose from several methods to transfer your image to the canvas, each with a unique style:

* **Scanline**: A methodical, line-by-line painting method.
* **Crayon Eater**: A distinct painting style that adds character to your final image.
* **VoidWeave Algorithm**: A pixel-by-pixel painting method for precise results.

### Image Filters
Prepare your images with a variety of built-in filters to enhance them before painting:

* **Emboss**: Adds a raised, three-dimensional effect to your image.
* **Oil Paint**: Applies a painterly effect, simulating an oil painting.
* **Pixelate**: Converts your image into a mosaic of larger, distinct pixels.
* **Comic Filter**: A specialized filter for a cartoon-like appearance.

### Smoothing & Sharpening Filters
Fine-tune your image with a second pass of filters to adjust its clarity and smoothness. Options include:

* **Blur**: Smooths detail for a soft effect.
* **Median**: Removes noise while preserving sharp edges.
* **Mean & LowPass**: Simple averaging filters that smooth the image by reducing noise and high-frequency details.
* **Sharpen**: Enhances the edges of your image, making it appear more defined.

### Configurable Hotkeys
Customize hotkeys for key actions directly from the user settings file, including starting, pausing, and stopping the painting process.

### Progress Tracking
A dedicated form displays real-time progress during image processing and painting, including an estimated time to completion.

---

## How to Use

1.  **Load an Image**: Use the main application window to load the image you wish to paint.
2.  **Capture Your Regions**:
    * **Palette**: Use the hotkey for "Capture Palette" to draw a box around the in-game color palette. This allows the application to sample the available colors.
    * **Canvas**: Use the hotkey for "Capture Canvas" to draw a box around the in-game canvas. This defines the area where the painting will take place.
3.  **Configure Settings**: In the settings menu, you can select your preferred paint method, apply various filters, and adjust the paint speed.
4.  **Start Painting**: Once the image is processed and regions are defined, press the "Start" hotkey to begin the automated painting process.
5.  **Pause and Stop**: Use the assigned hotkeys to pause or stop the painting process at any time.

---

## Hotkeys

| Action | Default Hotkey | Description |
| :--- | :--- | :--- |
| **CanvasOverlayToggle** | `F8` | Toggles the canvas selection overlay to define the painting area. |
| **PaletteOverlayToggle** | `F9` | Toggles the palette selection overlay to define the color palette area. |
| **Start/Pause** | `F10` | Starts or pauses the painting process. |
| **Stop** | `Escape` | Immediately stops the painting process. |

Hotkeys are configurable by editing the `UserCFG.ini` file located in the application's `User` directory.
