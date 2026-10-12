# Kevin Siundu Wafula - Engineering Portfolio

Personal portfolio for a senior iOS engineer and technology founder. It presents shipped mobile games from NovaLumina Studio, AI-agent products in development at Techna, open-source contributions, professional experience, and downloadable application documents.

## ✨ Features

### Design
- Responsive single-page layout for desktop and mobile
- Teal and warm accent palette with product artwork
- Lightweight HTML, CSS, and JavaScript; no build step

### 📋 Content Sections
1. Introduction and technical skills
2. Shipped NovaLumina iOS and Android games
3. Clarity and ForgeLab live previews, labelled as pending production release
4. Strix and other open-source contributions
5. Professional experience and downloadable CV and cover letter
6. Contact details

### 🔗 Key Functionality
- **Direct project, app-store, and GitHub links**
- **PDF downloads** served from the portfolio itself
- **Smooth navigation** with scroll-to-section functionality
- **Mobile-responsive hamburger menu**
- **Interactive elements** with hover effects
- **Lazy-loaded game artwork**

## 🛠️ Technologies Used

### Frontend
- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript** - Interactive elements and animations
- **Font Awesome** - Icon library for visual elements
- **Google Fonts** - Typography using system fonts

### Hosting
The site is static and can be hosted by GitHub Pages or any static web host.

## 📁 Project Structure

```
portfolio/
│
├── index.html
├── assets/
│   └── downloads/
│       ├── Kevin_Siundu_Resume.html
│       ├── Kevin_Siundu_Resume.pdf
│       ├── Kevin_Siundu_Cover_Letter.html
│       └── Kevin_Siundu_Cover_Letter.pdf
├── README.md
└── LICENSE
```

## Preview and publishing

Open `index.html` directly for a local preview. The portfolio has no build step. Publish the repository root with GitHub Pages or upload the files to another static host. Keep the relative PDF links and `assets/downloads/` paths intact when publishing.

The document HTML files are editable sources; the matching PDFs are the files linked from the site. Update both formats when revising the CV or cover letter.

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
   --primary: #146b5d;    /* Teal */
   --dark: #1b2927;       /* Dark text */
   --light: #f2f7f4;      /* Light background */
   --creative: #c56b45;   /* Warm accent */
}
```

### 2. Update Images
Replace image URLs in the project showcase:
```html
<img src="https://example.com/path/to/image.png"
   alt="Project name">
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
| PDFs not downloading | Verify the local `assets/downloads/` paths and uploaded PDF files |
| Images not loading | Verify image URLs and that the remote host permits public access |
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
