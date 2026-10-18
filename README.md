# 🎨 PixelForge

**A lightweight pixel-art reference and color palette tool.**

PixelForge is a lightweight desktop application designed to help pixel artists reference images, sample colors, and organize color palettes in one convenient workspace.

Built with Python and PySide6, PixelForge focuses on a simple interface, responsive image navigation, and low memory usage.

> [!NOTE]
> PixelForge is currently distributed through platform-specific packages. Check the latest GitHub Release for available downloads and compatibility information.

## ✨ Features

- 🖼️ **Image Reference** — Open reference images directly from your computer.
- 🔍 **Zoom & Pan** — Zoom in for pixel-level inspection and move around the image.
- 🎨 **Color Picker** — Sample colors from reference images using the cursor.
- 📋 **Automatic HEX Copy** — Copy sampled color codes to the clipboard automatically.
- 🧪 **Color Studio** — View and work with color values in HEX and RGB formats.
- 🗂️ **Palette Management** — Save and organize colors for future projects.
- 📥 **Palette Import & Export** — Work with supported palette formats.
- 🕘 **Recent Images** — Quickly access recently opened references.
- 🪟 **Flexible Workspace** — Dock or float Color Studio to suit your workflow.
- ⚡ **Lightweight Design** — Designed to keep resource usage low during everyday use.

## 📥 Download & Installation

Download the version that matches your operating system from the **[GitHub Releases](../../releases/latest)** page.

### Windows

1. Open the latest release.
2. Download the Windows package (`.zip` or the installer, if provided).
3. Extract the ZIP file if necessary.
4. Open `PixelForge.exe` or the installer included in the release.
5. Follow any installation instructions shown.

If Windows displays a security warning, verify that the file came from the official PixelForge repository before proceeding.

### Linux

1. Open the latest release.
2. Download the Linux package.
3. Extract the archive if necessary.
4. Follow the instructions included in the package.
5. Launch PixelForge using the supplied launcher or executable.

**Important:** Windows and Linux builds are different. Download the package intended for your operating system. If a standalone build is not available, Python and PySide6 may be required.

## 🚀 How to Use

### 1. Open a reference image

Launch PixelForge and open an image from your computer. Use it as a visual reference while creating pixel art.

### 2. Navigate the image

Use the mouse wheel to zoom in or out. Drag with the supported mouse control to inspect different parts of the image.

### 3. Pick a color

Move the cursor over the reference image and select the desired pixel or color. PixelForge copies the sampled HEX value to your clipboard automatically.

### 4. Open Color Studio

Open Color Studio from the application menu to view color values, copy HEX codes, and manage saved colors.

### 5. Save your palette

Save colors you want to reuse. You can organize a collection for a character, environment, sprite, or another pixel-art project.

### 6. Export your palette

Use the available palette import/export tools to move supported palettes between projects and compatible applications.

## 🗃️ Project Structure

```text
PixelForge/
├── main.py
├── requirements.txt
├── README.md
├── LICENSE
├── CHANGELOG.md
├── data/
│   └── palettes/
└── docs/
    └── screenshots/
```

The exact contents may vary between the source repository and packaged releases.

## 💾 System Requirements

- **Operating systems:** Windows and Linux, depending on available releases.
- **Runtime:** Python and PySide6 for source-based installations.
- **Standalone builds:** Use the packaged executable when provided.
- **Memory:** Designed for low memory consumption; actual usage depends on the image size and current workload.

## 🛠️ Run from Source

If you want to run the source code instead of downloading a packaged application:

1. Install a compatible Python version.
2. Clone or download this repository.
3. Install the dependencies:

```bash
python -m pip install -r requirements.txt
```

4. Run PixelForge:

```bash
python main.py
```

On Linux, use `python3` if that is the command available on your system.

## 🗺️ Roadmap

Potential future improvements include:

- More palette formats and palette organization tools.
- Additional image-reference controls.
- Improved packaging and installation experience.
- Further performance and usability improvements.

Suggestions and bug reports are welcome through GitHub Issues.

## 🐛 Report a Bug

If you encounter a problem, open a [GitHub Issue](../../issues) and include:

- Your operating system.
- The PixelForge version.
- Steps to reproduce the problem.
- Any error message or screenshot that helps explain the issue.

Please do not include private files or sensitive information.

## 📜 License

PixelForge is intended to be released under the **MIT License**. See [`LICENSE`](LICENSE) for the complete license text.

Third-party libraries and assets remain subject to their respective licenses. Only use the MIT notice once the repository owner has confirmed that the project code can be distributed under those terms.

## ❤️ Credits

Created to make pixel-art reference and color selection more convenient.

Built with Python and PySide6.

If PixelForge helps your workflow, consider giving the repository a ⭐ on GitHub.
