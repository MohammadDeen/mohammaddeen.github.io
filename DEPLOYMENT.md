# Deployment Guide

## Quick Deploy to GitHub Pages

1. **Commit your changes:**
   ```bash
   git add .
   git commit -m "Enhanced portfolio with fixed profile image and improved UX"
   git push origin main
   ```

2. **GitHub Pages will automatically deploy** - no additional setup needed since this is already configured.

3. **Check your live site** at: `https://mohammaddeen.github.io/`

## Important: Profile Image Setup

Since you have `profile.jpg` in your `assets/images/` folder, make sure this is your current professional photo. The old LinkedIn URL has been replaced with this local image.

**To update your profile photo:**
1. Replace `assets/images/profile.jpg` with your new photo
2. Recommended dimensions: 400x400px or larger (square aspect ratio)
3. Keep file size under 500KB for optimal loading
4. Commit and push the changes

## Testing Locally

If you want to test changes before deploying:

1. **Install a simple HTTP server:**
   ```bash
   # Using Python (if installed)
   python -m http.server 8000
   
   # Or using Node.js (if installed)
   npx http-server
   ```

2. **Open your browser** to `http://localhost:8000`

## Troubleshooting

### Profile Image Not Showing
- Verify `assets/images/profile.jpg` exists and is not corrupted
- Check file permissions
- Clear browser cache (Ctrl+F5)

### Mobile Menu Not Working
- Check browser console for JavaScript errors
- Ensure Font Awesome is loading properly

### Changes Not Appearing
- GitHub Pages can take 5-10 minutes to deploy changes
- Try hard refresh (Ctrl+F5)
- Check repository settings → Pages section

## Performance Tips

1. **Optimize images** before uploading:
   - Use tools like TinyPNG or Squoosh
   - Consider WebP format for better compression

2. **Monitor loading speed**:
   - Use Google PageSpeed Insights
   - Check Core Web Vitals

## Security

- Usercentrics script is included for GDPR compliance
- Google Analytics is properly configured
- All external links are properly attributed

---

Need help? Contact: mohammad.hayatu@uk-erlangen.de
