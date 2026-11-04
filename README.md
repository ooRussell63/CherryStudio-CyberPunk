# CherryStudio Cyberpunk Theme 🌈⚡

<div align="center">
  <img src="screenshots/v2.1.10-preview.png" alt="Theme Preview" width="800">
</div>

**A stunning cyberpunk-themed CSS for CherryStudio with neon effects**

[English](README.md) | [简体中文](README_CN.md)

## ✨ Features

- 🎨 **Cyberpunk Aesthetic**: Dark theme with cyan, neon pink, and hacker green
- 🌈 **Neon Effects**: Glowing borders and animated effects
- 💻 **Enhanced Code Blocks**: Special styling with hacker-green borders
- ⚡ **Smooth Animations**: Fluid transitions and hover effects

## ✅ Compatibility

Currently verified: **Cherry Studio 2.1.10 · macOS · dark mode**.

Checked in the installed app: the main view, neon input focus animation, a Python code block returned by a live model (including syntax highlighting and copy), mini-app tabs, and two-app split view. Windows, Linux, and other versions have not been tested on-device. Component styling may change with Cherry Studio updates.

Legacy compatibility is outside the current maintenance scope. The historical mini-app transparency report ([issue #1](https://github.com/ooRussell63/CherryStudio-CyberPunk/issues/1)) is not backported or marked as fixed by this update.

## 🖼️ Current preview

Recorded in **Cherry Studio 2.1.10 on macOS**, using this repository's CSS.

**Green terminal code block and neon input animation** (a real model response)

![Cherry Studio 2.1.10 green terminal and neon input animation](screenshots/v2.1.10-neon.gif)

**Mini-app tabs and split view**

![Cherry Studio 2.1.10 mini-app and split-view demo](screenshots/v2.1.10-miniapps.gif)

Embedded websites keep their own appearance; this theme styles the Cherry Studio interface.

## 🚀 Installation

1. **Download the CSS file or Copy the code directly**: [cyberpunk-theme.css](cyberpunk-theme.css)

2. **Apply to CherryStudio**:
   - Open CherryStudio
   - Go to Settings → Appearance → Custom CSS
   - Copy and paste the CSS content
   - Switch the theme to "Dark" mode
   - The custom CSS takes effect automatically

## 🎨 Customization

You can modify these color variables at the top of the CSS file:

```css
:root {
  --cyber-cyan: #00ffff;
  --cyber-pink: #ff0080;
  --cyber-green: #00ff41;
  /* ... more colors */
}
```

## 🙏 Credits

This theme is based in large part on [CherryStudio-Aero](https://github.com/hakadao/CherryStudio-Aero) by [hakadao](https://github.com/hakadao), especially its [original style.css](https://github.com/hakadao/CherryStudio-Aero/blob/main/style.css). The base color variables, transparency handling, and component background rules were adapted from that project. Thank you for the original work!

This project adds the cyberpunk palette, neon effects, animations, and code-block styling. See the [upstream license](https://github.com/hakadao/CherryStudio-Aero/blob/main/LICENSE) for CherryStudio-Aero's licensing terms.

## 🤝 Contributing

Found a bug or want to suggest improvements? Feel free to [open an issue](https://github.com/ooRussell63/CherryStudio-CyberPunk/issues)!

---

<div align="center">
⭐ Star this repo if you like it!

</div>

