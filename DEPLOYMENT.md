# Deployment Checklist

## Pre-Deployment

- [ ] Verify all HTML files are present
- [ ] Check all CSS files in assets/css/
- [ ] Ensure all JavaScript files are in assets/js/
- [ ] Confirm all images are in assets/img/
- [ ] Test all navigation links
- [ ] Verify responsive design on mobile
- [ ] Check browser compatibility
- [ ] Test Google Maps integration
- [ ] Validate all contact information

## Files to Upload

### Root Directory
- index.html
- profile.html
- businesses.html
- contact.html

### Assets Directory Structure
```
assets/
├── css/
│   ├── bootstrap.min.css
│   ├── animate.min.css
│   ├── magnific-popup.css
│   ├── fontawesome-all.min.css
│   ├── flaticon.css
│   ├── odometer.css
│   ├── swiper-bundle.css
│   ├── aos.css
│   ├── default.css
│   └── main.css
├── js/
│   └── [all JavaScript files]
├── img/
│   └── [all images organized in subfolders]
└── fonts/
    └── [flaticon font files]
```

## Testing After Deployment

1. **Homepage**
   - [ ] Banner loads correctly
   - [ ] All images display
   - [ ] Navigation works
   - [ ] Scroll animations work
   - [ ] Social media links are present

2. **Company Profile Page**
   - [ ] Breadcrumb navigation works
   - [ ] Images load
   - [ ] Content displays correctly
   - [ ] CTA button works

3. **Our Businesses Page**
   - [ ] All 4 business cards display
   - [ ] Images load correctly
   - [ ] Layout is responsive

4. **Contact Page**
   - [ ] Google Maps iframe loads
   - [ ] Contact information is correct
   - [ ] Phone and email links work
   - [ ] Breadcrumb navigation works

5. **Cross-Page Testing**
   - [ ] Header is consistent across all pages
   - [ ] Footer is consistent across all pages
   - [ ] Active menu highlighting works on each page
   - [ ] Mobile menu functions properly
   - [ ] All internal links work (no 404 errors)

## Performance Checks

- [ ] Page load time < 3 seconds
- [ ] Images are optimized
- [ ] CSS/JS files are minified
- [ ] No console errors in browser
- [ ] HTTPS enabled (if applicable)

## SEO Checklist

- [ ] All pages have unique titles
- [ ] Meta descriptions present
- [ ] Proper heading hierarchy (H1, H2, etc.)
- [ ] Alt text on images
- [ ] Favicon displays

## Mobile Responsive Test

- [ ] Test on iPhone (Safari)
- [ ] Test on Android (Chrome)
- [ ] Test on tablet
- [ ] Navigation menu works on mobile
- [ ] All content is readable
- [ ] Buttons are easily clickable

## Browser Compatibility

- [ ] Chrome (Windows/Mac)
- [ ] Firefox (Windows/Mac)
- [ ] Safari (Mac)
- [ ] Edge (Windows)
- [ ] Mobile Safari (iOS)
- [ ] Chrome Mobile (Android)

## Final Checks

- [ ] Remove any test/debug code
- [ ] Update copyright year if needed
- [ ] Verify all phone numbers
- [ ] Verify all email addresses
- [ ] Check all external links
- [ ] Backup current live site (if updating)
- [ ] Set up 301 redirects if changing from .php to .html

## Post-Deployment

- [ ] Submit sitemap to Google Search Console
- [ ] Test contact form (if added later)
- [ ] Monitor server logs for errors
- [ ] Check analytics setup
- [ ] Verify SSL certificate
- [ ] Test from different locations/networks

## Notes

- Original PHP site used dynamic includes for header/footer
- Now each page has complete HTML (easier to maintain)
- Active navigation state is set per page
- No server-side processing required
- Can be hosted on any static file server

## Hosting Options

1. **Shared Hosting** - Traditional web hosting (cPanel, etc.)
2. **GitHub Pages** - Free static hosting
3. **Netlify** - Free tier available, easy deployment
4. **Vercel** - Free for personal projects
5. **AWS S3** - Static website hosting
6. **Google Cloud Storage** - Static website hosting
7. **Azure Static Web Apps** - Free tier available

## Contact for Support

If you encounter any issues during deployment, contact your web development team.
