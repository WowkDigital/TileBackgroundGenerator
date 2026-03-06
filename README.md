# TileGen Pro - Seamless Background Generator

TileGen Pro is a high-performance, web-based utility designed to create seamless, 1:1 square tiling textures from a single transparent PNG or WebP image. Built with vanilla JavaScript and the HTML5 Canvas API, it allows designers and developers to generate complex background patterns for websites and games instantly.

**[Try TileGen Pro Online](https://wowkdigital.github.io/TileBackgroundGenerator/)**

## 🚀 Features

### 🎨 Tiling Patterns
* **Normal:** A standard centered tile.
* **Mirror 2x2:** Creates a kaleidoscope-like effect by mirroring the image across X and Y axes in a 2x2 grid.
* **Diagonal:** A specialized seamless pattern where parts of the graphic are placed in corners and the center to ensure perfectly continuous diagonal lines.
* **Chaos (Scatter):** Generates a randomized distribution of instances with automatic edge-wrapping to maintain seamlessness. Includes a "Randomize" seed trigger.
* **Custom 2x2 (Pro):** Provides granular control over each of the four quadrants, allowing independent rotation and flipping for unique geometric designs.

### 🛠 Tools & Customization
* **Global Transformations:** Control base rotation and scale across all patterns.
* **Live Tiled Preview:** The background of the workspace updates in real-time to show how the tile looks when repeated over a large area.
* **Grid Overlay:** Toggle a visual grid to inspect the seams and alignment of your tiles.
* **Transparency Support:** Full support for alpha channels in PNG/WebP files, with a classic checkerboard backdrop for visibility.
* **Export:** High-quality PNG export at 256px, 512px, or 1024px resolutions.

### 🛠 Technical Details
* **Logic:** Pure Vanilla JavaScript (No frameworks).
* **Rendering:** HTML5 Canvas API for real-time image manipulation.
* **Styling:** Tailwind CSS for a modern, responsive dark-themed UI.
* **Icons:** Lucide-React (via CDN).
* **Architecture:** Single-file architecture for portability and zero-config deployment.

## 📖 How to Use

1.  **Upload:** Drag and drop or click the upload area to select your base transparent graphic (PNG/WebP).
2.  **Configure:** Use the global sliders to set the initial scale and rotation.
3.  **Choose Pattern:** Select one of the five pattern types from the sidebar.
4.  **Refine:** If using Chaos or Custom 2x2, adjust the contextual settings that appear below the pattern selector.
5.  **Preview:** Check the main viewport to see the pattern tiled across the screen. Toggle the grid icon in the top-left to check for seams.
6.  **Download:** Click "Download .png" to save your tile.

## 💻 Local Development

Since this is a standalone HTML file, no installation is required.

1.  Clone the repository:
    `git clone https://github.com/your-username/tilegen-pro.git`
2.  Open `index.html` in any modern web browser.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
