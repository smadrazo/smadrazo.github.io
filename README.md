# Modern Professional Resume Template

A clean, responsive HTML resume template built with Jekyll and optimized for GitHub Pages. Features contemporary design elements, smooth animations, and professional styling focused on showcasing your experience and skills.

## ✨ Features

### 🎨 **Modern Design**
- **Clean Professional Layout** - Elegant white design with blue gradient accents
- **Card-Based Sections** - Contemporary sectioned design for better content organization
- **Gradient Header** - Eye-catching blue gradient header with professional styling
- **Smooth Animations** - Subtle hover effects and scroll-triggered animations
- **Modern Typography** - Inter font family for excellent readability

### 📱 **Responsive & Accessible**
- **Mobile-First Design** - Optimized for all screen sizes from mobile to desktop
- **Touch-Friendly** - Enhanced mobile interactions and navigation
- **Accessibility Compliant** - Semantic HTML, proper contrast ratios, and keyboard navigation
- **Cross-Browser Compatible** - Works seamlessly across all modern browsers

### 🖨️ **Professional Output**
- **Print Optimized** - Professional print styles with proper page breaks
- **PDF Export Ready** - High-quality PDF generation with preserved styling
- **ATS Friendly** - Clean HTML structure for applicant tracking systems

### ⚡ **Performance & UX**
- **Fast Loading** - Optimized CSS with minimal dependencies
- **Smooth Scrolling** - Enhanced navigation experience
- **Interactive Elements** - Engaging hover states and micro-interactions
- **Clean Codebase** - Simple, maintainable code structure

## 🚀 Quick Start

1. **Fork or clone this repository**
   ```bash
   git clone https://github.com/yourusername/resume.git
   cd resume
   ```

2. **Update `_config.yml`** with your personal information
   ```yaml
   name: "Your Full Name"
   title_position: "Your Professional Title"
   email: "your.email@example.com"
   linkedin: "linkedin.com/in/yourprofile"
   github: "github.com/yourusername"
   ```

3. **Customize `index.md`** with your professional information:
   - Professional summary
   - Work experience with achievements
   - Education and certifications
   - Technical skills organized by category
   - Notable projects

4. **Enable GitHub Pages** in repository settings
   - Go to Settings → Pages
   - Select "Deploy from a branch"
   - Choose `main` branch and `/ (root)` folder

5. **Visit your resume** at `https://yourusername.github.io/resume`

## 🎨 Customization

### **Personal Information**
Edit the variables in `_config.yml`:
```yaml
name: "Your Full Name"
title_position: "Your Professional Title"
email: "your.email@example.com"
phone: "+1 (555) 123-4567"
location: "City, State"
linkedin: "linkedin.com/in/yourprofile"
github: "github.com/yourusername"
website: "yourwebsite.com" # optional
```

### **Content Structure**
Update `index.md` with your professional information:

- **Professional Summary** - Comprehensive career overview
- **Experience** - Detailed work history with achievements
- **Education** - Academic background and certifications
- **Technical Skills** - Organized by categories (6 skill groups)
- **Certifications** - Professional credentials in list format

### **Visual Customization**
Modify `assets/css/main.css` to customize:

- **Colors** - Primary blue (#3b82f6) and accent cyan (#06b6d4) colors
- **Typography** - Inter font family with professional hierarchy
- **Layout** - Card-based design with consistent spacing
- **Animations** - Hover effects and smooth transitions
- **Components** - Section styling, buttons, and interactive elements

### **Design Features**
- **Blue Gradient Header** - Professional header with contact information
- **Card-Based Sections** - Clean, organized content presentation
- **Hover Effects** - Interactive elements with smooth transitions
- **Responsive Design** - Mobile-first approach with breakpoints
- **Print Optimization** - Professional PDF export styling

## 💻 Local Development

### **Prerequisites**
- Ruby 2.7+ and Bundler
- Git

### **Setup**
1. **Install Jekyll:**
   ```bash
   gem install bundler jekyll
   ```

2. **Clone and setup:**
   ```bash
   git clone https://github.com/yourusername/resume.git
   cd resume
   bundle install
   ```

3. **Run locally:**
   ```bash
   bundle exec jekyll serve --livereload
   ```

4. **Visit:** `http://localhost:4000`

### **Development Features**
- **Live Reload** - Automatic browser refresh on changes
- **Theme Testing** - Test both light and dark themes
- **Responsive Preview** - Test on different screen sizes
- **Print Preview** - Test PDF export functionality

## 🚀 Deployment

### **GitHub Pages (Recommended)**
1. Push changes to `main` branch
2. Go to repository **Settings → Pages**
3. Select **"Deploy from a branch"**
4. Choose `main` branch and `/ (root)` folder
5. Resume available at `https://yourusername.github.io/resume`

### **Custom Domain (Optional)**
1. Add `CNAME` file with your domain
2. Configure DNS settings
3. Enable HTTPS in GitHub Pages settings

## 🖨️ PDF Export & Printing

### **Built-in Print Function**
- Click **"Print Resume"** button in header
- Use browser print: `Ctrl/Cmd + P`
- Optimized print styles ensure professional formatting

### **PDF Generation Tips**
- **Chrome/Chromium** recommended for best results
- Use **"Save as PDF"** destination
- Select **"More settings"** → **"Options"** → **"Background graphics"**
- Margins: **Minimum** or **Custom (0.4 inches)**

### **Print Features**
- **Professional Layout** - Optimized spacing and typography
- **Page Breaks** - Intelligent content flow
- **Color Preservation** - Maintains theme colors in print
- **Clean Output** - Removes interactive elements

## 🌟 Key Features Explained

### **Professional Design**
- **Clean Layout** - Focused on content with minimal distractions
- **Blue Gradient Header** - Eye-catching professional header design
- **Card-Based Sections** - Organized, scannable content structure
- **Consistent Styling** - Unified design language throughout

### **Modern Design Elements**
- **Subtle Animations** - Smooth hover and scroll effects
- **Professional Colors** - Blue and cyan gradient with clean whites/grays
- **Typography Hierarchy** - Clear information structure with Inter font
- **Interactive Elements** - Engaging hover states and transitions

### **Responsive Behavior**
- **Mobile-First** - Optimized for small screens first
- **Touch-Friendly** - Enhanced mobile interactions
- **Flexible Grid** - Adapts to any screen size
- **Progressive Enhancement** - Works without JavaScript

## 🔧 Browser Support

| Browser | Version | Features |
|---------|---------|----------|
| **Chrome** | 90+ | ✅ Full support (recommended for printing) |
| **Firefox** | 88+ | ✅ Full support |
| **Safari** | 14+ | ✅ Full support |
| **Edge** | 90+ | ✅ Full support |

## 📱 Mobile Experience

- **Touch Gestures** - Smooth scrolling and interactions
- **Optimized Typography** - Readable on small screens
- **Compressed Layout** - Efficient use of mobile space
- **Fast Loading** - Optimized for mobile networks

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit changes: `git commit -am 'Add feature'`
4. Push to branch: `git push origin feature-name`
5. Submit a Pull Request

## 📄 License

**MIT License** - Feel free to use this template for your professional resume!

---

### 💡 **Pro Tips**
- **Customize colors** by editing the blue (#3b82f6) and cyan (#06b6d4) values in main.css
- **Test print output** regularly during customization using the print button
- **Keep content concise** - focus on achievements and quantifiable impact
- **Use action verbs** in experience descriptions for better ATS compatibility
- **Maintain consistency** in formatting across all sections
- **Update contact information** in _config.yml before deploying