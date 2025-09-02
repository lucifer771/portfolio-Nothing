<div align="center">

# 💼 HariNath's Portfolio Website

</div>

A modern, responsive portfolio website for HariNath, showcasing full-stack development skills, projects, and journey. Built with HTML, CSS, JavaScript, Bootstrap, GSAP, Tailwind CSS, and features animated particle backgrounds.

---

## 🚀 Features

### ✨ **Core Features**

- Responsive design for all devices
- Animated transparent navigation bar with interactive menu
- Hero section with animated name and particle background
- Custom cursor for enhanced UI
- Animated download button for resume
- Smooth scroll and scroll progress indicator
- Journey timeline with animated cards
- Tech stack section with categorized skills
- Projects and upcoming projects with interactive cards
- Contact form with validation and feedback
- "Back to Top" button with animation

### 📧 **Contact Form**

- Formspree integration for message delivery
- Real-time validation and gibberish detection
- Success/error feedback with animated messages
- Accessible and styled input fields

### ⚡ **Performance Optimizations**

- Lazy loading for images
- Reduced motion support for accessibility
- Optimized animations using GSAP
- Service Worker for offline support (PWA)
- Font and critical CSS optimizations

### 🐙 **GitHub Integration**

- Live GitHub stats (repos, stars, followers, commits)
- Recent activity feed from GitHub API
- Most used programming languages display
- Fallback data for offline viewing

### 🎨 **Enhanced UI/UX**

- Dark theme with accent colors
- Particle backgrounds for hero and projects
- Animated social icons and buttons
- Print-friendly styles
- Accessibility improvements

---

## 🛠️ Tech Stack

- **HTML5** – Semantic markup
- **CSS3** – Custom styles, Bootstrap 5, Tailwind CSS
- **JavaScript** – Interactivity, animations, API integration
- **GSAP** – Advanced animations and scroll triggers
- **Particles.js** – Particle backgrounds
- **Formspree** – Contact form backend
- **GitHub API** – Live activity and stats
- **Service Worker** – Offline/PWA support

---

## 📱 PWA Features

- **Installable** as a native app
- **Offline Support** via Service Worker
- **Fast Loading** with caching
- **App-like Experience** in full-screen mode

---

## 📸 Live Preview

👉 [Live Demo](https://harinath-portfolio-demo-link.com) <!-- Replace with your actual live link -->

## 📸 Screenshot

![Portfolio Website](./assets/portfolio-ss.png)

---

## 🚀 Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/lucifer771/Portfolio.git
   cd Portfolio
   ```

2. **Open in browser**

   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js
   npx serve .

   # Or simply open index.html in your browser
   ```

3. **Customize**
   - Update personal info in `index.html`
   - Change colors/styles in `styles.css`
   - Add your own projects and content
   - Update GitHub username in `script.js`

---

## 📁 Project Structure

```
Portfolio/
├── index.html          # Main HTML file
├── styles.css          # Custom styles and animations
├── script.js           # JavaScript functionality
├── manifest.json       # PWA manifest
├── sw.js               # Service Worker
├── assets/             # Images and media files
└── README.md           # Project documentation
```

---

## 🔧 Configuration

### Contact Form

Update the Formspree endpoint in `script.js`:

```javascript
const response = await fetch('https://formspree.io/f/YOUR_FORM_ID', {
```

### GitHub Integration

Update your GitHub username in `script.js`:

```javascript
const username = "YOUR_GITHUB_USERNAME";
```

---

## 📈 Performance

- **Lighthouse Score**: 95+ (Performance, Accessibility, Best Practices, SEO)
- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Cumulative Layout Shift**: < 0.1

---

## 🤝 Contributing

Contributions are welcome! Please submit a Pull Request.

---

## 📄 License

This project is open source under the [MIT License](LICENSE).

---

## 📞 Contact

- **Email**: harinath4456@gmail.com
-
