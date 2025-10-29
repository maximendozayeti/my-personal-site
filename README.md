# Personal Portfolio Website

A modern, responsive personal portfolio website for Maximiliano Mendoza González, showcasing professional experience, skills, and contact information.

## 📋 Overview

This is a single-page portfolio website built with HTML5, CSS3, and Bootstrap 5.3.8. The site features a clean, professional design with dark/light theme support and responsive layout that works across all devices.

## 🚀 Features

- **Responsive Design**: Mobile-first approach with Bootstrap grid system
- **Dark/Light Theme**: Toggle between themes with automatic system preference detection
- **Professional Layout**: Clean, modern design showcasing work experience
- **Interactive Elements**: Hover effects and smooth transitions
- **Contact Integration**: Direct links to LinkedIn and email contact
- **Company Showcase**: Professional experience with Latam Airlines, Deel, and LVK

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and modern web standards
- **CSS3**: Custom styling with CSS variables and transitions
- **Bootstrap 5.3.8**: Responsive framework and components
- **JavaScript**: Theme switching functionality
- **SVG Icons**: Scalable vector graphics for icons

## 📁 File Structure

```
My Personal Site/
├── index.html          # Main HTML file
├── style.css           # Custom CSS styles
├── foto-perfil.jpg     # Profile picture
├── Deel logo.png       # Deel company logo
├── Latam isotype.jpg   # Latam Airlines logo
├── LVK logo.jpg        # LVK company logo
└── README.md           # This documentation file
```

## 🎨 Design Features

### Theme System
- **Light Theme**: Clean, bright interface with dark text
- **Dark Theme**: Modern dark interface with light text
- **Auto Theme**: Automatically matches system preference
- **Theme Toggle**: Fixed position toggle button in bottom-right corner

### Visual Elements
- **Profile Image**: Circular profile photo with shadow effect
- **Company Logos**: Circular company logos for professional experience
- **Feature Icons**: SVG icons for skills and capabilities
- **Hover Effects**: Smooth button animations and transitions
- **Responsive Images**: Optimized images that scale across devices

## 📱 Responsive Breakpoints

The site uses Bootstrap's responsive breakpoints:
- **Mobile**: < 576px
- **Tablet**: 576px - 768px
- **Desktop**: 768px - 992px
- **Large Desktop**: 992px - 1200px
- **Extra Large**: > 1200px

## 🎯 Sections

### 1. Hero Section
- Professional introduction
- LinkedIn profile link
- Profile image
- Call-to-action button

### 2. Work Experience
- **Latam Airlines**: Passenger care services and airport operations
- **Deel**: Customer review management and support
- **LVK**: Strategic client management and account support

### 3. About Me & Skills
- Client-centered collaboration approach
- Multilingual support capabilities
- Systems insight and process optimization
- Proactive problem-solving
- Team-oriented outcomes

### 4. Contact Information
- Email contact button
- Professional summary
- Skills showcase with icons

### 5. Footer
- Newsletter subscription
- Social media links
- Copyright information

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No server required - runs as static files

### Installation
1. Clone or download the repository
2. Open `index.html` in your web browser
3. The site will load with all features functional

### Local Development
1. Ensure all files are in the same directory
2. Open `index.html` in your preferred browser
3. Make changes to HTML or CSS files
4. Refresh browser to see changes

## 🎨 Customization

### Colors and Themes
The site uses CSS custom properties for easy theme customization:
```css
:root {
    --bs-body-bg: var(--bs-light);
    --bs-body-color: var(--bs-dark);
}
```

### Button Styles
Custom button styling with hover effects:
```css
.btn {
  border-radius: 50px;
  font-weight: 500;
  transition: 0.3s ease-in-out;
}
```

### Profile Image
Circular profile image with custom sizing:
```css
.overflow-hidden img {
  border-radius: 50%;
  width: 300px;
}
```

## 📧 Contact Information

- **Email**: maxi.mendoza.gonz@icloud.com
- **LinkedIn**: [Maximiliano Mendoza González](https://www.linkedin.com/in/maximiliano-mendoza-gonzalez-20b80992/)

## 🔗 External Links

- **Latam Airlines**: https://www.latamairlines.com/ar/es
- **Deel**: https://www.deel.com/
- **LVK**: https://lvk.com/

## 📄 License

© 2025 Maxi Mendoza, Inc. All rights reserved.

## 🚀 Future Enhancements

Potential improvements for the portfolio:
- Add a projects/portfolio section
- Implement a contact form with backend processing
- Add animations and micro-interactions
- Include a blog section
- Add testimonials or recommendations
- Implement analytics tracking
- Add a resume download feature

## 🐛 Known Issues

- Newsletter subscription form is not functional (frontend only)
- Social media links point to generic pages
- Footer navigation links are placeholder links

## 📝 Notes

- The site is optimized for performance with CDN-hosted Bootstrap
- All images are optimized for web use
- The design follows modern web accessibility guidelines
- Cross-browser compatibility is maintained through Bootstrap

---

**Last Updated**: January 2025
**Version**: 1.0.0
