# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. Features a clean design, smooth animations, and is fully optimized for mobile devices.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **SEO Optimized**: Proper meta tags, semantic HTML, and structured data
- **Interactive Elements**: Smooth scrolling, hover effects, and form validation
- **Performance Optimized**: Fast loading times and optimized assets
- **Accessibility**: WCAG compliant with proper ARIA labels and keyboard navigation

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎨 Customization Guide

### 1. Personal Information

Update the following in `index.html`:

#### Basic Info
```html
<!-- Replace "Your Name" throughout the file -->
<title>Your Name | Professional Portfolio</title>
<meta name="author" content="Your Name">
<meta property="og:title" content="Your Name | Professional Portfolio">

<!-- Hero Section -->
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
<h2 class="hero-subtitle">Your Title Here</h2>
```

#### Contact Information
```html
<!-- Contact Section -->
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
<div class="contact-item">
    <i class="fas fa-phone"></i>
    <span>+1 (555) 123-4567</span>
</div>
<div class="contact-item">
    <i class="fas fa-map-marker-alt"></i>
    <span>Your City, Country</span>
</div>
```

#### Social Media Links
```html
<div class="social-links">
    <a href="https://github.com/yourusername" class="social-link">
        <i class="fab fa-github"></i>
    </a>
    <a href="https://linkedin.com/in/yourusername" class="social-link">
        <i class="fab fa-linkedin"></i>
    </a>
    <a href="https://twitter.com/yourusername" class="social-link">
        <i class="fab fa-twitter"></i>
    </a>
</div>
```

### 2. About Section

Update the about section with your personal story:

```html
<div class="about-text">
    <p>
        Your personal story and background here...
    </p>
    <p>
        More details about your journey and expertise...
    </p>
</div>
```

### 3. Skills Section

Modify the skills to match your expertise:

```html
<div class="skill-category">
    <h3>Frontend Development</h3>
    <div class="skill-items">
        <div class="skill-item">
            <i class="fab fa-html5"></i>
            <span>HTML5</span>
        </div>
        <!-- Add/remove skills as needed -->
    </div>
</div>
```

### 4. Experience Section

Update with your work experience:

```html
<div class="timeline-item">
    <div class="timeline-content">
        <div class="timeline-header">
            <h3>Your Job Title</h3>
            <span class="company">Company Name</span>
            <span class="period">2022 - Present</span>
        </div>
        <p>
            Your job description and achievements...
        </p>
        <div class="tech-stack">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
    </div>
</div>
```

### 5. Projects Section

Replace with your actual projects:

```html
<div class="project-card">
    <div class="project-image">
        <div class="image-placeholder">
            <i class="fas fa-project-icon"></i>
        </div>
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>
            Project description...
        </p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="https://github.com/yourusername/project" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
            <a href="https://project-demo.com" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
        </div>
    </div>
</div>
```

## 🎨 Styling Customization

### Colors

The main color scheme uses CSS custom properties. Update these in `styles.css`:

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #f093fb;
    --text-color: #2d3748;
    --text-light: #4a5568;
    --background-light: #f7fafc;
}
```

### Fonts

The website uses Inter font from Google Fonts. To change:

1. Update the Google Fonts link in `index.html`
2. Change the font-family in `styles.css`

```css
body {
    font-family: 'Your Font', sans-serif;
}
```

## 🚀 Deployment

### GitHub Pages (Recommended)

1. **Create a GitHub Repository**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/portfolio.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click "Settings" → "Pages"
   - Select "Deploy from a branch"
   - Choose "main" branch
   - Click "Save"

3. **Your site will be available at**: `https://yourusername.github.io/portfolio`

### Alternative Deployment Options

#### Netlify
1. Drag and drop your project folder to [Netlify](https://netlify.com)
2. Your site will be deployed instantly

#### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts

## 📱 Mobile Optimization

The website is fully responsive and includes:

- Mobile-first design approach
- Touch-friendly navigation
- Optimized images and assets
- Fast loading times
- Proper viewport settings

## 🔧 Performance Optimization

- Minified CSS and JavaScript (for production)
- Optimized images
- Lazy loading for better performance
- Efficient animations using CSS transforms
- Reduced layout shifts

## 📊 SEO Features

- Semantic HTML structure
- Meta tags for social sharing
- Open Graph tags
- Twitter Card support
- Proper heading hierarchy
- Alt text for images
- Structured data markup

## 🛠️ Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your needs. If you find any bugs or have suggestions, please open an issue.

## 📞 Support

If you need help customizing or deploying your portfolio:

1. Check the customization guide above
2. Review the code comments
3. Open an issue on GitHub

## 🎯 Next Steps

After customizing your portfolio:

1. **Add Real Projects**: Replace placeholder projects with your actual work
2. **Add Images**: Replace placeholder icons with real project screenshots
3. **Add Analytics**: Integrate Google Analytics or similar
4. **Add Blog**: Consider adding a blog section
5. **Add Resume**: Include a downloadable resume
6. **Add Testimonials**: Add client or colleague testimonials

## 🚀 Quick Start

1. Clone or download this repository
2. Open `index.html` in your browser to preview
3. Customize the content as described above
4. Deploy to GitHub Pages or your preferred hosting service

---

**Happy coding! 🎉**

Your portfolio is now ready to showcase your skills and impress potential employers or clients. 