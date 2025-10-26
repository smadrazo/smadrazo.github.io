# Modern Minimal Resume

A professional, responsive HTML resume built with Jekyll and hosted on GitHub Pages.

## Features

- **Modern Minimal Design** - Clean, professional layout with subtle colors
- **Fully Responsive** - Looks great on desktop, tablet, and mobile
- **Print Optimized** - Professional print styles with proper page breaks
- **SEO Optimized** - Meta tags and structured data for search engines
- **Fast Loading** - Optimized CSS and minimal dependencies
- **Accessible** - Semantic HTML and proper contrast ratios

## Setup

1. **Fork or clone this repository**
2. **Update `_config.yml`** with your personal information
3. **Customize `index.md`** with your experience, education, and skills
4. **Enable GitHub Pages** in repository settings
5. **Visit your resume** at `https://yourusername.github.io/resume`

## Customization

### Personal Information
Edit the variables in `_config.yml`:
```yaml
name: "Your Full Name"
title_position: "Your Job Title"
email: "your.email@example.com"
# ... etc
```

### Content
Update `index.md` with your:
- Professional summary
- Work experience
- Education
- Skills
- Projects

### Styling
Modify `assets/css/main.css` to customize:
- Colors (CSS variables at the top)
- Typography
- Layout
- Spacing

### Print Styles
The resume includes optimized print styles in `assets/css/print.css` for professional PDF generation.

## Local Development

1. Install Jekyll:
   ```bash
   gem install bundler jekyll
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Run locally:
   ```bash
   bundle exec jekyll serve
   ```

4. Visit `http://localhost:4000`

## GitHub Pages Deployment

1. Push your changes to the `main` branch
2. Go to repository Settings → Pages
3. Select "Deploy from a branch"
4. Choose `main` branch and `/ (root)` folder
5. Your resume will be available at `https://yourusername.github.io/resume`

## Printing/PDF Export

Click the "Print Resume" button or use your browser's print function (Ctrl/Cmd + P) to generate a PDF. The print styles ensure professional formatting with proper page breaks.

## Browser Support

- Chrome/Chromium (recommended for printing)
- Firefox
- Safari
- Edge

## License

MIT License - feel free to use this template for your own resume!