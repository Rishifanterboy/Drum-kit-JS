# 🥁 Drum Kit JS

A fun, interactive virtual drum kit built using HTML, CSS, and JavaScript. Play sounds by clicking on the drum pads or pressing keys on your keyboard — each pad is mapped to a specific key and sound.

---

## 🔑 Features

-  Click or press keys (`w`, `a`, `s`, `d`, `j`, `k`, `l`) to play different drum sounds  
-  Visual feedback using animation (`.pressed` class)  
-  Fully responsive and styled layout  
-  Keyboard event listeners (`keydown`) and mouse click handling  

---

## 🎹 Drum Key Mappings

| Key | Sound      |
|-----|------------|
| w   | Tom 1      |
| a   | Tom 2      |
| s   | Tom 3      |
| d   | Tom 4      |
| j   | Snare      |
| k   | Kick Bass  |
| l   | Crash      |

---

## 📂 Project Structure

```bash
drum-kit-js/
│
├── index.html         # Main HTML structure
├── styles.css         # Styling for the drum kit
├── index.js           # JavaScript for sound and animation
├── /sounds/           # Folder containing .mp3 sound files
│   ├── tom-1.mp3
│   ├── tom-2.mp3
│   └── ...
└── /images/           # Background images for drum buttons

