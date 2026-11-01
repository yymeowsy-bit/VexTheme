# Vermont Discord Theme

A sleek, dark midnight purple theme for Discord mobile clients (such as Vendetta, Replugged, or Aliucord).

---

## 🎨 Preview & Features

- **Primary Colors:** Deep obsidian black with vivid purple accents.
- **Background:** Subtle anime background with optimized opacity (`0.25`) for maximum legibility.
- **Contrast Fixed:** Clear, high-contrast text for easy reading.

---

## 🚀 Installation Guide

### Option 1: Direct Link (Recommended)

1. Open your modified Discord app on mobile.
2. Go to **User Settings** $\rightarrow$ **Themes**.
3. Tap **Install Theme** or **Fetch Theme**.
4. Paste the following URL:
   ```text
   https://yymeowsy-bit.github.io/VexTheme/Vermont.json
   ```
   *(Alternatively, use the raw GitHub link: `https://raw.githubusercontent.com/yymeowsy-bit/VexTheme/main/Vermont.json`)*
5. Press **Install** and select **Apply Theme**.

---

### Option 2: Manual File Load

1. Download the `Vermont.json` file directly from this repository.
2. Transfer or save the file onto your device storage.
3. Open Discord, navigate to **Settings** $\rightarrow$ **Themes**.
4. Tap **Import from File** (or the folder icon) and choose `Vermont.json`.

---

## 🛠️ Customization

If you want to adjust the background image visibility, open `Vermont.json` in any text editor and change the `"alpha"` parameter at the bottom of the file:

```json
"background": {
  "url": "YOUR_IMAGE_URL",
  "alpha": 0.25,
  "size": "cover",
  "position": "center"
}
```

* **`0.15`** — Very faint watermark effect.
* **`0.25`** — Balanced visibility (Default).
* **`0.35`** — High image visibility.

---

## 📄 License

Created by **vexis**. Free to use and edit!
