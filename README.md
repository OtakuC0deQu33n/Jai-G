# 💻 Jai G. — Software Developer Portfolio

A sleek, **futuristic portfolio website** built entirely with **HTML and CSS**.  
This project showcases a portion of my developer profile, projects, and creative identity through a modern, layered glass and aurora design.

---

## ✨ Overview

This portfolio was designed to demonstrate:
- Clean, semantic **HTML5 structure**
- Advanced **CSS-only visual effects**
- A smooth, futuristic user experience without JavaScript
- Fully **responsive layout** for all devices

---

## 🧩 Features

### 🎨 Visual Style
- **Aurora gradient layer** that gives a luminous sci-fi atmosphere  
- **Particle animation background** made with simple CSS keyframes  
- **Glass panels** using `backdrop-filter: blur(10px)` and transparency  
- **Soft shadows & glow effects** accentuating the main color palette  

### 🧱 Layout
- **Sticky Navbar** for quick navigation between sections  
- **Smooth section flow** — Hero, About, Projects, Skills, Contact  
- **Dedicated photo space** for your personal image in the About section  
- **Responsive project grid** with hover transitions  
- **Minimal color scheme** inspired by modern tech interfaces  

### 🧑‍💻 Code Simplicity
- **No JavaScript required** — all interactivity and motion handled in CSS  
- **Lightweight and fast**, ideal for hosting on GitHub Pages or Netlify  
- Built with modular sections and reusable CSS classes  

---

## 🗂 Folder Structure

portfolio/
├── index.html # Page layout and section structure
├── style.css # Visual styling, gradients, and animations
└── assets/
├── profile.jpg # Personal image used in the About section
├── logo.png # Portfolio logo or favicon
└── project/ # Screenshots or images for projects



---

## 🎨 Key Design Variables

Located at the top of `style.css` for quick customization:

```css
:root {
  --primary: #0fb8ff;        /* Main accent color */
  --bg-dark: #0d0f17;        /* Deep background */
  --bg-glass: rgba(255,255,255,0.05);
  --light: #eaf2ff;          /* Text color on dark */
  --muted: #9fb2cc;          /* Subtext color */
  --radius: 12px;
  --shadow: 0 8px 25px rgba(0,0,0,.45);
  --blur: blur(10px);
  --transition: all 0.3s ease;
}



🧠 How It Was Designed

The design follows a layered composition technique using only HTML and CSS:

Background Layers

A <div class="background"> container holds both the aurora gradient and moving particle elements.

The aurora effect is created with a radial-gradient blend animated by background-position shifts.

Tiny <div class="particle"> elements are placed in a loop with subtle opacity and blur, animated through @keyframes to drift slowly — creating a sense of depth.

Glass & Content Panels

Sections (About, Projects, etc.) sit atop a translucent glass layer (rgba(255,255,255,0.05)).

A backdrop-filter: blur(10px) gives the illusion of frosted glass.

Light shadows (box-shadow) and border radii add smooth, modern curves.

Typography & Layout

The design uses a sans-serif, tech-style font for clarity.

CSS Grid & Flexbox ensure consistent spacing across devices.

All transitions (hover, background glow, color shifts) use a unified timing function from --transition.

Color & Lighting

The main accent --primary: #0fb8ff is applied to headings, highlights, and interactive elements.

Subtle glows and text shadows create a luminous “underlight” effect typical of futuristic UI design.

This method keeps the project lightweight, maintainable, and aesthetically dynamic without any scripts or external libraries.



Author: Jai G. (Jaileta Gaither)
Theme: Futuristic Tech-Pro / Glass & Aurora Style
