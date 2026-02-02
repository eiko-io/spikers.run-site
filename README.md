# SPIKERS - Static Website

A simple, modern, and responsive static website for the SPIKERS project.

## Features

- 📱 **Responsive Design** - Works perfectly on all devices (mobile, tablet, desktop)
- ✨ **Modern UI** - Clean and professional appearance
- ⚡ **Fast Loading** - Pure HTML, CSS, and JavaScript (no frameworks)
- 🎨 **Customizable** - Easy to modify colors, content, and layout
- 🔗 **Smooth Navigation** - Smooth scrolling and interactive elements

## Project Structure

```
spikers-site/
├── index.html      # Main HTML file with page structure
├── styles.css      # All styling and responsive design
├── script.js       # Interactive features and smooth scrolling
└── README.md       # This file
```

## Getting Started

1. Open the project in your browser or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js (http-server)
   npx http-server
   ```

2. Navigate to `http://localhost:8000` in your browser

## Sections

- **Home** - Hero section with call-to-action
- **About** - Information about SPIKERS with key values
- **Features** - Showcase of project features
- **Contact** - Contact section with email link
- **Footer** - Social links and copyright

## Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #3498db;      /* Main brand color */
    --secondary-color: #2c3e50;    /* Dark background */
    --accent-color: #e74c3c;       /* Accent color */
    /* ... more variables ... */
}
```

### Content
Simply edit the HTML in `index.html` to update:
- Company name and descriptions
- Feature list
- Contact information
- Social media links

### Typography
Modify font sizes, families, and weights in `styles.css`

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

© 2026 SPIKERS. All rights reserved.

## Notes

- This is a static website - no backend required
- All content is in `index.html`
- Styling is in `styles.css`
- JavaScript interactions are in `script.js`

Feel free to customize and expand this template for your SPIKERS project!
