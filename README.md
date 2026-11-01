# Vermont 🖤🤍

A clean, modern, monochrome theme designed for Discord mobile client loaders (such as Vendetta, Replugged, or Aliucord). Built with high contrast, sharp white text, and pure dark slate tones.

<p align="center">
  <img src="preview.png" width="600" alt="Vermont Monochrome Theme Preview">
</p>

## 🎨 Features

* **Monochrome Palette:** Pure black (`#000000`), slate gray, and bright white without distracting saturated colors.
* **High Contrast Readability:** Crisp white text paired with deep black backgrounds for optimal legibility day or night.
* **OLED Dark Mode:** Optimized deep dark tones to save screen battery and reduce eye strain.
* **Custom Background Support:** Subtle background overlay integration that stays clean and readable.

## 🚀 Installation Guide

### Option 1: Direct Fetch Link (Recommended)

1. Open your modified Discord app on your device.
2. Go to **User Settings** $\rightarrow$ **Themes**.
3. Tap **Install Theme** or **Fetch Theme**.
4. Paste the raw URL below:

```text
https://raw.githubusercontent.com/yymeowsy-bit/VexTheme/main/Vermont.json
```

5. Tap **Install** and select **Apply Theme**.

### Option 2: GitHub Pages Link

If your client loader supports GitHub Pages links, you can paste:

```text
https://yymeowsy-bit.github.io/VexTheme/Vermont.json
```

## 🛠️ Customizing Background Visibility

To adjust how visible the background image is, open `Vermont.json` in your repository and change the `"alpha"` parameter under the `"background"` section:

```json
"background": {
  "url": "YOUR_IMAGE_URL",
  "alpha": 0.25,
  "size": "cover",
  "position": "center"
}
```

* **`0.15`** — Very faint / minimal watermark effect.
* **`0.25`** — Balanced default (Recommended for clear text).
* **`0.35`** — High image visibility.

## 📄 License

Created by **vexis**. Free to use, modify, and share!
