# Portfolio Site

A modern, responsive portfolio website to showcase your projects, skills, and professional experience.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Customization Guide](#customization-guide)
- [Directory Structure](#directory-structure)
- [Deployment](#deployment)
- [Technologies Used](#technologies-used)

## Overview

This is a personal portfolio website built with modern web technologies. It's designed to be fast, accessible, and easy to customize. The site is hosted on GitHub Pages and automatically deployed from this repository.

## Features

- 📱 **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- ⚡ **Fast Performance** - Optimized for quick loading times
- 🎨 **Modern Aesthetics** - Clean and professional design
- 🔧 **Easy to Customize** - Simple configuration options
- 📊 **Project Showcase** - Display your best work
- 🌙 **Dark Mode Support** - Optional dark theme
- ♿ **Accessible** - Built with accessibility standards in mind

## Getting Started

### Prerequisites

- Git
- Node.js (v14 or higher) - if using build tools
- A text editor (VS Code, Sublime Text, etc.)

### Installation

1. Clone this repository:
```bash
git clone https://github.com/gabriellewp/gabriellewp.github.io.git
cd gabriellewp.github.io
```

2. Install dependencies (if applicable):
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open your browser and navigate to `http://localhost:3000` (or your configured port)

## Customization Guide

### 1. **Personal Information**

Update your personal details in the main content files:

- **Name & Title**: Edit the header section in `index.html` or your main component
- **Bio/About**: Update the about section with your background and professional summary
- **Contact Information**: Add your email, phone, and social media links

### 2. **Colors & Styling**

Customize the color scheme by editing the CSS variables:

- Look for `:root` CSS variables or theme configuration files
- Common variables to customize:
  - Primary color
  - Secondary color
  - Background color
  - Text color
  - Accent colors

Example (in `styles.css` or similar):
```css
:root {
  --primary-color: #007bff;
  --secondary-color: #6c757d;
  --background-color: #ffffff;
  --text-color: #333333;
}
```

### 3. **Projects Section**

Add or update your projects:

- Edit the projects data file (typically `data/projects.json` or similar)
- Add project information:
  ```json
  {
    "title": "Project Name",
    "description": "Brief description of your project",
    "technologies": ["JavaScript", "React", "CSS"],
    "link": "https://github.com/yourname/project",
    "liveDemo": "https://project-demo.com",
    "image": "path/to/image.jpg"
  }
  ```

### 4. **Skills & Experience**

Update your skills section:

- List your technical skills, programming languages, and frameworks
- Organize by category if desired
- Include proficiency levels if applicable

### 5. **Social Links**

Add your social media and professional links:

- GitHub profile URL
- LinkedIn profile URL
- Twitter/X handle
- Email address
- Other relevant links

### 6. **Images & Assets**

- Place images in an `assets/` or `images/` directory
- Use optimized image formats (WebP, JPEG, PNG)
- Consider using a CDN for better performance

### 7. **Typography**

Customize fonts:

- Update font imports in CSS
- Common choices: Google Fonts, system fonts
- Example:
```css
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

h1, h2, h3 {
  font-family: 'Poppins', sans-serif;
}
```

### 8. **Navigation Menu**

Update the main navigation:

- Add or remove menu items
- Update links to point to your sections
- Customize menu styling and layout

## Directory Structure

```
gabriellewp.github.io/
├── index.html              # Main HTML file
├── assets/                 # Images and media files
│   ├── images/
│   ├── icons/
│   └── videos/
├── css/                    # Stylesheets
│   ├── styles.css
│   ├── responsive.css
│   └── variables.css
├── js/                     # JavaScript files
│   ├── main.js
│   ├── projects.js
│   └── interactions.js
├── data/                   # Data files
│   ├── projects.json
│   ├── skills.json
│   └── experience.json
├── README.md               # This file
└── .gitignore              # Git ignore rules
```

## Deployment

This site is automatically deployed to GitHub Pages when changes are pushed to the main branch.

### Manual Deployment

1. Commit and push your changes:
```bash
git add .
git commit -m "Update portfolio content"
git push origin main
```

2. GitHub Pages will automatically build and deploy your site
3. Visit `https://gabriellewp.github.io` to see your changes (may take a few minutes to propagate)

### Domain Configuration

To use a custom domain:

1. Add a `CNAME` file in the root directory with your domain name
2. Configure your domain's DNS settings to point to GitHub Pages
3. Verify the domain in your repository settings

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Styling and responsive design
- **JavaScript** - Interactivity and dynamic content
- **GitHub Pages** - Hosting and deployment

Optional frameworks/libraries:
- React, Vue, or other JavaScript frameworks
- Build tools (Webpack, Vite, etc.)
- CSS preprocessors (SASS, LESS)

## Best Practices

### Content

- Keep your bio concise and compelling
- Highlight your best 3-5 projects
- Use clear, professional language
- Include relevant keywords for SEO

### Performance

- Optimize images before uploading
- Minify CSS and JavaScript
- Use lazy loading for images
- Keep bundle sizes small

### Maintenance

- Update projects regularly
- Keep your content fresh and current
- Fix broken links periodically
- Test on multiple devices and browsers

## SEO Optimization

- Add proper meta tags in the `<head>` section
- Use descriptive alt text for images
- Structure content with semantic HTML
- Create an XML sitemap
- Add a robots.txt file

## Accessibility

- Use semantic HTML elements
- Provide alt text for images
- Ensure sufficient color contrast
- Make navigation keyboard accessible
- Test with screen readers

## Troubleshooting

### Site not updating after push?
- Wait 5-10 minutes for GitHub Pages to rebuild
- Clear your browser cache (Ctrl+F5 or Cmd+Shift+R)
- Check the GitHub Pages settings in your repository

### Images not showing?
- Verify the image paths are correct
- Check that images are in the correct folder
- Ensure image file names match the paths in your HTML

### Styling looks off?
- Check for CSS file path issues
- Clear browser cache
- Verify all CSS files are properly linked in HTML

## License

This portfolio is open source and available under the MIT License.

## Support

For issues, questions, or suggestions:
- Create an issue in the GitHub repository
- Contact through the links in your portfolio

---

**Happy coding! 🚀**

Last updated: 2025-12-23
