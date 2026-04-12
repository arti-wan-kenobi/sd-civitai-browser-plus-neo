# sd-civitai-browser-plus-neo

> **Fork of [sd-civitai-browser-plus](https://github.com/BlafKing/sd-civitai-browser-plus) by BlafKing**, originally based on [SignalFlagZ's sd-webui-civbrowser](https://github.com/SignalFlagZ/sd-webui-civbrowser).  
> This fork adds support for **[sd-webui-forge-neo](https://github.com/Haoming02/sd-webui-forge-classic/tree/neo)** and is actively maintained.

---

### Extension for [sd-webui-forge-neo](https://github.com/Haoming02/sd-webui-forge-classic/tree/neo)

<h1>Features 🚀</h1>
<h3>Browse all models from CivitAI 🧩</h3>

* Explore a wide range of models at your fingertips.

<h3>Check for updates and installed models 🔄</h3>

* Easily spot new updates and identify already installed models while browsing.
* Ability to scan all installed models for available updates.

<h3>Download any Model, any version, and any file 📥</h3>

* Get the specific model version and file you need hassle-free.
* Download queue to avoid waiting for finished downloads.

<h3>Automatically assign tags to installed models 🏷️</h3>

* Assign tags by scanning all installed models for automatic use in image generation.

<h3>Quick Model Info Access 📊</h3>

* A button for each model card in txt2img and img2img to load it into the extension.
* A button under each image in model info to send its generation info to txt2img.

<h3>High-speed downloads with Aria2 🚄</h3>

* Maximize your bandwidth for lightning-fast downloads.

<h3>Sleek and Intuitive User Interface 🖌️</h3>

* Enjoy a clutter-free, user-friendly interface, designed to enhance your experience.

<summary><h1>Known Issues 🐛</h1></summary>

<h3>Unable to download / Frozen download:</h3>

**If you're experiencing issues with broken or frozen downloads, there are two possible solutions you can try:**

1. **Revert to the old download method**:
   Disable the "Download models using Aria2" feature to switch back to the old download method.

   ![Revert to old download method](https://github.com/BlafKing/sd-civitai-browser-plus/assets/9644716/982b0ebb-0cac-4053-8060-285533e0e176)

2. **Disable Async DNS for Aria2**:
   If you're using a DNS manager program like PortMaster, try turning on the "Disable Async DNS for Aria2" option.

   ![Disable Async DNS for Aria2](https://github.com/BlafKing/sd-civitai-browser-plus/assets/9644716/3cf7fab3-0df5-4995-9543-d9824b7931ff)

These settings can be found under the "Settings" tab in Web-UI and then under the "SD CivitAI Browser+ NEO" tile.

# How to install 📘

<h3>Automatic Installation:</h3>

1. Open your WebUI and go to the **Extensions** tab
2. Select **Install from URL**
3. Paste: `https://github.com/arti-wan-kenobi/sd-civitai-browser-plus-neo`
4. Click **Install**, then restart

<h3>Manual Installation:</h3>

1. Download the latest version from this repository and unpack the `.zip`
2. Navigate to your extensions folder (`<your SD folder>/webui/extensions`)
3. Place the unpacked folder inside the extensions folder
4. Restart SD-WebUI

# Changelog 📋

<h3>v1.0.0 — Initial fork release</h3>

* Forked from [BlafKing/sd-civitai-browser-plus](https://github.com/BlafKing/sd-civitai-browser-plus) (v3.6.0)
* Added compatibility with [sd-webui-forge-neo](https://github.com/Haoming02/sd-webui-forge-classic/tree/neo)