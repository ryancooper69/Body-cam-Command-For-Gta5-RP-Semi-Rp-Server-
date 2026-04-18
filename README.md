# Body-cam-Command-For-Gta5-RP-Semi-Rp-Server-
A futuristic cyberpunk-style dashboard for navigating department-based command pages, featuring smooth animations, interactive backgrounds, and a modern responsive UI.
# 🚀 Los Santos Hub — Command Central

A futuristic, cyberpunk-style dashboard interface for navigating department-specific command pages. Built using **HTML, CSS (Tailwind + custom styles), and JavaScript**, this project delivers an immersive UI experience with advanced animations, loaders, and transitions.

---

## ✨ Features

### 🎨 Modern UI/UX
- Cyberpunk-inspired design with glowing gradients and glassmorphism
- Fully responsive layout for desktop and mobile
- Custom typography using Orbitron, Rajdhani, and Share Tech Mono

### ⚡ Advanced Animations
- Smooth page entry and exit transitions
- Animated loading screen with:
  - Multi-layer spinner
  - Dynamic progress bar
  - Status message updates
- Hover effects with visual feedback and subtle sound

### 🌌 Dynamic Background
- Interactive animated background powered by **Vanta.js (NET effect)**
- Layered visual effects:
  - Grid overlay
  - Scanlines
  - Gradient shading

### ✨ Particle System
- Floating animated particles (purple & white)
- Randomized motion, timing, and positioning

### 🔗 Navigation System
- Department-based navigation cards:
  - 🕵️ FIB Commands
  - 👮 LSPD Commands
  - 🚔 SAHP Commands
  - 🏛️ Government Commands
  - 🪖 National Guard Commands
  - 💀 Bad Cops Commands
- Smooth transition animation between pages

---

## 📁 Project Structure

```
project-root/
│── index.html        # Main dashboard page
│── fibbyryan.html    # FIB commands
│── lspdbyryan.html   # LSPD commands
│── sahpbyryan.html   # SAHP commands
│── govbyryan.html    # Government commands
│── ngbyryan.html     # National Guard commands
│── biobyryan.html    # Bad cops commands
```

---

## 🛠️ Technologies Used

- HTML5
- Tailwind CSS (CDN)
- Vanilla JavaScript
- Vanta.js (animated backgrounds)
- Three.js (dependency for Vanta)
- Google Fonts

---

## ⚙️ Setup & Usage

1. Clone or download this repository  
2. Place all HTML files in the same directory  
3. Open `index.html` in your browser  

No build tools or installations required — everything runs via CDN.

---

## 🎮 How It Works

### Loader System
- Simulates system initialization with progressive loading
- Randomized progress increments for realism
- Displays dynamic system messages

### Page Transitions
- Intercepts link clicks
- Plays exit animation before navigation
- Creates a smooth, app-like experience

### Background Engine
- Uses Vanta.NET to render animated node connections
- Fully interactive with mouse movement

---

## 🔊 Audio Effects
- Subtle hover sound on card interaction
- Uses lightweight audio playback with fallback handling

---

## 📱 Responsiveness

- Optimized for:
  - Desktop 💻
  - Tablet 📱
  - Mobile 📱
- Adaptive grid layout and typography scaling

---

## ♿ Accessibility

- Respects `prefers-reduced-motion`
- Disables animations for users who prefer minimal motion

---

## 📌 Customization

You can easily modify:

- 🎨 Colors via CSS variables (`:root`)
- ⚡ Animation timing and effects
- 🧩 Add/remove departments
- 🌌 Background settings in Vanta config
- 🔊 Sound effects

---

## 🧠 Author

**Ryan Cooper**  
> "//- Made By Ryan Cooper 🛡️-\\"

---

## 📜 License

This project is open for personal and educational use.  
Modify and expand as needed.

---

## 💡 Future Improvements

- Add backend integration
- Save user preferences
- Dark/light theme toggle
- Command search functionality
- Authentication system
