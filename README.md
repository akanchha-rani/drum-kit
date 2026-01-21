# 🥁 Drum Kit Web Application

The **Drum Kit** is an interactive and responsive web application that allows users to play drum sounds directly in their browser. Users can create beats by either **clicking on drum buttons** or **pressing specific keyboard keys**, making it a fun project to explore JavaScript event handling and DOM manipulation.

This project is ideal for beginners learning **JavaScript**, **HTML**, and **CSS**, and demonstrates real-time user interaction with audio playback.


## 📌 Project Objectives

- Understand **JavaScript event listeners**
- Learn how to handle **keyboard and mouse events**
- Work with **audio files in JavaScript**
- Improve **UI feedback using animations**
- Build an interactive front-end project


## ✨ Features

### 🎶 Multiple Drum Sounds
Each drum button is mapped to a unique sound such as:
- Snare
- Kick
- Crash
- Tom drums

### ⌨️ Keyboard Interaction
- Users can play sounds using keyboard keys: W A S D J K L
- Each key triggers a specific drum sound instantly.

### 🖱️ Mouse Interaction
Clicking on any drum button plays the corresponding sound.

### 🎨 Button Animation
- Buttons animate briefly when pressed
- Visual feedback improves user experience
- Makes the application feel responsive and dynamic

### 📱 Responsive Design
The layout adapts to different screen sizes and works on:
- Desktop
- Tablet
- Mobile devices


## 🛠️ Technologies Used

| Technology | Purpose |
|----------|--------|
| **HTML5** | Structure of the web page |
| **CSS3** | Styling, layout, and animations |
| **JavaScript** | Event handling, audio control, and logic |


## 📂 Project Structure

drum-kit/
│
├── index.html # Main HTML file
├── styles.css # Styling and animations
├── index.js # JavaScript logic
├── sounds/ # Drum sound audio files
│ ├── crash.mp3
│ ├── kick-bass.mp3
│ ├── snare.mp3
│ └── tom-*.mp3
└── images/ # Button background images 


## ⚙️ How It Works

1. **Event Listeners**
   - JavaScript listens for:
     - `click` events on buttons
     - `keydown` events from the keyboard

2. **Sound Mapping**
   - Each key/button corresponds to a specific audio file
   - The correct sound is played using the `Audio()` object

3. **Animation Logic**
   - A CSS class is temporarily added to the pressed button
   - Removed after a short delay to create a press effect


📈 Future Enhancements

🎚️ Volume control slider

🎼 Record and replay beats

📱 Improved mobile UI

🎨 Theme customization

🎹 Add more instruments
