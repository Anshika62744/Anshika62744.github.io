# Academic Portfolio Website

A modern, responsive portfolio website for applied physics researchers, specifically designed for PhD students specializing in Solar Radio Physics at NJIT.

## Features

- 📱 **Fully Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- 🎨 **NJIT Theme Colors** - Professional branding with university colors
- 🔍 **SEO Optimized** - Meta tags, structured data, and semantic HTML
- ⚡ **Fast Performance** - Optimized images, efficient CSS, and minimal JavaScript
- 📚 **Academic Focus** - Sections for research, publications, teaching, and blog posts
- 🔗 **Academic Integrations** - Links to Google Scholar, ORCID, ResearchGate, GitHub
- 🌟 **Modern UI/UX** - Clean design with smooth animations and interactions

## Sections

1. **Hero/Home** - Professional introduction with photo and social links
2. **About** - Educational background, research focus, and technical skills
3. **Research** - Current projects and research interests
4. **Publications** - Filterable list of papers with citation links
5. **Teaching** - Teaching experience and philosophy
6. **Blog** - Tutorials and educational content
7. **Contact** - Contact information and form

## Technical Stack

- **HTML5** - Semantic markup with accessibility features
- **CSS3** - Modern CSS with custom properties and Grid/Flexbox
- **Vanilla JavaScript** - No dependencies, lightweight and fast
- **Font Awesome** - Professional icons
- **Google Fonts** - Inter font family for readability

## NJIT Theme Colors

- **Primary Red**: `#CE1141` (NJIT Red)
- **Secondary Blue**: `#003366` (NJIT Blue)
- **Dark Blue**: `#001122` (NJIT Dark Blue)

## Setup Instructions

1. **Clone or Download** this repository
2. **Replace Placeholder Content**:
   - Update `[Your Name]` throughout the files
   - Add your actual profile photo as `images/profile.jpg`
   - Update contact information and social media links
   - Replace placeholder publications with your actual work
   - Add your research project images

3. **Customize Content**:
   - Education details in the About section
   - Research projects and interests
   - Teaching experience
   - Blog posts and tutorials

4. **GitHub Pages Deployment**:
   - Push to a GitHub repository
   - Enable GitHub Pages in repository settings
   - Your site will be available at `https://yourusername.github.io/repository-name`

## File Structure

```
├── index.html              # Main homepage
├── css/
│   └── styles.css         # All styling with NJIT theme
├── js/
│   └── main.js           # Interactive functionality
├── images/               # Profile photos and project images
├── blog/                 # Blog posts and tutorials
├── README.md            # This file
└── .github/
    └── copilot-instructions.md
```

## Customization Guide

### Adding Publications

1. Find the publications section in `index.html`
2. Copy the `.publication-item` structure
3. Update with your publication details
4. Add appropriate filter classes (`journal`, `conference`, `preprint`)

### Adding Blog Posts

1. Create new HTML files in the `blog/` directory
2. Follow the same structure as the main site
3. Update the blog section links in `index.html`
4. Add new blog post cards to the blog grid

### Updating Colors

All colors are defined as CSS custom properties in `styles.css`:
```css
:root {
    --njit-red: #CE1141;
    --njit-blue: #003366;
    /* Modify these to change the theme */
}
```

## SEO Features

- **Meta Tags** - Title, description, keywords for search engines
- **Open Graph** - Social media sharing optimization
- **Structured Data** - JSON-LD markup for rich snippets
- **Semantic HTML** - Proper heading hierarchy and landmarks
- **Alt Text** - Descriptive alt text for all images
- **Clean URLs** - SEO-friendly URL structure

## Performance Optimizations

- **Lazy Loading** - Images load only when needed
- **Optimized CSS** - Efficient selectors and minimal reflow
- **Compressed Assets** - Minified code for production
- **Caching** - Proper cache headers for static assets

## Accessibility Features

- **Keyboard Navigation** - Full keyboard accessibility
- **Screen Reader Support** - Proper ARIA labels and semantics
- **Color Contrast** - WCAG AA compliant color ratios
- **Focus Indicators** - Clear focus states for interactive elements
- **Responsive Text** - Scalable fonts and layout

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## Contributing

Feel free to submit issues, feature requests, or improvements. This template is designed to be easily customizable for any academic researcher.

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

Created for Applied Physics PhD students at NJIT. For questions or support, please open an issue on GitHub.

---

**Note**: Remember to replace all placeholder content with your actual information before deploying to GitHub Pages.
