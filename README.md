# Personal Portfolio Website
A modern, responsive portfolio website showcasing my projects, skills, and experience as a Computer Science student. Built with clean HTML, CSS, and JavaScript, featuring bilingual support (English/Arabic) and an elegant dark/light theme system.

[![Live Demo](https://img.shields.io/badge/demo-live-success?style=for-the-badge)](https://rawanmismail.github.io/personal-website)
[![GitHub](https://img.shields.io/badge/github-repository-181717?style=for-the-badge&logo=github)](https://github.com/rawanmismail/personal-website)


### Design
- **Clean & Minimal Design** — Aesthetic brown color scheme with professional styling
- **Dark/Light Mode** — Toggle between themes with smooth transitions
- **Bilingual Support** — Full English and Arabic versions
- **Smooth Animations** — Typing effects, scroll animations, and hover interactions
- **Scroll Progress Bar** — Visual indicator at the top showing page progress
- **Custom Cursor** — Interactive cursor design (desktop only)
- **Fully Responsive** — Optimized for all devices (mobile, tablet, desktop)

### 🚀 Functionality
- **Single Page Navigation** — Smooth scroll to sections
- **Animated Typing** — Dynamic text showcasing specialties
- **Skill Progress Bars** — Visual representation of skill levels with animations
- **Contact Form** — Functional form with success modal
- **Back to Top Button** — Quick navigation to top of page
- **Fade-in Animations** — Content reveals as you scroll

### 📱 Sections
1. **Hero** — Introduction with typing animation and social links
2. **About** — Personal bio, location, and interests
3. **Education** — Foundation year at Heriot-Watt University
4. **Volunteering** — Leadership and community service experience
5. **Skills** — Technical and soft skills with progress indicators
6. **Certifications** — Professional development achievements
7. **Awards** — Robotics competition recognition
8. **Projects** — Portfolio of web development and database projects
9. **Contact** — Email, phone, social links, and contact form



## 🛠️ Tech Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)


**Built with:**
- Pure HTML5, CSS3, and Vanilla JavaScript
- Font Awesome 6.4.0 for icons
- CSS Custom Properties for theming
- CSS Grid & Flexbox for layouts
- Intersection Observer API for scroll animations
- LocalStorage for theme persistence

---

## 🎯 Color Palette

### Dark Mode
```css
Background: #0a0e27
Cards: #151b3d
Accent: #c9a77c (Warm Brown)
Text: #e4e7eb
```

### Light Mode
```css
Background: #faf8f5
Cards: #ffffff
Accent: #a67c52 (Rich Brown)
Text: #2d2520
```

---

## 📂 Project Structure

```
personal-website/
├── index.html          # English version
├── index-ar.html       # Arabic version
├── style.css           # Main stylesheet
├── style-ar.css        # Arabic RTL overrides
├── script.js           # English JavaScript
├── script-ar.js        # Arabic JavaScript
└── README.md           # Documentation
```

---

## 🚀 Quick Start

### View Live
Visit the live website: [rawanmismail.github.io/personal-website](https://rawanmismail.github.io/personal-website)

### Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/rawanmismail/personal-website.git
   cd personal-website
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your preferred browser
   # Or use a local server (recommended)
   
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve
   ```

3. **View the website**
   - Navigate to `http://localhost:8000` (or whichever port your server uses)
   - The website should load with full functionality

---

## 🎨 Customization

### Changing Colors
Edit the CSS custom properties in `style.css`:

```css
:root {
    --accent: #c9a77c;        /* Your brand color */
    --accent-hover: #b8935a;  /* Hover state */
    /* Modify other variables as needed */
}
```

### Adding New Sections
1. Add HTML markup in `index.html` and `index-ar.html`
2. Add navigation link in both files
3. Style the section in `style.css`
4. Add translations for Arabic version

### Modifying Content
- **Projects:** Update the project cards in the Projects section
- **Skills:** Edit skill items and data-level attributes (0-100)
- **Social Links:** Update href attributes with your actual profiles
- **Contact Info:** Replace placeholder email and phone number

---

## 🌐 Bilingual Support

The website includes complete English and Arabic versions:

- **English:** `index.html` + `script.js`
- **Arabic:** `index-ar.html` + `style-ar.css` + `script-ar.js`

The language toggle button switches between versions while preserving the selected theme.

### RTL Layout
Arabic version includes:
- Right-to-left text direction
- Mirrored layouts for timeline and cards
- Adjusted spacing and positioning
- Arabic typography optimization

---

## 📱 Browser Support

| Browser | Version |
|---------|---------|
| Chrome  | ✅ Latest |
| Firefox | ✅ Latest |
| Safari  | ✅ Latest |
| Edge    | ✅ Latest |
| Opera   | ✅ Latest |

**Note:** Custom cursor is disabled on mobile devices for better UX.

---

## ⚡ Performance

- **Lightweight:** No external frameworks or heavy dependencies
- **Fast Loading:** Minimal CSS and JavaScript
- **Optimized Images:** Icons loaded from CDN
- **Smooth Animations:** CSS transitions and transforms
- **Efficient Code:** Clean, organized, and well-commented

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Author

**Rawan Mohamed**

- 🌐 Website: [rawanmismail.github.io/personal-website](https://rawanmismail.github.io/personal-website)
- 💼 LinkedIn: [linkedin.com/in/rawan28-](https://linkedin.com/in/rawan28-)
- 🐙 GitHub: [github.com/rawanmismail](https://github.com/rawanmismail)
- 📧 Email: rawan.mohamedismail@yahoo.com

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## ⭐ Show Your Support

If you like this project, please give it a ⭐ on GitHub!

---

## 📝 Changelog

### v1.0.0 (2026)
- ✅ Initial release
- ✅ Bilingual support (EN/AR)
- ✅ Dark/Light theme toggle
- ✅ Scroll progress bar
- ✅ Animated skill bars
- ✅ Contact form with modal
- ✅ Fully responsive design
- ✅ Custom cursor (desktop)
- ✅ Smooth scroll animations

---

<p align="center">Made with ❤️ by Rawan Mohamed</p>
<p align="center">© 2026 All Rights Reserved</p>
