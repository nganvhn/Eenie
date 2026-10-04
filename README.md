Here is a documentation file (`README.md`) for your project based on `index.html`:

---

🎲 `eenie.` — Random Picker

**eenie.** is a lightweight, single-file web application designed to help make decisions fun and effortless. Featuring smooth animations, multiple selection visual styles, and rich icon fallbacks, it turns everyday choices into engaging random picks.

---

✨ Features

* **3 Distinct Pick Styles (Modes)**:


* **Slot Reel**: Classic spinning slot-machine animation.


* **Shuffle**: Dynamic jittering shuffle animation.


* **Spotlight**: Decelerating tile highlight hopping until a winner is selected.




* **Preset & Custom Categories**:
* Pre-populated categories for Food, Sweets, Animals, Travel, and Activities.


* Intelligent keyword search/categorization matching.


* Claude AI integration fallback to generate custom category choices and emoji suggestions on the fly.




* **Customizable Options**: Add, edit, or remove options in real-time.


* **Dynamic Icons**:
* Uses Microsoft Fluent 3D Emoji assets by default.


* Standard Unicode emoji backup.


* Algorithmic color-gradient fallback avatars.




* **Keyboard Shortcuts**:
* Press `Space` to initiate a pick.


* Press `Esc` to close the result overlay.




* **Zero Build Tools Required**: Built using React and HTM loaded directly via CDN in a standalone HTML file.



---

🚀 Quick Start

Because **eenie.** is built as a self-contained web app inside a single HTML file, getting started requires no node installation or build steps:

1. Download or save `index.html` locally.


2. Double-click `index.html` or open it in any modern web browser.



---

🛠️ Configuration & Settings

Inside `index.html`, you can tweak default settings directly in the `CONFIG` object:

```javascript
const CONFIG = {
  mode: 'reel',        // Default picker style: 'reel', 'shuffle', or 'spotlight'
  duration: 3.2,       // Animation duration in seconds
  avoidRepeats: true   // Avoid picking the same item back-to-back when >2 items exist
};
```[cite: 1]

---

🧰 Tech Stack & Dependencies

- **Frontend Framework**: [React 18](https://react.dev/) (via CDN)[cite: 1]
- **DOM Rendering**: [ReactDOM 18](https://react.dev/) (via CDN)[cite: 1]
- **Templating**: [HTM (Hyperscript Tagged Markup)](https://github.com/developit/htm) (allows JSX-like syntax without JSX compilation)[cite: 1]
- **Iconography**: [Microsoft Fluent UI Emoji (3D)](https://github.com/microsoft/fluentui-emoji)[cite: 1]
- **Typography**: [Bricolage Grotesque](https://fonts.google.com/specimen/Bricolage+Grotesque) & [DM Mono](https://fonts.google.com/specimen/DM+Mono) via Google Fonts[cite: 1]

---

📜 License

Distributed under the open-source MIT License[cite: 1].

```
