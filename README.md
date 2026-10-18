# Hemanth S — Interactive Scroll Animation Portfolio

A high-performance, single-page portfolio website featuring an Apple-style **scroll-scrubbed canvas animation** synchronized with modern, transparent, glassmorphic typography and UI cards.

🌐 **Live Website**: [https://hemanth001-s.github.io/portfolio/](https://hemanth001-s.github.io/portfolio/)

---

## ⚡ Tech Stack & Features

- **HTML5 `<canvas>` Engine**: 240 high-definition frames rendered with sub-frame Lerp interpolation at native display refresh rates (60Hz / 120Hz+).
- **GPU Asynchronous Decode**: `HTMLImageElement.prototype.decode()` preloads all frames off-thread for 0-latency scrubbing without stutter.
- **Lenis Smooth Scroll**: Buttery inertia and momentum scrolling across trackpad, mouse wheel, and mobile touch.
- **Glassmorphic UI**: Fully transparent layout with frosted glass cards (`backdrop-filter: blur(16px)`), allowing the video animation to shine through.
- **Responsive High-DPI**: Automatically scales to any screen aspect ratio (`object-fit: cover`) and retina pixel density (`devicePixelRatio`).

---

## 📂 Project Structure

```
portfolio/
├── frames/                       # 240 video frames (1280x720 JPEG)
├── index.html                    # Core application & scrub engine
├── lenis.min.js                  # Standalone Lenis v1.1.20 smooth scroll library
├── server.js                     # Zero-dependency local Node.js server
└── README.md                     # Project documentation
```

---

## 🛠️ Sections Overview

1. **Hero Section**:
   - `Welcome Recruiter`
   - Tagline: `— I AM THE ONE U ARE SEARCHING FOR !!!`
   - Statement: `TECHIE.` with amber-gold accent dot.

2. **About Me**:
   - Vertical typography: `ABOUT ME`
   - Interactive badge: [`hemanthsh967@gmail.com`](mailto:hemanthsh967@gmail.com)
   - Detailed bio covering AI, Cloud Computing, Software Development, IT Automation, and Computer Vision.
   - Signature: `Hemanth S`

3. **Work Experience & Showcase**:
   - `WORK EXPERIENCE` & Education: `Bachelor of computer applications`
   - **PROJECTS**:
     1. Hand gesture mouse control system
     2. Frontend web development
     3. Digital marketing for farmers
     4. Password analyzer
   - **PORTFOLIO LINKS**: [GitHub](https://github.com/hemanths288) & [LinkedIn](https://www.linkedin.com/in/hemanth20)
   - **SOFT SKILLS**: Leadership, Communication Skills, Problem Solving, Quick Learner, Attention to Detail, Active Listening, Critical Thinking
   - **SKILLS**: Java, Python, HTML/CSS, MySQL, AI Agents, Microsoft 360, AWS / AZURE, OOPS, ServiceNow, Digital Marketing
   - **PROFESSIONAL SUMMARY**:
     - System Engineer — Cognizant (Aug - Oct 2026)
     - Cyber Security Intern — Elevate Labs (Sept 2025 - Jan 2026)
     - Web Development Intern — Internpe (Feb - April 2025)
   - **CONTACT**: Email, Phone (`+91 9353525539`), Location (`BANGLORE`)

---

## 🚀 Local Development

To run locally:
```bash
node server.js
```
Then open `http://localhost:3000/` in your browser.
