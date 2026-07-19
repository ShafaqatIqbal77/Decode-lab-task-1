# Professional Portfolio Website

A modern, responsive static portfolio website built with pure HTML5 and CSS3. This project showcases professional web design skills with semantic markup, modern UI components, and responsive layouts.

## Features

- **Semantic HTML5**: Uses proper semantic tags (header, nav, main, section, article, footer)
- **Responsive Design**: Built with Flexbox and CSS Grid for optimal viewing on all devices
- **Modern UI**: Clean, professional design with attractive color scheme
- **Google Fonts**: Inter (body text) and Playfair Display (headings)
- **Hero Section**: Eye-catching hero with heading, description, CTA button, and image
- **About Section**: Company information with animated statistics
- **Services Section**: 3 service cards with custom SVG icons
- **Portfolio Gallery**: 6-item portfolio grid with hover effects
- **Contact Section**: Contact information and styled contact form
- **Footer**: Company info, quick links, and social media icons
- **No JavaScript**: Pure HTML/CSS implementation
- **Well-Commented Code**: Clean, organized, and documented code

## Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Styling, Flexbox, CSS Grid, animations, and responsive design
- **Google Fonts**: Typography
- **SVG Icons**: Scalable vector graphics for icons

## File Structure

```
.
├── index.html      # Main HTML file with all sections
├── styles.css      # Complete styling with responsive design
└── README.md       # Project documentation
```

## Sections

1. **Header**: Sticky navigation with logo and menu links
2. **Hero**: Introduction with call-to-action
3. **About**: Company overview and statistics
4. **Services**: Three service cards showcasing offerings
5. **Portfolio**: Gallery of recent work/projects
6. **Contact**: Contact form and information
7. **Footer**: Links, social media, and copyright

## Responsive Breakpoints

- **Desktop**: Full grid layouts (1200px+)
- **Tablet**: 2-column layouts (≤968px)
- **Mobile**: Single-column layouts (≤640px)

## Color Palette

- **Primary**: Indigo (#6366f1)
- **Secondary**: Slate (#0f172a)
- **Accent**: Amber (#f59e0b)
- **Background**: White (#ffffff) and Light Slate (#f8fafc)
- **Text**: Dark Slate (#1e293b) and Slate (#64748b)

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/ShafaqatIqbal77/Decode-lab-task-1.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Decode-lab-task-1
   ```

3. Open `index.html` in your web browser

## Local Development

To run the website locally:

Using Python:
```bash
python3 -m http.server 8000
```

Using Node.js (http-server):
```bash
npx http-server
```

Then open http://localhost:8000 in your browser.

## Customization

### Changing Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #0f172a;
    /* ... other variables */
}
```

### Updating Content
Edit the HTML content in `index.html` to change text, images, and links.

### Adding New Portfolio Items
Add new `<article class="portfolio-item">` elements in the portfolio section.

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

This project is open source and available for educational purposes.

## Author

Created by Shafaqat Iqbal

---

**Note**: This is a static website with no backend or JavaScript dependencies. All interactivity is handled through CSS hover states and smooth scrolling.
