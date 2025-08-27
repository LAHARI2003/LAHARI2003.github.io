# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Perfect for showcasing your work and skills on GitHub Pages.

## Features

- 🎨 **Modern Design** - Clean, professional layout with smooth animations
- 📱 **Responsive** - Works perfectly on all devices (desktop, tablet, mobile)
- ⚡ **Fast Loading** - Optimized for performance
- 🎯 **SEO Friendly** - Proper meta tags and semantic HTML
- 📧 **Contact Form** - Ready-to-use contact form with validation
- 🌟 **Smooth Animations** - Engaging scroll animations and hover effects
- 🎪 **Interactive Elements** - Mobile navigation, smooth scrolling, and more

## Sections

1. **Hero Section** - Eye-catching introduction with call-to-action buttons
2. **About** - Personal information and statistics
3. **Skills** - Technical skills organized by category
4. **Projects** - Featured projects with links to code and live demos
5. **Contact** - Contact form and social media links

## Quick Start

### 1. Customize Your Content

Edit the following files to personalize your portfolio:

#### `index.html`
- Replace "Your Name" with your actual name
- Update the hero subtitle and description
- Modify the about section content
- Add your real projects to the projects section
- Update contact information and social media links

#### `styles.css`
- Change the color scheme by modifying CSS variables
- Adjust fonts, spacing, and layout as needed
- Customize animations and effects

### 2. Deploy to GitHub Pages

1. **Create a new repository** on GitHub
   - Name it: `yourusername.github.io` (replace `yourusername` with your actual GitHub username)

2. **Upload your files** to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll down to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch
   - Click "Save"

4. **Your portfolio will be live** at: `https://yourusername.github.io`

## Customization Guide

### Changing Colors

The main color scheme is defined in `styles.css`. Look for these color values:

```css
/* Primary colors */
--primary-color: #2563eb;
--secondary-color: #7c3aed;
--accent-color: #fbbf24;

/* Background colors */
--bg-light: #f8fafc;
--bg-dark: #1f2937;
```

### Adding Your Projects

In the projects section of `index.html`, replace the example projects with your own:

```html
<div class="project-card">
    <div class="project-image">
        <!-- Add your project screenshot or icon -->
        <i class="fas fa-laptop-code"></i>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Description of your project</p>
        <div class="project-tech">
            <span>React</span>
            <span>Node.js</span>
            <span>MongoDB</span>
        </div>
        <div class="project-links">
            <a href="https://github.com/yourusername/project" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
            <a href="https://your-project-demo.com" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live
            </a>
        </div>
    </div>
</div>
```

### Updating Skills

Modify the skills section to match your expertise:

```html
<div class="skill-item">
    <i class="fab fa-react"></i>
    <span>React</span>
</div>
```

### Contact Information

Update the contact section with your real information:

```html
<div class="contact-method">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
<div class="contact-method">
    <i class="fab fa-linkedin"></i>
    <span>linkedin.com/in/yourprofile</span>
</div>
<div class="contact-method">
    <i class="fab fa-github"></i>
    <span>github.com/yourusername</span>
</div>
```

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Features

- Optimized images and assets
- Minimal JavaScript for fast loading
- CSS animations for smooth interactions
- Responsive design for all screen sizes
- SEO optimized structure

## Contributing

Feel free to fork this project and customize it for your own portfolio. If you make improvements, consider sharing them with the community!

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing your portfolio or have questions about deployment, feel free to:

1. Check the GitHub Pages documentation
2. Review the HTML/CSS comments in the code
3. Open an issue in this repository

## Credits

- Fonts: [Inter](https://fonts.google.com/specimen/Inter) from Google Fonts
- Icons: [Font Awesome](https://fontawesome.com/)
- Design inspiration from modern portfolio trends

---

**Happy coding! 🚀**
