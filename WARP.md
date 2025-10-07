# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Project Overview

This is a static portfolio website for Ronak Yadav, an 18-year-old student at Scaler School of Technology. The portfolio showcases AI automation projects and coding skills.

## Commands

### Development Server
```bash
# Serve the site locally using Python's built-in server
python3 -m http.server 8000

# Or using Node.js (if available)
npx serve .

# Or using PHP (if available)
php -S localhost:8000
```

### File Operations
```bash
# View the site structure
ls -la

# Open index.html in default browser
open index.html  # macOS
xdg-open index.html  # Linux

# Edit files
code index.html script.js style.css  # VS Code
```

### Git Workflow
```bash
# Initialize and track files (if not already done)
git add index.html script.js style.css
git commit -m "Initial portfolio setup"

# Check status and stage changes
git status
git add .
git commit -m "Update portfolio content"
```

## Architecture

This is a single-page application (SPA) built with vanilla web technologies:

### Core Files
- **`index.html`** - Main HTML document with semantic structure for portfolio sections (hero, about, projects, contact)
- **`style.css`** - Complete CSS styling with responsive design, animations, and modern layout techniques
- **`script.js`** - JavaScript functionality for mobile navigation, smooth scrolling, form handling, and scroll animations

### Key Features
- **Responsive Design**: Mobile-first approach with breakpoints at 480px, 768px, and 1024px
- **Interactive Navigation**: Mobile hamburger menu with smooth transitions
- **Scroll Animations**: Intersection Observer API for element animations on scroll
- **Contact Form**: Client-side form validation with basic submission handling
- **Modern CSS**: Uses CSS Grid, Flexbox, custom properties, and backdrop filters

### Section Structure
1. **Header/Navigation**: Fixed header with responsive mobile menu
2. **Hero Section**: Introduction with call-to-action
3. **About Section**: Personal information and skills grid
4. **Projects Section**: Portfolio showcase with project cards
5. **Contact Section**: Contact information and form
6. **Footer**: Social links and copyright

### Styling Approach
- Uses Google Fonts (Poppins for headings, Roboto for body text)
- Font Awesome icons for social media and UI elements
- CSS custom animations with `@keyframes`
- Consistent color scheme based on blue (#2563eb) primary color
- Box shadows and transitions for interactive elements

### JavaScript Features
- Mobile menu toggle functionality
- Smooth scrolling navigation
- Form validation and submission handling
- Scroll-based header hide/show behavior
- Intersection Observer for scroll animations
- Event delegation and proper cleanup

## Development Notes

### Contact Information
- Email: ronakyadav1609@gmail.com
- Phone: +91 9991336228
- GitHub: https://github.com/roonakyadav
- LinkedIn: https://www.linkedin.com/in/ronak-yadav-330a0937a/
- Instagram: https://instagram.com/roonakyadav_

### Content Updates
When updating project information or personal details, maintain consistency across:
- Project descriptions and tech stacks
- Social media links in multiple locations (header, contact, footer)
- Personal information in the about section

### Image Placeholders
Current projects use placeholder images from via.placeholder.com. Replace with actual project screenshots when available.