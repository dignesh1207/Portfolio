# Dignesh Solanki - Portfolio Website

A modern, interactive portfolio website with dark/light mode toggle featuring a professional blue/teal color scheme.

## 📁 File Structure

```
portfolio/
├── index.html              # Main HTML file
├── styles.css              # All CSS styling
├── script.js               # All JavaScript functionality
├── Dignesh_Solanki_Resume.pdf  # Your resume (add this file)
└── README.md              # This file
```

## 🎨 Features

- **Dark/Light Mode Toggle**: Switches between themes and saves preference
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile
- **Smooth Animations**: Scroll-triggered animations and hover effects
- **Interactive Elements**: 
  - Scroll progress indicator
  - Mouse cursor gradient effect
  - Animated skill cards
  - Portfolio hover overlays
- **Professional Sections**:
  - Hero/Landing
  - About
  - Skills (6 skill cards)
  - Projects/Portfolio (6 projects)
  - Resume (Experience & Education)
  - Contact

## 🎨 Color Scheme

### Light Mode
- Primary: `#2d6a8e` (Professional Blue)
- Accent: `#4a9bc7` (Light Blue)
- Background: `#f8f5f0` (Warm Paper)
- Text: `#1a1a1a` (Dark Ink)

### Dark Mode
- Primary: `#5dade2` (Bright Blue)
- Accent: `#85c1e9` (Sky Blue)
- Background: `#1a1a1a` (Dark)
- Text: `#f8f5f0` (Light)

## 🚀 How to Use

1. **Download all files** to the same folder
2. **Add your profile picture** - Name it `profile.jpg` and place it in the same folder (will appear as a circular image in the About section)
3. **Add your resume PDF** - Name it `Dignesh_Solanki_Resume.pdf` and place it in the same folder
4. **Open `index.html`** in your web browser
5. **Customize content**:
   - Edit `index.html` to update text, images, and links
   - Modify `styles.css` to change colors or styling
   - Adjust `script.js` for different animations or features

## 📝 Customization Guide

### Update Your Information

**Personal Details** (in `index.html`):
- Line 15: Page title
- Line 19: Logo/name in navigation
- Lines 32-37: Hero section text
- Lines 43-50: About section content
- Lines 217-238: Contact information

**Projects** (in `index.html`):
- Lines 113-159: Portfolio grid items
- Replace image URLs with your own project screenshots
- Update project titles and descriptions

**Resume** (in `index.html`):
- Lines 169-213: Work experience and education
- Update job titles, companies, dates, and descriptions

### Change Colors

Edit `styles.css` - Lines 1-17:
```css
:root {
    --accent: #YOUR_COLOR;  /* Main accent color */
}
```

### Replace Images

Update image URLs in `index.html`:
- Profile picture (line 51): Replace `profile.jpg` with your photo filename
  - **Recommended:** Use a square photo (e.g., 500x500px) for best circular display
  - Save as `profile.jpg` in the same folder as index.html
- Portfolio projects now show as clean cards without images

## 🔧 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS variables, flexbox, and grid
- **Vanilla JavaScript**: No frameworks, pure JS for interactivity
- **Google Fonts**: 
  - Bebas Neue (headings)
  - Playfair Display (titles)
  - Crimson Text (body)

## 📱 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 💡 Tips

1. **Optimize Images**: Use compressed images for faster loading
2. **Add Your Own Photos**: Replace placeholder images with real project screenshots
3. **Test Responsiveness**: Check on different screen sizes
4. **Update Links**: Make sure all social links point to your actual profiles
5. **Host Online**: Upload to GitHub Pages, Netlify, or Vercel for free hosting

## 📄 License

Free to use and modify for personal projects.

## 🤝 Support

For questions or issues, contact: solank86@uwindsor.ca

---

Built with 💙 by Dignesh Solanki
