# Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This portfolio showcases your personal information, education, skills, and projects in a professional and visually appealing way.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and mobile navigation
- **Sections Included**:
  - Hero section with introduction
  - About section with skills and statistics
  - Education timeline
  - Projects showcase
  - Contact information
  - Social media links

## Getting Started

### Prerequisites

- A modern web browser
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation

1. Download or clone this repository
2. Open `index.html` in your web browser
3. The portfolio is ready to use!

## Customization Guide

### 1. Personal Information

Edit the following sections in `index.html`:

#### Hero Section
```html
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
<p class="hero-subtitle">Web Developer & Designer</p>
<p class="hero-description">
    Your personal description here...
</p>
```

#### About Section
```html
<p>
    Your about me text here...
</p>
```

#### Skills
```html
<div class="skill-tags">
    <span class="skill-tag">Your Skill 1</span>
    <span class="skill-tag">Your Skill 2</span>
    <!-- Add more skills as needed -->
</div>
```

#### Statistics
```html
<div class="stat-item">
    <h3>Your Number</h3>
    <p>Your Stat Description</p>
</div>
```

### 2. Education

Update the education timeline in the education section:

```html
<div class="timeline-item">
    <div class="timeline-content">
        <div class="timeline-header">
            <h3>Your Degree</h3>
            <span class="timeline-date">Year - Year</span>
        </div>
        <p class="timeline-institution">Institution Name</p>
        <p class="timeline-description">
            Your education description...
        </p>
    </div>
</div>
```

### 3. Projects

Replace the sample projects with your own:

```html
<div class="project-card">
    <div class="project-image">
        <div class="project-placeholder">
            <i class="fas fa-laptop-code"></i>
        </div>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Your project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-github-link" class="project-link"><i class="fab fa-github"></i> Code</a>
            <a href="your-live-link" class="project-link"><i class="fas fa-external-link-alt"></i> Live</a>
        </div>
    </div>
</div>
```

### 4. Contact Information

Update your contact details:

```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <div>
        <h3>Email</h3>
        <p>your.email@example.com</p>
    </div>
</div>
```

### 5. Social Media Links

Update the social media links in the contact section:

```html
<div class="social-links">
    <a href="your-github-url" class="social-link"><i class="fab fa-github"></i></a>
    <a href="your-linkedin-url" class="social-link"><i class="fab fa-linkedin"></i></a>
    <a href="your-twitter-url" class="social-link"><i class="fab fa-twitter"></i></a>
    <a href="your-instagram-url" class="social-link"><i class="fab fa-instagram"></i></a>
</div>
```

### 6. Profile Picture

To add your profile picture:

1. Replace the placeholder in the hero section:
```html
<div class="hero-image">
    <img src="path/to/your/image.jpg" alt="Your Name" class="profile-image">
</div>
```

2. Add CSS for the profile image in `styles.css`:
```css
.profile-image {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid rgba(255, 255, 255, 0.2);
}
```

### 7. Project Images

To add images for your projects:

1. Replace the placeholder in project cards:
```html
<div class="project-image">
    <img src="path/to/project-image.jpg" alt="Project Name" class="project-img">
</div>
```

2. Add CSS for project images:
```css
.project-img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
```

## Color Scheme

The current color scheme uses:
- Primary Blue: `#2563eb`
- Secondary Yellow: `#fbbf24`
- Dark Gray: `#1f2937`
- Light Gray: `#f8fafc`

To change colors, update the CSS variables in `styles.css`.

## Fonts

The portfolio uses the Inter font family. To change fonts:

1. Update the Google Fonts link in `index.html`
2. Change the font-family in the CSS body selector

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select your branch and save

### Netlify
1. Drag and drop your project folder to Netlify
2. Your site will be live instantly

### Vercel
1. Connect your GitHub repository to Vercel
2. Deploy automatically

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Contributing

Feel free to fork this project and customize it for your needs. If you make improvements, consider sharing them back!

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing your portfolio, feel free to:
- Check the comments in the code
- Refer to this README
- Look up HTML, CSS, and JavaScript documentation

## Updates and Maintenance

- Keep your projects section updated with your latest work
- Regularly update your skills and experience
- Add new achievements to your education timeline
- Keep contact information current

---

**Happy coding! 🚀** 