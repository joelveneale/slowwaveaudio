# Slow Wave Audio Solutions Website

A modern, minimalist website for Slow Wave Audio Solutions Ltd - showcasing sound design work, audio applications, and music projects.

## Features

- Responsive design that works on all devices
- Clean black and green color scheme matching your brand
- Smooth scrolling navigation
- Project showcase sections
- Mobile-friendly hamburger menu
- Animated elements on scroll
- Easy to customize and maintain

## File Structure

```
/
├── index.html              # Main landing page
├── styles.css              # All styling
├── script.js               # Interactive features
├── project-sound-1.html    # Example sound design project page
├── project-app-1.html      # Example audio app project page
├── sw_byline-green-*.png   # Your logo
└── README.md               # This file
```

## Setup Instructions

1. **Upload to GitHub:**
   - Create a new repository on GitHub
   - Upload all files to the repository
   - Go to Settings → Pages
   - Select main branch as source
   - Your site will be live at: `https://yourusername.github.io/repository-name`

2. **Customize Content:**
   - Update the email in `index.html` (search for "hello@slowwaveaudio.com")
   - Add your actual social media links (search for "twitter.com", "instagram.com", etc.)
   - Update Bandcamp and FXhash URLs with your profile links

3. **Add Projects:**
   - Duplicate `project-sound-1.html` or `project-app-1.html` to create new project pages
   - Name them `project-sound-2.html`, `project-sound-3.html`, etc.
   - Update the content, titles, and descriptions
   - Add links to these pages in `index.html` in the project cards

4. **Add Images:**
   - Replace the placeholder divs with actual images of your work
   - Add images in the same folder as your HTML files
   - Update the image paths in the HTML

## Customization Guide

### Colors
All colors are defined in `styles.css` at the top using CSS variables:
```css
:root {
    --green: #739072;    /* Your brand green */
    --black: #0a0a0a;    /* Background */
    --dark-gray: #1a1a1a;
    --mid-gray: #2a2a2a;
}
```

### Logo
The logo is in the hero section. To update it:
1. Replace the PNG file
2. Update the filename in `index.html` if needed

### Social Media Icons
Current social links include:
- Twitter/X
- Instagram
- LinkedIn
- SoundCloud

To add more or change them, find the social-links section in `index.html` and add/modify SVG icons.

### Contact Email
Search for "hello@slowwaveaudio.com" in `index.html` and replace with your actual email.

### Adding More Project Pages
1. Copy `project-sound-1.html`
2. Rename it (e.g., `project-sound-4.html`)
3. Update the content inside
4. Link to it from `index.html` in the appropriate project card

## Hosting Options

### GitHub Pages (Recommended - Free)
1. Push code to GitHub repository
2. Enable GitHub Pages in repository settings
3. Your site will be live at `username.github.io/repo-name`

### Other Options
- **Netlify**: Drag and drop folder for instant deployment
- **Vercel**: Connect to GitHub for automatic deployments
- **Custom Domain**: Point your domain to any of these services

## Browser Support

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## Mobile Responsive

The site is fully responsive and includes:
- Mobile navigation menu
- Flexible grid layouts
- Touch-friendly interface
- Optimized for phones, tablets, and desktops

## Need Help?

For questions about:
- Customizing the design
- Adding new features
- Technical issues

Feel free to reach out!

## License

© 2026 Slow Wave Audio Solutions Ltd. All rights reserved.
