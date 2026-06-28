# Professional Portfolio Website

A modern, professional portfolio website designed for computer science students seeking internships and entry-level software developer roles.

## Features

- **Responsive Design**: Works on mobile, tablet, and desktop
- **Dark/Light Mode**: Toggle between themes with system preference detection
- **Modern UI**: Clean, professional design with smooth animations
- **SEO Friendly**: Semantic HTML structure
- **Accessible**: Proper ARIA labels and keyboard navigation
- **Optimized**: Fast loading with lazy loading for images

## Sections

1. Hero Section - Introduction with resume download
2. About Me - Personal introduction and strengths
3. Education - Academic background
4. Technical Skills - Categorized skills
5. Projects - Showcase of work with live demos and source code
6. Experience/Internships - Work experience
7. Certifications - Professional certifications
8. Achievements & Activities - Awards and extracurriculars
9. GitHub & Coding Profiles - Links to coding profiles
10. Contact - Contact form and information
11. Footer - Social media links

## Customization

### Personal Information
Edit the following in `index.html`:
- Replace `[Your Name]` in the header
- Update the introduction paragraph
- Add your actual resume path (currently points to the Google Drive folder: `https://drive.google.com/drive/folders/1w9vK-3h2i9fsIXYKzkbg5fmezQYecsym?usp=drive_link`)
- Update all placeholder text in sections
- Update contact information

### Images
Place your images in the `images/` folder:
- `profile.jpg` - Your profile picture
- `project1.jpg`, `project2.jpg`, `project3.jpg` - Project screenshots

### Colors
Modify the CSS variables in `css/style.css`:
- `--primary-color`: Main accent color (default: blue)
- `--secondary-color`: Secondary text color
- `--accent-color`: Accent color for highlights
- Adjust other variables as needed

### Social Media Links
Update the social media links in the footer and profiles section:
- GitHub
- LinkedIn
- Twitter
- Instagram
- Stack Overflow
- LeetCode

## Deployment

This is a static website that can be hosted on:
- GitHub Pages
- Netlify
- Vercel
- Any static web host

Simply upload the entire `portfolio` folder to your hosting provider.

## Development

To run locally:
1. Open `index.html` in your browser
2. No build process required
3. Changes are reflected immediately

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Accessibility Features

- Semantic HTML elements
- Proper color contrast
- Keyboard navigable
- ARIA labels where needed
- Responsive text sizing
- Focus indicators

## Performance Optimizations

- CSS minification ready
- Lazy loading for images
- Efficient CSS selectors
- Minimal DOM manipulation
- Optimized JavaScript

## Custom JavaScript Features

- Theme persistence (localStorage)
- Mobile menu toggle
- Smooth scrolling
- Active navigation highlighting
- Form validation
- Scroll reveal animations
- Lazy loading images
- Responsive header on scroll

## License

MIT License - Feel free to use and modify for your personal portfolio.