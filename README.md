# Rivendell AI - Agency Website

A modern, responsive website for Rivendell AI - an AI solutions and consulting agency. Built with vanilla HTML, CSS, and JavaScript, featuring a clean design and excellent user experience.

## 📁 Project Structure

```
Rivendell-AI/
├── index.html                 # Main homepage
├── assets/                    # Images, icons, and media files
│   ├── favicon.png
│   └── og-image.png
├── css/
│   ├── style.css             # Main stylesheet
│   └── responsive.css        # Mobile and responsive styles
├── js/
│   └── main.js              # JavaScript interactivity
├── pages/
│   ├── portfolio.html        # Portfolio and projects showcase
│   ├── solutions.html        # AI Solutions and products
│   ├── packages.html         # Pricing and packages
│   └── contact.html          # Contact form and information
└── README.md                 # This file
```

## 🌐 Pages

### 1. **Home (index.html)**
   - Hero section with call-to-action
   - Services overview (6 main services)
   - Portfolio showcase (6 featured projects)
   - Solutions presentation
   - Pricing packages
   - Team introduction
   - Contact/CTA section

### 2. **Portfolio (pages/portfolio.html)**
   - Showcase of 150+ AI projects
   - Filterable portfolio items
   - Project categories: AI/ML, Analytics, Automation, NLP, Vision
   - Detailed project cards

### 3. **Solutions (pages/solutions.html)**
   - AI Model Hub (Available)
   - MLOps Platform (Upcoming)
   - Data Pipeline Framework (Available)
   - Status badges and feature lists

### 4. **Packages (pages/packages.html)**
   - Three pricing tiers: Starter ($299), Pro ($799-$1,999), Enterprise (Custom)
   - Comparison table
   - FAQ section
   - Feature breakdown

### 5. **Contact (pages/contact.html)**
   - Contact form with validation
   - Contact information
   - Office hours
   - Social media links
   - Why Choose Us section

## 🎨 Design Features

- **Color Scheme:**
  - Primary: Purple (#7C3AED)
  - Secondary: Pink (#EC4899)
  - Accent: Cyan (#06B6D4)

- **Responsive Design:**
  - Mobile-first approach
  - Breakpoints: 768px, 480px, 360px
  - Hamburger menu for mobile navigation
  - Optimized for all devices

- **Modern UI Elements:**
  - Smooth animations and transitions
  - Hover effects on cards and buttons
  - Gradient backgrounds
  - Professional typography (Poppins & Inter fonts)

## 🔧 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Styling and animations
- **JavaScript (Vanilla)** - Interactivity
- **Google Fonts** - Typography

## 📱 Features

✅ Responsive navigation with hamburger menu
✅ Smooth scroll behavior
✅ Portfolio filtering system
✅ Contact form handling
✅ CTA buttons throughout
✅ Team member showcase
✅ Pricing comparison table
✅ Mobile-optimized design
✅ Accessibility features
✅ Print-friendly styles
✅ Dark mode support (CSS variables)

## 🚀 Getting Started

1. **Extract the project files** to your desired directory
2. **Open `index.html` in a web browser** or serve locally:

```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if you have http-server installed)
http-server
```

3. Navigate to `http://localhost:8000` in your browser

## 📝 Customization

### Change Colors
Edit CSS variables in `css/style.css`:
```css
:root {
    --primary: #7C3AED;      /* Purple */
    --secondary: #EC4899;    /* Pink */
    --accent: #06B6D4;       /* Cyan */
    /* ... other variables ... */
}
```

### Update Content
Edit HTML files directly to update:
- Company information
- Service descriptions
- Portfolio projects
- Pricing details
- Team members
- Contact information

### Add Images
Place image files in the `assets/` folder and reference them:
```html
<img src="./assets/your-image.png" alt="Description">
```

## 🔗 Navigation Links

All navigation links are pre-configured:
- Home → `index.html`
- Services → `index.html#services`
- Portfolio → `pages/portfolio.html`
- Solutions → `pages/solutions.html`
- Packages → `pages/packages.html`
- Contact → `pages/contact.html`

## 📧 Contact Form

The contact form on `pages/contact.html` includes:
- Name field
- Email field
- Company name
- Service selection dropdown
- Message textarea
- Basic form validation

**Note:** To fully integrate the form with email, you'll need to set up a backend service or use a third-party form handler (Formspree, Netlify Forms, etc.)

## 🌙 Dark Mode

The website includes CSS media query support for dark mode preference:
```css
@media (prefers-color-scheme: dark) {
    /* Dark mode styles */
}
```

## ♿ Accessibility

Features include:
- Semantic HTML structure
- Proper heading hierarchy
- Alt text for images
- Color contrast compliance
- Reduced motion support
- Keyboard navigation support

## 📱 Mobile Optimization

- Mobile-first responsive design
- Touch-friendly buttons and links
- Optimized images for mobile
- Hamburger menu for small screens
- Readable font sizes at all breakpoints

## 🎯 Browser Compatibility

Works on:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This website template is provided as-is for the Rivendell AI project.

## 🤝 Support

For customization or issues, refer to the inline comments in the CSS and JavaScript files, or consider:
1. Checking the browser console for errors
2. Testing in different browsers
3. Validating HTML at https://validator.w3.org/

## 🎓 Learning Resources

- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS-Tricks](https://css-tricks.com/)
- [Web.dev](https://web.dev/)

---

**Version:** 1.0  
**Last Updated:** January 2026  
**Created for:** Rivendell AI
