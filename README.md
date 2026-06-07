# 🔮 Glassmorphism Digital Clock, Alarm & Stopwatch

A premium, visually stunning web-based digital watch experience featuring interactive clock displays, multiple alarms with custom sound selection, and a millisecond-precise stopwatch. Built entirely using vanilla HTML, CSS, and modern ES6 JavaScript.

Developed under the tag **DailyBuildup** / **#Hello Coder's** 🚀

---

## ✨ Features

- **🔮 Glassmorphism Design**: Elegant UI utilizing backdrop filters (`blur`), semi-transparent borders, vibrant background gradients, and dynamic animated blob shapes drifting in the background.<img width="1918" height="1078" alt="Screenshot 2026-06-07 152243" src="https://github.com/user-attachments/assets/9eb83c6a-b51e-4770-ae83-184d6fb059a6" />

- **🕒 Interactive Clock Mode**: Shows the current time in a 12-hour format (hours and minutes) with separate floating indicators for seconds, AM/PM, and localized day/date formatting.
- **📊 Circular Progress Rings**: Three nested SVG arcs that visually fill up corresponding to the current hours, minutes, and seconds in real-time.
- **⏰ Multi-Alarm Sidebar**: 
  - Set multiple active alarms at precise times.
  - Choose from 10+ distinct custom digital alarm tones (Beeps, Classic Rings, Sci-Fi alerts, Radar, etc.).
  - Play or stop live previews of selected alarm tones.
  - Interactive alarm list with individual deletion buttons.
  - Dynamic blinking alert overlay with a **Stop** button when an alarm triggers.
- **⏱️ Stopwatch Mode**: 
  - Millisecond-accurate stopwatch.
  - Integrated start, pause, and reset controls using the centralized control hub.
  - Arcs adjust dynamically to show progress for milliseconds, seconds, and minutes.
- **🕶️ Interactive 3D Tilt Effect**: The clock container tilts dynamically in 3D space based on mouse hover position, creating a premium depth effect (disabled on mobile for performance).
- **📱 Fully Responsive**: Custom media queries scale down the clock rings, reposition floating labels, and convert the alarm setup sidebar into a collapsible dropdown list on smaller displays.

---

## 🛠️ Tech Stack

- **Structure**: Semantic [HTML5](file:///c:/Users/ppatw/OneDrive/%EB%AC%B8%EC%84%9C/My%20Project/Hello%20Coder%27s/glass-digital-clock/index.html)
- **Styling**: Modern [CSS3](file:///c:/Users/ppatw/OneDrive/%EB%AC%B8%EC%84%9C/My%20Project/Hello%20Coder%27s/glass-digital-clock/style.css) (Custom fonts from Google Fonts, Flexbox, CSS Variables, SVG Stroke animations, Keyframe Animations, Backdrop Filter)
- **Logic**: Pure [ES6+ JavaScript](file:///c:/Users/ppatw/OneDrive/%EB%AC%B8%EC%84%9C/My%20Project/Hello%20Coder%27s/glass-digital-clock/script.js) (RequestAnimationFrame for smooth updates, DOM manipulation, 3D coordinates calculation, HTML5 Audio API)

---

## 📂 Project Structure

```text
glass-digital-clock/
├── index.html        # Main webpage layout, alarm configurations, SVGs, and audio tags
├── style.css         # Typography, glassmorphism design, keyframe animations, and mobile responsiveness
├── script.js         # Clock updating logic, stopwatch handler, alarm trigger systems, and 3D hover effects
└── README.md         # Documentation and guide
```

---

## 🚀 How to Run Locally

Since this project uses vanilla technologies, there are no build steps or dependencies to install.

### Method 1: Double Click
1. Download or clone this repository.
2. Locate the [index.html](file:///c:/Users/ppatw/OneDrive/%EB%AC%B8%EC%84%9C/My%20Project/Hello%20Coder%27s/glass-digital-clock/index.html) file in your file explorer.
3. Double-click it to open it in your default web browser.

### Method 2: Local Server (Recommended for Audio)
To ensure HTML5 audio playbacks and third-party asset streams work flawlessly without browser security restrictions, serve it using a local server:

Using Node.js:
```bash
# Install a lightweight server globally
npm install -g serve

# Serve from the project directory
serve .
```

Or using Python:
```bash
# Python 3
python -m http.server 8000
```
Then visit `http://localhost:8000` or `http://localhost:3000` in your browser.

---

## 🎨 Design Aesthetics & Details

- **Typography**: Uses the modern, clean `Outfit` font from Google Fonts.
- **Harmonious Palettes**: 
  - Second Ring Gradient: Red to Purple (`#df8a8a` to `#8a2387`)
  - Minute Ring Gradient: Violet to Light Purple (`#6b30c3` to `#b671ff`)
  - Hour Ring Gradient: Pink to Lavender (`#ffafbd` to `#b984ff`)
  - Moving Background: Dynamic four-color pastel gradient animation.
- **Glassmorphic Effect**: Created using `rgba(255, 255, 255, 0.3)` background, standard `1px solid rgba(255,255,255,0.5)` borders, and `backdrop-filter: blur(15px)`.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page or submit pull requests to enhance the styles, add new widgets, or optimize the stopwatch accuracy.

---

*Designed and Developed with ❤️ by Pankaj buildUp (2026).*
<img width="1918" height="1078" alt="Screenshot 2026-06-07 152243" src="https://github.com/user-attachments/assets/34fae3a3-ded9-4f79-b4ad-de89ac60f2da" />
