# Imran - Technical Architect Portfolio

A modern, responsive, and professional personal portfolio website showcasing my role as a Technical Architect with 12+ years of experience in designing and delivering scalable, high-performance web and mobile solutions.

## 🌟 Features

### Design & User Experience
- **Modern & Clean Design**: Minimalist design inspired by tech/startup portfolios
- **Professional Color Palette**: Blues, whites, and subtle grays with gradient accents
- **Dark Mode Toggle**: Complete dark/light theme support with persistent preference
- **Smooth Animations**: Fade-ins, hover effects, and scroll animations using AOS library
- **Mobile-First Responsive**: Fully responsive layout that works on all devices
- **Smooth Scrolling**: Seamless navigation between sections

### Sections
- **Hero Section**: Introduction with call-to-action buttons
- **About Me**: Professional bio with your provided content
- **Core Strengths**: Highlighted skills in interactive cards
- **Skills & Technologies**: Visual badges for AWS, Azure, Node.js, React, Java, etc.
- **Featured Projects**: Project showcase with descriptions and links
- **Experience Timeline**: Career progression visualization
- **Contact Form**: Interactive contact form with validation

### Technical Features
- **SEO Optimized**: Meta tags, structured content, and semantic HTML
- **Performance Optimized**: Fast loading with optimized assets
- **Accessibility**: WCAG compliant with proper ARIA labels
- **Cross-Browser Compatible**: Works on all modern browsers
- **GitHub Pages Ready**: Optimized for static hosting

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation
1. Clone or download this repository
2. Open `index.html` in your web browser
3. The site is ready to use!

### For GitHub Pages Deployment
1. Push the code to your GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (usually `main` or `master`)
4. Your portfolio will be available at `https://yourusername.github.io`

## 🎨 Customization

### Personal Information
Update the following in `index.html`:

```html
<!-- Update title and meta tags -->
<title>Your Name - Technical Architect</title>
<meta name="author" content="Your Name">

<!-- Update hero section -->
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
<h2 class="hero-subtitle">Your Role</h2>

<!-- Update contact information -->
<a href="mailto:your.email@example.com">your.email@example.com</a>
<a href="https://github.com/yourusername">github.com/yourusername</a>
<a href="https://linkedin.com/in/yourprofile">linkedin.com/in/yourprofile</a>
```

### Colors & Theme
Modify the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;    /* Main brand color */
    --secondary-color: #64748b;  /* Secondary text color */
    --bg-primary: #ffffff;       /* Background color */
    /* ... other variables */
}
```

### Projects
Add your projects in the projects section:

```html
<div class="project-card" data-aos="fade-up" data-aos-delay="100">
    <div class="project-image">
        <!-- Add your project image here -->
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology</span>
        </div>
        <div class="project-links">
            <a href="#" class="project-link"><i class="fab fa-github"></i> Code</a>
            <a href="#" class="project-link"><i class="fas fa-external-link-alt"></i> Demo</a>
        </div>
    </div>
</div>
```

### Skills
Add or modify skills in the skills section:

```html
<div class="skill-category" data-aos="fade-up">
    <h3>Category Name</h3>
    <div class="skill-badges">
        <span class="skill-badge skillname">Skill Name</span>
    </div>
</div>
```

## 📁 File Structure

```
immran.github.io/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with CSS Grid, Flexbox, and custom properties
- **JavaScript (ES6+)**: Interactive functionality and animations
- **AOS Library**: Scroll animations
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family
- **GitHub Pages**: Hosting platform

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📈 Performance Features

- Optimized images and assets
- Minimal external dependencies
- Efficient CSS and JavaScript
- Fast loading times
- SEO optimized structure

## 🎯 SEO Features

- Semantic HTML structure
- Meta tags for description and keywords
- Open Graph tags (can be added)
- Structured data (can be added)
- Fast loading times
- Mobile-friendly design

## 📞 Contact Form

The contact form includes:
- Form validation
- Email format checking
- Success/error messages
- Responsive design

**Note**: The form currently shows an alert message. To make it functional, you'll need to:
1. Set up a backend service (Netlify Forms, Formspree, etc.)
2. Update the form action and method
3. Handle form submission on the server side

## 🌙 Dark Mode

The portfolio includes a complete dark mode implementation:
- Toggle button in the navigation
- Persistent preference storage
- Smooth transitions between themes
- Optimized colors for both themes

## 🚀 Deployment Options

### GitHub Pages (Recommended)
1. Push to GitHub repository
2. Enable GitHub Pages in repository settings
3. Site will be available at `https://username.github.io/repository-name`

### Netlify
1. Connect your GitHub repository
2. Deploy automatically on push
3. Custom domain support available

### Vercel
1. Import your GitHub repository
2. Automatic deployments
3. Excellent performance

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- [AOS Library](https://michalsnik.github.io/aos/) for scroll animations
- [Font Awesome](https://fontawesome.com/) for icons
- [Google Fonts](https://fonts.google.com/) for typography
- [GitHub Pages](https://pages.github.com/) for hosting

---

**Built with ❤️ for showcasing technical expertise and professional experience**

*Last updated: December 2024*
