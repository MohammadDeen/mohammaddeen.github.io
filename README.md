# Mohammad Deen Hayatu - Portfolio Website

A modern, responsive portfolio website showcasing the professional work and research of Mohammad Deen Hayatu, MSc, a doctoral candidate specializing in inflammation, immunology, and genetics.

## 🚀 Recent Enhancements (June 2025)

### Fixed Issues:
- **Profile Image**: Replaced expired LinkedIn URL with local image (`assets/images/profile.jpg`)
- **Mobile Responsiveness**: Added proper mobile navigation menu
- **User Experience**: Enhanced animations and interactions

### New Features:
- ✅ Mobile-responsive navigation menu
- ✅ Smooth scroll animations
- ✅ Back-to-top button
- ✅ Intersection Observer for fade-in animations
- ✅ Improved profile image with hover effects
- ✅ Enhanced hero section with better typography
- ✅ Better mobile menu UX

## 🛠️ Technical Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Framework**: Tailwind CSS
- **Icons**: Font Awesome 6.5.1
- **Fonts**: Custom Noto Sans Condensed
- **Hosting**: GitHub Pages

## 📱 Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile
- **SEO Optimized**: Proper meta tags, Open Graph, and Twitter Cards
- **Accessibility**: ARIA labels and semantic HTML
- **Performance**: Optimized images and minimal JavaScript
- **Analytics**: Google Analytics integration
- **Social Integration**: Links to LinkedIn, GitHub, ResearchGate, and X (Twitter)

## 🔧 Maintenance Notes

### Profile Image
- Current: `assets/images/profile.jpg`
- Dimensions: Optimized for 192x192px (w-48 h-48 in Tailwind)
- Format: JPG/PNG recommended
- Update path in `index.html` line ~87 if changing filename

### Adding Publications
Edit the Publications section in `index.html` around line 140-150. Follow the existing format:

```html
<div class="border-l-4 border-blue-600 pl-4 mb-6">
    <p class="text-lg mb-2"><em>Your Publication Title</em></p>
    <p class="text-gray-600">Authors (Year). Journal, Volume, Pages.</p>
    <a href="DOI_LINK" class="text-blue-600 hover:text-blue-800">Full Text →</a>
</div>
```

### Contact Information
Update contact details in the Contact section around line 190-200.

## 🚀 Deployment

This site is hosted on GitHub Pages. Any push to the main branch will automatically deploy.

1. Make your changes
2. Commit and push to GitHub
3. Changes will be live at: `https://mohammaddeen.github.io/`

## 📊 Performance Recommendations

1. **Image Optimization**: Consider WebP format for better compression
2. **CDN**: Tailwind and Font Awesome are loaded from CDN for better caching
3. **Analytics**: Currently using Google Analytics 4
4. **Security**: Added Usercentrics for GDPR compliance

## 🐛 Troubleshooting

### Profile Image Not Showing
1. Check if `assets/images/profile.jpg` exists
2. Verify file permissions
3. Clear browser cache
4. Check browser console for errors

### Mobile Menu Not Working
1. Ensure JavaScript is enabled
2. Check browser console for errors
3. Verify Font Awesome icons are loading

## 📝 Future Enhancements

Consider implementing:
- [ ] Dark mode toggle
- [ ] Blog/News section
- [ ] Interactive research timeline
- [ ] PDF CV download
- [ ] Contact form with backend
- [ ] Multi-language support
- [ ] Progressive Web App (PWA) features

## 📞 Support

For technical issues or updates, contact: mohammad.hayatu@uk-erlangen.de

---

© 2024 Mohammad Deen Hayatu. All rights reserved.