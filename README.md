# 🥁 Drum Kit JS

A fun, interactive virtual drum kit web application built using HTML, CSS, and JavaScript. Play sounds by clicking on the drum pads or pressing keys on your keyboard — each pad is mapped to a specific key and sound.

---

## 🔑 Features

- Click or press keys (`w`, `a`, `s`, `d`, `j`, `k`, `l`) to play different drum sounds  
- Visual feedback using animation (`.pressed` class)  
- Fully responsive and styled layout  
- Keyboard event listeners (`keydown`) and mouse click handling  

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

```
drum-kit-js/
│
├── index.html         # Main HTML structure of the drum kit app
├── styles.css         # Styling for the drum kit UI
├── index.js           # JavaScript to handle sound playback and animations
├── /sounds/           # Folder containing .mp3 sound files for each drum pad
│   ├── tom-1.mp3
│   ├── tom-2.mp3
│   └── ...
└── /images/           # Folder for background images of the drum pads
```

---

## 🚀 Getting Started

To set up and run the Drum Kit JS web application locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Rishifanterboy/Drum-kit-js.git
    ```

2. **Navigate to the project folder**:
    ```bash
    cd Drum-kit-js
    ```

3. **Open the `index.html` file** in your browser to start playing the drum kit. Simply double-click the `index.html` file, and it will open in your default web browser.

---

## 🎨 UI Design

The drum kit app is designed with a clean, responsive layout. Each drum pad is styled with appropriate background images. When a drum pad is pressed (either by clicking or using the keyboard), the `.pressed` class applies a brief animation to visually indicate the pad that was activated.

---

## 🧑‍💻 Usage

1. Open the app in your browser.
2. Click on any of the drum pads or press the corresponding key (`w`, `a`, `s`, `d`, `j`, `k`, `l`) on your keyboard.
3. The corresponding sound will play, and the drum pad will visually "press down" with an animation.

---

## 🛠️ Tech Stack

- **HTML5**: For the structure of the drum kit web app.
- **CSS3**: For styling and responsive design to ensure the app works across devices.
- **JavaScript**: For sound playback, handling keyboard/mouse events, and animations.


