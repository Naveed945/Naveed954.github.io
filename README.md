# Naveed Ahmed Mohammed - Portfolio

A beautiful, light & minimal portfolio website showcasing my work as a Senior Software Engineer & AI/ML Specialist.

## 🎯 Features

- **Light & Minimal Design** - Clean, professional aesthetic with purple accent colors
- **Fully Responsive** - Works perfectly on desktop, tablet, and mobile devices
- **Interactive Elements** - Typing text animation, smooth scrolling, fade-in animations
- **Fast Performance** - Pure HTML/CSS/JavaScript, no heavy frameworks
- **Accessible** - Semantic HTML, proper contrast ratios, keyboard navigation
- **SEO Optimized** - Proper meta tags, structured content

## 📁 File Structure

```
.
├── index.html          # Main portfolio page
├── README.md          # This file
└── _config.yml        # Jekyll configuration (optional)
```

## 🚀 Quick Start

### Option 1: GitHub Pages (Recommended)

1. Create a new repository named `username.github.io` (replace `username` with your GitHub username)
2. Clone the repository locally:
   ```bash
   git clone https://github.com/username/username.github.io
   cd username.github.io
   ```
3. Copy `index.html` to the repository root
4. Push to GitHub:
   ```bash
   git add .
   git commit -m "Initial portfolio commit"
   git push origin main
   ```
5. Your portfolio will be live at `https://username.github.io`

### Option 2: Custom Domain

If using a custom domain:
1. Follow steps 1-4 above
2. Create a `CNAME` file with your domain name
3. Update your DNS settings to point to GitHub Pages

### Option 3: Local Development

Simply open `index.html` in your browser:
```bash
open index.html
```

## 🎨 Customization

### Colors

Edit the CSS variables in the `<style>` section:

```css
:root {
    --primary: #2D1B69;      /* Main purple */
    --secondary: #5A189A;    /* Secondary purple */
    --accent: #9D4EDD;       /* Bright purple accent */
    --light-bg: #F8F7FC;     /* Background */
    --card-bg: #FFFFFF;      /* Card background */
    --text-dark: #2D3748;    /* Main text */
    --text-light: #718096;   /* Secondary text */
}
```

### Content

All content is directly in the HTML. Edit:
- Hero section text and buttons
- Skills cards
- Timeline entries (Experience section)
- Projects section
- Stats numbers
- Contact links

### Typography

Change fonts by updating the `font-family` in the `body` selector:

```css
body {
    font-family: 'Your Font Name', sans-serif;
}
```

### Logo Text

Change `NAM` (Naveed Ahmed Mohammed) in the navbar:

```html
<div class="logo">NAM</div>
```

## 📋 SEO & Meta Tags

Update these meta tags in the `<head>` section:

```html
<title>Your Name | Your Title</title>
<meta name="description" content="Your description here">
```

## 🔗 Links to Update

Search for and update these in the HTML:
- GitHub: `https://github.com/naveedmd954`
- LinkedIn: `https://linkedin.com/in/naveed-mohammed-51a431181`
- Email: `naveedmd954@gmail.com`
- Project links (currently pointing to `#`)

## 📱 Responsive Design

The portfolio is fully responsive with breakpoints at:
- Desktop: 1200px and above
- Tablet: 768px to 1199px
- Mobile: Below 768px

## ⚡ Performance

- **No external dependencies** - Pure HTML/CSS/JavaScript
- **Single file** - Easy to deploy and maintain
- **Fast load times** - Optimized animations and transitions
- **Lighthouse score** - Typically 95+ on all metrics

## 🔐 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎬 Animations Included

1. **Typing Text** - Cycles through roles with typing effect
2. **Fade-in Cards** - Skills and projects fade in on scroll
3. **Hover Effects** - Cards lift and add shadows on hover
4. **Smooth Scrolling** - Smooth transitions between sections
5. **Stats Counter** - Numbers animate when stats section comes into view
6. **Navigation Underline** - Links show animated underline on hover

## 📈 Future Enhancements

- Blog section
- Dark mode toggle
- Contact form integration
- Testimonials carousel
- Certificate showcase
- PDF resume download

## 📄 License

Free to use and modify. No attribution required.

## 💬 Questions?

Feel free to open an issue or reach out for customization help.

---

Built with ❤️ by Naveed Ahmed Mohammed
