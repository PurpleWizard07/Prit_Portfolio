# Personal Portfolio Website

A modern, responsive personal portfolio website designed for a final year B.Tech Computer Engineering student. This portfolio showcases skills, projects, education, and contact information in a visually appealing manner.

## Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI**: Clean and professional design with smooth animations
- **Interactive Elements**: Project filtering, smooth scrolling, and form validation
- **Sections**: Home, About, Skills, Projects, Education, and Contact
- **Customizable**: Easy to personalize with your own information

## How to Use

1. **Clone or Download**: Get a copy of this repository
2. **Customize Content**: Edit the HTML file to add your personal information
3. **Modify Styling**: Adjust colors and styles in the CSS file if desired
4. **Add Projects**: Update the projects section with your own work
5. **Deploy**: Host on platforms like GitHub Pages, Netlify, or Vercel

## Customization Guide

### Personal Information

Update the following sections in `index.html`:

- **Header**: Change the logo text
- **Hero Section**: Update your name, title, and introduction
- **About Section**: Add your personal bio and details
- **Skills Section**: Modify skills and proficiency levels
- **Projects Section**: Add your own projects with descriptions and links
- **Education Section**: Update with your educational background
- **Contact Section**: Add your contact information

### Styling

The main styling variables are defined at the top of `styles.css`:

```css
:root {
    --primary-color: #4a6cf7;
    --secondary-color: #6c757d;
    --dark-color: #0e1133;
    --light-color: #f8f9fa;
    --success-color: #28a745;
    --danger-color: #dc3545;
    --box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    --transition: all 0.3s ease;
}
```

Change these values to customize the color scheme of your portfolio.

### Adding Projects

To add a new project, copy the project card structure and update the content:

```html
<div class="project-card" data-category="your-category">
    <div class="project-img">
        <img src="path/to/your/image.jpg" alt="Project Title">
    </div>
    <div class="project-info">
        <h3>Project Title</h3>
        <p>Project description goes here...</p>
        <div class="project-tags">
            <span>Technology 1</span>
            <span>Technology 2</span>
            <span>Technology 3</span>
        </div>
        <div class="project-links">
            <a href="#" target="_blank" class="btn small-btn"><i class="fas fa-external-link-alt"></i> Live Demo</a>
            <a href="#" target="_blank" class="btn small-btn"><i class="fab fa-github"></i> Source Code</a>
        </div>
    </div>
</div>
```

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- Font Awesome Icons
- Google Fonts

## Future Enhancements

- Dark/Light theme toggle
- Blog section
- Project detail pages
- More animations and transitions
- Backend integration for contact form

## License

Feel free to use this template for your personal portfolio. Attribution is appreciated but not required.

---

Designed with ❤️ for showcasing your skills and projects to potential recruiters.