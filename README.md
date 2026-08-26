# 🥁 Beatify

> A modern, interactive electronic drum kit built with **HTML5**, **CSS3**, **JavaScript**, and the **Web Audio API**.

**Beatify** lets users create beats directly in their browser using interactive electronic drum pads. Play sounds using your keyboard, mouse, or touch, adjust the mixer, control bass and treble, change the master volume, and enjoy an automatic demo beat — all from a single HTML file.

---

## ✨ Features

* 🥁 Interactive electronic drum pads
* ⌨️ Keyboard controls
* 🖱️ Mouse and touch support
* 🎵 Kick, snare, hi-hat, toms, crash, ride, clap and percussion
* 🎚️ Individual drum volume controls
* 🎛️ Built-in mixer system
* 🔊 Master volume control
* 💥 Bass EQ control
* ✨ Treble EQ control
* ▶️ Automatic demo beat
* ⏹️ Stop demo playback
* ↺ Reset mixer controls
* 💡 Animated drum-pad feedback
* 🖥️ Digital status display
* 📱 Responsive design
* 🎨 Modern electronic drum-machine interface
* ⚡ Real-time sound generation
* 🚫 No external dependencies
* 📄 Single HTML file
* 🌐 Runs directly in modern browsers

---

## 🖥️ Tech Stack

* HTML5
* CSS3
* JavaScript
* Web Audio API
* CSS Grid
* JavaScript DOM API
* Responsive Web Design

---

## 🚀 Live Project

View the source code on GitHub:

