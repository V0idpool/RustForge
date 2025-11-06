# RustForge
![RustForge](https://img.shields.io/badge/version-1.9-red)
![Release](https://img.shields.io/badge/Release-10%2F22%2F2025-orange)
<img width="1536" height="1024" alt="RFBanner" src="https://github.com/user-attachments/assets/bbef19a5-3ef2-45f5-bd04-0616c7e4e6d5" />

RustForge takes any image, automatically converts it to the closest Rust color palette, and paints it directly onto a sign in-game. It’s perfect for adding custom, high-quality art to your base without spending hours on it.

### Support Development

☕ BuyMeACoffee: [https://buymeacoffee.com/rustforgedev](https://buymeacoffee.com/rustforgedev)

⭐ Patreon (All Projects & Early Access): [https://www.patreon.com/cw/voidpool](https://www.patreon.com/cw/voidpool)

## Premium Access & Early Builds

Premium unlocks advanced features and helps fund ongoing development. Access is granted through either a BuyMeACoffee donation or by joining a specific Patreon tier (Patreon tiers offer Early Access builds and more).

**💎 How to get Premium**:

1.  **Donate ANY amount** via [Buy Me a Coffee](https://buymeacoffee.com/rustforgedev).
2.  **Subscribe** to the **🛠️ Early Access** tier or higher on Patreon.


### **Join the RustForge Discord for Support:**
https://discord.gg/R4bR9JwAfv

---

### Premium Features

* **VoidWeave Algorithm** – The most advanced painting method for stunning, detailed, high-fidelity images. Scans the image, and blends pixels as it paints.

* **Resume Painting on Click**: Press the Resume On Click Hotkey: **F5** and click a point on the canvas with your image loaded, and the paint session will resume from that row with the correct palette color. No more redoing entire paintings if you die, disconnect, or crash mid-paint.

* **Session Save** – Save your painting progress and resume later without restarting. This is useful if you need to reboot, or something happens where you need to close the game or step away for extended periods.

* **Session Load** – Quickly load a saved session and continue painting exactly where you left off.

* **Integrated Image Editor** – No more needing external tools! You can now access an image editor directly within RustForge, featuring cropping and text overlay functionality to perfectly prepare your artwork before painting.

* **Timelapse GIF Creator** – When enabled, this exciting premium feature automatically takes a series of timelapse screenshots during the painting process and compiles them into a timelapse GIF of your finished artwork. Also use the powerful editor to fine-tune your timelapse GIF before saving. You can now adjust the playback speed, skip frames, manually remove specific frames, and even customize the painting stats text that appears on the GIF.

## Features

* **Load Recent Files**: Don't waste time searching for images! A new menu item now saves the last 10 used images, allowing you to quickly load them without having to re-select from your computer or enter a URL.

* **Real-time Notifications**: Stay informed about your painting status with new toast notifications that appear in the top-right corner of the screen. You will now be notified when a paint session starts, pauses, or stops.

* **Background Color Ignore**: You can now select a specific color to be **skipped entirely** during the painting process (e.g., white borders or solid backgrounds). This saves a significant amount of painting time by skipping unnecessary paint clicks. The time estimation feature reflects these savings!
  * Customizable Color Tolerance: Set a custom value to fine-tune how strictly RustForge ignores background-like colors when Background Color Ignore is active.
  * Color Space Selection (RGB or CIEDE2000): Choose between Euclidean RGB for standard color matching, or CIEDE2000 for the most perceptually accurate color matching to the Rust palette.

* **Transparency Threshold Setting**: Define a custom threshold for alpha transparency. Pixels that are more transparent than this value will be skipped entirely during the painting process.

* **Discord Rich Presence**: Your painting status (Paused, Painting, Completed) and current job information will now be displayed in your Discord profile.

* **Screenshot on Finish Toggle**: Automatically capture a screenshot of your finished painting once the session is complete.

* **Dedicated Splash Screen:** A new splash form now elegantly handles the loading process for all necessary libraries and settings, providing a smoother startup experience.

* **Advanced Error Logging & Support Integration:** Enhanced, advanced error logging is now enabled, writing all errors to RF_Logs.txt. Also gives the option to instantly open the Discord support channel, making it easy to drag-and-drop your log file directly into your support post for developer troubleshooting.

* **Mouse Click Delay Setting:** Users can now precisely control the delay for automated mouse movements (e.g., brush selection) to ensure reliability on various systems and server conditions.


### Multiple Painting Methods
Choose from several methods to transfer your image to the canvas, each with a unique style:

* **VoidWeave Algorithm(Premium)**: The default and most advanced method. It's designed for complex, detailed images and provides the most accurate color representation and highest quality final image.
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
* **Watercolor**: Smooth, painterly effect with soft edges, simulating watercolor painting.
* **Line Art**: Converts the image to a high-contrast black/white sketch, preserving original dark lines and generating new lines based on contours. (Perfect to color in images yourself!)
* **Grayscale**: Removes all color, converting the image to black, white, and shades of gray.

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
    (Press **Enter** after setting your Canvas area, and Palette area to save)
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
| **Resume On Click** | `F5` | Click a point on the canvas with your image loaded, and the paint session will resume from that row with the correct palette color. |

Hotkeys are configurable in the settings window.

