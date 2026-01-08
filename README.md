# 🚦 Glassmorphism Traffic Light

A modern, animated **traffic light simulation** built with **HTML, CSS, and JavaScript**.  
This project combines **glassmorphism design**, glowing LED effects, ambient background animations, and interactive controls to create a realistic yet futuristic traffic light experience.

---

## ✨ Features
- 🎨 **Glassmorphism UI** with frosted glass, bevels, and glossy highlights
- 💡 **Realistic LED Lamps** (Red, Yellow, Green) with glow and active states
- 🌌 **Ambient Background Animation** for a digital, futuristic feel
- 🔩 **Decorative Screws & Industrial Flair**
- 📱 **Responsive Design** for mobile and desktop
- ⚙️ **Interactive Controls**:
  - Manual buttons to activate **Red, Yellow, Green**
  - **Auto Mode** cycles through lights automatically (Red → Green → Yellow)
  - Auto indicator with pulsing dot animation

---

## 🛠️ Technologies Used
- **HTML5** – semantic structure
- **CSS3** – gradients, blur effects, animations, glassmorphism styling
- **JavaScript (ES6)** – event handling, lamp activation, auto cycling logic

---

## ⚙️ JavaScript Logic Overview
The interactivity is powered by `script.js`:

- **Lamp Activation (`setActive`)**
  - Removes `active` class from all lamps
  - Adds `active` class to the selected lamp (Red, Yellow, Green)

- **Manual Controls**
  - Buttons allow direct activation of each lamp
  - Cancels auto cycle when manually selected

- **Auto Cycle (`cycle`)**
  - Cycles through Red → Green → Yellow with realistic delays:
    - Red → 2.5s  
    - Green → 3.2s  
    - Yellow → 1.6s  
  - Updates automatically using `setInterval`

- **Auto Mode Button**
  - Starts continuous cycling
  - Displays **Auto Indicator** with pulsing green dot

---

## 🚀 Getting Started

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ChiFrontEnd/CSS-TrafficLight.git
   
2. Navigate to the project folder:
   ```bash
   cd CSS-TrafficLight
   
4. Open ```index.html``` in your browser.

---

## 🎮 Usage

- Click Red, Yellow, Green buttons to manually control the lights.

- Press Auto to enable automatic cycling between lights.

- Watch the Auto Indicator pulse when cycling is active.

- Resize the window to see responsive adjustments.

---

## 📸 Screenshots

(Add screenshots or GIFs of the traffic light in action — red, yellow, green states, and auto mode)

---

## 🔮 Future Improvements

- ⏱ Countdown Timer for each light to simulate real traffic signals

- 🚶 Pedestrian Crossing Signal with walk/stop icons

- 🔊 Sound Effects for transitions (e.g., beeps for pedestrian mode)

- 🌐 Live Demo Hosting via GitHub Pages or Netlify

- 🎥 Animated GIFs in README to showcase auto cycling visually

---

## 🤝 Contributing
Pull requests are welcome!  
For major changes, please open an issue first to discuss improvements.  

Ideas for new features are encouraged, such as:  
- 🚶 Pedestrian signals  
- ⏱ Countdown timers  
- 🔊 Sound effects  

---

## 📜 License
This project is for **personal/educational use only**.  
© 2025 Glassmorphism Traffic Light Project

---