[🥁 Beatify — GitHub Repository](https://github.com/suchitrachendake97/Beatify)

---

## 📦 Installation

No installation or external dependencies are required.

### Clone the repository

```bash
git clone https://github.com/suchitrachendake97/Beatify.git
```

### Go into the project

```bash
cd Beatify
```

### Open the project

Simply open:

```text
index.html
```

in any modern web browser.

You can also double-click the HTML file to run Beatify directly.

---

# 🥁 How It Works

Beatify uses the **Web Audio API** to generate electronic drum sounds directly inside the browser.

No external audio files are required.

Different sounds are created using oscillators, noise generators, gain nodes, and audio filters.

For example, the kick drum uses an oscillator whose frequency rapidly decreases:

```javascript
osc.frequency.setValueAtTime(150, now);
osc.frequency.exponentialRampToValueAtTime(42, now + 0.35);
```

Noise generators are used for sounds such as:

* Snare
* Hi-Hat
* Crash
* Clap
* Ride

Oscillators are used for:

* Kick
* Toms
* Rim
* Percussion

This makes Beatify lightweight while still providing interactive drum sounds.

---

# ⌨️ Keyboard Controls

Beatify can be played directly using your computer keyboard.

| Key | Drum Sound |
| --- | ---------- |
| `Q` | Kick       |
| `W` | Snare      |
| `E` | Hi-Hat     |
| `R` | Crash      |
| `A` | Tom 1      |
| `S` | Tom 2      |
| `D` | Tom 3      |
| `F` | Ride       |
| `Z` | Clap       |
| `X` | Rim        |
| `C` | Percussion |
| `V` | Floor Tom  |

Simply press a key to trigger the corresponding drum pad.

---

# 🎛️ Mixer System

Beatify includes a built-in mixer for controlling individual drum channels.

### 🥁 Kick

Controls the kick drum volume.

### 🥁 Snare

Controls the snare volume.

### 🪘 Toms

Controls the tom volume.

### 🔔 Cymbal

Controls crash and cymbal volume.

### 🔊 Master

Controls the overall output volume.

The mixer allows users to customize the balance of the drum kit while playing.

---

# 🎚️ Audio Controls

Beatify includes real-time audio controls.

### 💥 Bass

Adjusts the low-frequency response of the drum kit.

### ✨ Treble

Adjusts the high-frequency response.

### 🔊 Master Volume

Controls the overall output level.

Beatify uses Web Audio API filters and gain nodes to process the generated sounds.

---

# ▶️ Demo Beat

The **Demo Beat** button automatically plays a predefined electronic drum pattern.

The demo uses:

* Kick
* Snare
* Hi-Hat
* Ride
* Crash

The beat continues playing until the **Stop** button is pressed.

This gives Beatify a simple electronic drum-machine experience.

---

# ↺ Reset Controls

The **Reset Mixer** button restores the audio controls to their default values.

It resets:

* Kick volume
* Snare volume
* Hi-Hat volume
* Bass
* Treble
* Master volume

This makes it easy to return to the default Beatify configuration.

---

# 🎨 User Interface

Beatify features a modern electronic music-machine inspired interface.

The design includes:

* 🌑 Dark electronic theme
* 🔴 Neon red accents
* 🥁 Large interactive drum pads
* 🎛️ Mixer controls
* 🎚️ Audio controls
* 💡 Active pad animations
* 🖥️ Digital status display
* ✨ Gradients and soft shadows
* 📱 Responsive layout

The interface is designed to provide a compact electronic drum-machine experience directly in the browser.

---

# 📱 Responsive Design

Beatify automatically adapts to different screen sizes using responsive CSS.

It works on:

* 🖥️ Desktop
* 💻 Laptop
* 📱 Mobile
* 📲 Tablet

The drum pads and controls automatically rearrange themselves for smaller screens.

No CSS framework is required.

---

# 📁 Project Structure

```text
Beatify/
│
├── index.html
├── README.md
└── LICENSE
```

The complete application is contained inside:

```text
index.html
```

The file includes:

* HTML structure
* CSS styling
* JavaScript logic
* Drum sound generation
* Keyboard controls
* Mouse controls
* Touch controls
* Mixer system
* Bass and treble controls
* Master volume
* Demo beat
* Responsive design

---

# 🎯 Use Cases

Beatify can be useful for:

* 🥁 Music experimentation
* 🎵 Beat creation
* 🎚️ Audio experimentation
* 🧪 Web Audio API learning
* 📚 Student projects
* 💻 JavaScript learning
* 🎨 Creative coding
* 🌐 Frontend portfolio projects
* 🎧 Browser-based music tools
* 🥁 Electronic drum practice

---

# 🧠 Concepts Demonstrated

This project demonstrates several useful web-development concepts:

* HTML5 structure
* CSS Grid layouts
* Responsive CSS
* JavaScript DOM manipulation
* Event handling
* Keyboard events
* Pointer events
* Web Audio API
* Oscillator synthesis
* Noise generation
* Audio filters
* Gain control
* Real-time audio processing
* Dynamic UI updates
* Interactive controls
* Responsive interface design

---

# 🔮 Future Improvements

Possible future enhancements include:

* 🎼 Custom beat sequencer
* 🥁 Step-by-step drum pattern editor
* 🎚️ Individual channel EQ
* 🎛️ Pan controls
* 🔊 Reverb and delay effects
* 🎵 Adjustable BPM
* 🔴 Beat recording
* 💾 Save drum patterns
* 📤 Export beats
* 🎧 Headphone mode
* 🎹 MIDI keyboard support
* 🥁 More realistic drum samples
* 🌈 Multiple visual themes
* 📱 Progressive Web App support
* ☁️ Cloud beat saving
* 👥 Beat sharing

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/amazing-feature
```

3. Make your changes
4. Commit your changes

```bash
git commit -m "Add amazing feature"
```

5. Push your branch

```bash
git push origin feature/amazing-feature
```

6. Open a Pull Request

---

# 📄 License

This project is licensed under the **MIT License**.

See the `LICENSE` file for more information.

---

# ⭐ Show Your Support

If you like **Beatify**:

⭐ Star the repository

🍴 Fork the project

🐞 Report bugs

💡 Suggest improvements

🚀 Build your own beats

🎵 Create something creative

🥁 Share Beatify with other music lovers

---

## 👨‍💻 Author

**Suchitra Chendake**

AI & Full Stack Developer

Interested in:

* 🤖 Artificial Intelligence
* 🧠 Machine Learning
* 👁️ Computer Vision
* 🌐 Web Development
* 🎨 UI/UX Design
* 💻 Creative Coding

---

## 🥁 Made with

**HTML + CSS + JavaScript + Web Audio API**

Made with ❤️, 🎵 and a little bit of code.

---

## 🔗 Repository

**Beatify — Electronic Drum Kit**

https://github.com/suchitrachendake97/Beatify.git
