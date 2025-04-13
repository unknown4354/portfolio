# Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This portfolio showcases professional work, skills, and contact information with a clean, elegant design.

## Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Enhanced Dark/Light Theme**: Toggle between dark and light themes with persistent preference using localStorage
- **System Preference Detection**: Automatically detects and applies user's system color scheme preference
- **Modern UI**: Clean, professional design with smooth animations and gradient effects
- **Interactive Elements**: Hover effects, animations, and interactive components
- **Sections**:
  - Hero section with introduction
  - About section with skills and experience
  - Portfolio showcase
  - Contact form with validation
  - Footer with social links

## Technologies Used

- HTML5
- CSS3 (with CSS variables for comprehensive theming)
- JavaScript (for theme toggling and persistence)
- Font Awesome for icons
- Google Fonts (Outfit)

## Theme System

The website implements a comprehensive theming system with the following features:

- **CSS Variables**: All colors and design elements use CSS variables, making theme switching seamless
- **Theme Toggle**: Easy-to-use toggle in the top right corner of the page
- **LocalStorage Persistence**: User's theme preference is saved between sessions
- **System Preference Detection**: If no preference is stored, the site respects the user's system settings
- **Smooth Transitions**: All theme changes include smooth transitions for a polished experience

## Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/portfolio-website.git
   ```

2. Open the project folder:
   ```
   cd portfolio-website
   ```

3. Open `index.html` in your browser to view the website.

## Customization

### Personal Information

Edit the `index.html` file to update:
- Your name and title
- About section content
- Work experience and education
- Skills and percentages
- Portfolio projects
- Contact information

### Styling

The website uses CSS variables for easy customization. Edit the following in `styles.css`:

```css
:root {
  /* Light Theme Colors */
  --primary-color: #6d28d9;
  --primary-color-hover: #7c3aed;
  --primary-glow: rgba(109, 40, 217, 0.5);
  --secondary-color: #f9fafb;
  --text-color: #1f2937;
  --text-color-light: #6b7280;
  --background-color: #ffffff;
  --card-background: #ffffff;
  --border-color: #e5e7eb;
  --shadow-color: rgba(0, 0, 0, 0.1);
  --gradient-start: rgba(109, 40, 217, 0.15);
  --gradient-end: rgba(255, 255, 255, 0);
  
  /* Animation Speeds */
  --transition-fast: 0.2s;
  --transition-normal: 0.3s;
  --transition-slow: 0.5s;
  
  /* Spacing & other variables ... */
}

/* Dark Theme Colors */
[data-theme="dark"] {
  --primary-color: #8b5cf6;
  --primary-color-hover: #a78bfa;
  --primary-glow: rgba(139, 92, 246, 0.5);
  --secondary-color: #1f2937;
  --text-color: #f9fafb;
  --text-color-light: #d1d5db;
  --background-color: #111827;
  --card-background: #1f2937;
  --border-color: #374151;
  --shadow-color: rgba(0, 0, 0, 0.3);
  --gradient-start: rgba(139, 92, 246, 0.15);
  --gradient-end: rgba(17, 24, 39, 0);
}
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Font Awesome for the icons
- Google Fonts for the Outfit font family
- Placeholder images from placeholder.com 