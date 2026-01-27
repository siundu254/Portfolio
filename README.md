# Kevin Siundu Wafula - iOS Developer Portfolio

## 📱 About This Portfolio

A modern, responsive portfolio website showcasing my expertise as a Senior iOS Engineer with 7+ years of experience. This portfolio highlights my technical skills, professional experience, and personal iOS projects with direct links to GitHub repositories.

## ✨ Features

### 🎨 Modern Design
- **Clean iOS-inspired UI** with Apple's design language
- **Responsive layout** that works on all devices (mobile, tablet, desktop)
- **Smooth animations** and transitions
- **Dark/Light mode ready** color scheme
- **Gradient accents** using iOS blue (#007AFF) and creative purple (#5856D6)

### 📋 Content Sections
1. **Hero Section** - Eye-catching introduction with call-to-action buttons
2. **About Me** - Creative section with development philosophy and technical expertise
3. **Personal Projects** - Showcasing iOS applications with GitHub links
4. **Professional Experience** - Timeline of career progression
5. **Documents** - Downloadable resume and cover letter
6. **Contact** - Multiple ways to get in touch

### 🔗 Key Functionality
- **Direct GitHub integration** with live repository links
- **PDF downloads** for professional documents
- **Smooth navigation** with scroll-to-section functionality
- **Mobile-responsive hamburger menu**
- **Interactive elements** with hover effects
- **Performance optimized** with lazy loading

## 🛠️ Technologies Used

### Frontend
- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript** - Interactive elements and animations
- **Font Awesome** - Icon library for visual elements
- **Google Fonts** - Typography using system fonts

### Hosting & Integration
- **GitHub Pages** - Free hosting and deployment
- **GitHub API** - Direct repository integration
- **GitHub Raw Content** - PDF document hosting

### Development Tools
- **VS Code** - Code editor
- **Git** - Version control
- **GitHub** - Repository hosting and deployment

## 📁 Project Structure

```
portfolio/
│
├── index.html                    # Main portfolio file
│
├── assets/                       # All static assets
│   ├── downloads/                # Professional documents
│   │   ├── Kevin_Siundu_Resume.pdf
│   │   └── Kevin_Siundu_Cover_Letter.pdf
│   │
│   ├── images/                   # Project screenshots and icons
│   │   ├── projects/
│   │   │   ├── todo-list.png
│   │   │   └── calculator.png
│   │   └── profile/
│   │
│   └── css/                      # Stylesheets (optional)
│
├── README.md                     # This documentation file
│
└── .gitignore                    # Git ignore file
```

## 🚀 Quick Start Guide

### Option 1: Use as Template (Recommended)
1. **Fork this repository** to your GitHub account
2. **Clone your fork** to your local machine:
   ```bash
   git clone https://github.com/YOUR_USERNAME/portfolio.git
   cd portfolio
   ```
3. **Customize the content** in `index.html`:
   - Replace personal information
   - Update project details
   - Add your own images and PDFs
4. **Upload your documents** to `assets/downloads/`
5. **Update GitHub links** to point to your repositories
6. **Commit and push** changes:
   ```bash
   git add .
   git commit -m "Customize portfolio"
   git push origin main
   ```
7. **Enable GitHub Pages** in repository settings

### Option 2: Manual Setup
1. Create a new repository named `portfolio`
2. Create the folder structure shown above
3. Copy the HTML content into `index.html`
4. Upload your PDF documents to `assets/downloads/`
5. Enable GitHub Pages in Settings → Pages

## 📄 Document Setup

### Adding Your PDFs
1. Place your resume and cover letter in `assets/downloads/`
2. Recommended file names:
   - `Kevin_Siundu_Resume.pdf`
   - `Kevin_Siundu_Cover_Letter.pdf`
3. Update the download links in the HTML:
   ```html
   <!-- Resume link -->
   <a href="https://github.com/YOUR_USERNAME/portfolio/raw/main/assets/downloads/Your_Resume.pdf"
      download="Your_Name_Resume.pdf">
   
   <!-- Cover letter link -->
   <a href="https://github.com/YOUR_USERNAME/portfolio/raw/main/assets/downloads/Your_Cover_Letter.pdf"
      download="Your_Name_Cover_Letter.pdf">
   ```

### GitHub Pages Configuration
1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under **Source**, select:
   - Branch: **main**
   - Folder: **/(root)**
4. Click **Save**
5. Your site will be available at: `https://YOUR_USERNAME.github.io/portfolio/`

## 🔧 Customization Guide

### Personal Information
Edit these sections in the HTML:
- **Name and title** - Hero section
- **Contact details** - Contact section
- **Social media links** - Footer
- **About me text** - About section

### Projects
To add/update projects:
1. Find the projects section in the HTML
2. Duplicate a project card structure
3. Update:
   - Project title and description
   - Technology tags
   - GitHub repository links
   - Project images

### Skills
Update the skills cloud:
- Add/remove skill tags
- Adjust colors by changing the CSS classes
- Categorize skills with different styling

### Experience
Modify the timeline section:
- Add new timeline items
- Update company names and dates
- Edit role descriptions

## 🎯 Key Customization Points

### 1. Change Colors
Edit the CSS variables at the top of the HTML:
```css
:root {
    --primary: #007AFF;    /* iOS blue */
    --dark: #1a1a1a;       /* Dark text */
    --light: #f8f9fa;      /* Light background */
    --creative: #5856D6;   /* Accent purple */
}
```

### 2. Update Images
Replace image URLs in the project cards:
```html
<img src="https://raw.githubusercontent.com/YOUR_USERNAME/PROJECT/main/path/to/image.png"
     alt="Project Name"
     onerror="this.onerror=null; this.src='FALLBACK_IMAGE_URL'">
```

### 3. Add Analytics
Add Google Analytics before the closing `</head>` tag:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 📈 Performance Optimization Tips

1. **Image Optimization**
   - Use WebP format for better compression
   - Implement lazy loading for images
   - Set appropriate image dimensions

2. **Code Optimization**
   - Minify CSS and JavaScript for production
   - Use CSS sprites for icons
   - Implement caching strategies

3. **SEO Best Practices**
   - Add meta descriptions and Open Graph tags
   - Use semantic HTML elements
   - Create a sitemap.xml

## 🐛 Troubleshooting

### Common Issues & Solutions

| Issue | Solution |
|-------|----------|
| GitHub Pages not updating | Wait 1-2 minutes for cache to clear |
| PDFs not downloading | Check raw GitHub URL format |
| Images not loading | Verify image paths and fallback URLs |
| Mobile menu not working | Check JavaScript console for errors |

### Browser Compatibility
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 11+
- ✅ Edge 79+
- ✅ Mobile browsers

## 🔗 Useful Resources

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Font Awesome Icons](https://fontawesome.com/icons)
- [Unsplash for Images](https://unsplash.com/)
- [CSS Gradient Generator](https://cssgradient.io/)
- [HTML Validator](https://validator.w3.org/)

## 🤝 Contributing

While this is a personal portfolio, feel free to:
1. Fork the repository
2. Create a feature branch
3. Make your improvements
4. Submit a pull request

## 📄 License

This portfolio template is available under the MIT License. See the LICENSE file for more details.

## 📬 Contact

**Kevin Siundu Wafula**
- Email: siundu344@gmail.com
- GitHub: [@siundu254](https://github.com/siundu254)
- LinkedIn: [Kevin Siundu](https://www.linkedin.com/in/kevin-siundu-506b2a162)
- Location: Nairobi, Kenya

---

⭐ **If you found this portfolio helpful, please give it a star on GitHub!** ⭐
