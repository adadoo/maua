# MAUA International Limited - Pure HTML Website

This is the converted pure HTML/CSS version of the MAUA International Limited website. All PHP dependencies have been removed and replaced with static HTML files.

## Folder Structure

```
maua-website/
│
├── index.html                 # Homepage
├── profile.html              # Company Profile page
├── businesses.html           # Our Businesses page
├── contact.html              # Contact page
│
├── assets/
│   ├── css/
│   │   ├── bootstrap.min.css
│   │   ├── animate.min.css
│   │   ├── magnific-popup.css
│   │   ├── fontawesome-all.min.css
│   │   ├── flaticon.css
│   │   ├── odometer.css
│   │   ├── swiper-bundle.css
│   │   ├── aos.css
│   │   ├── default.css
│   │   └── main.css
│   │
│   ├── js/
│   │   ├── vendor/
│   │   │   └── jquery-3.6.0.min.js
│   │   ├── bootstrap.bundle.min.js
│   │   ├── jquery.magnific-popup.min.js
│   │   ├── jquery.odometer.min.js
│   │   ├── jquery.appear.js
│   │   ├── gsap.js
│   │   ├── ScrollTrigger.js
│   │   ├── SplitText.js
│   │   ├── gsap-animation.js
│   │   ├── jquery.parallaxScroll.min.js
│   │   ├── swiper-bundle.js
│   │   ├── ajax-form.js
│   │   ├── wow.min.js
│   │   ├── aos.js
│   │   └── main.js
│   │
│   ├── img/
│   │   ├── logo/
│   │   │   └── logo.png
│   │   ├── banner/
│   │   │   └── banner_bg.jpg
│   │   ├── bg/
│   │   │   ├── breadcrumb_bg.jpg
│   │   │   └── request_bg.jpg
│   │   ├── images/
│   │   │   ├── h4_about_img01.jpg
│   │   │   ├── inner_about01.jpg
│   │   │   ├── inner_about02.jpg
│   │   │   ├── inner_about_shape.jpg
│   │   │   ├── choose_img01.jpg
│   │   │   ├── choose_img_shape.png
│   │   │   ├── breadcrumb_shape01.png
│   │   │   ├── breadcrumb_shape02.png
│   │   │   ├── breadcrumb_shape03.png
│   │   │   ├── breadcrumb_shape04.png
│   │   │   ├── breadcrumb_shape05.png
│   │   │   ├── request_shape01.png
│   │   │   ├── request_shape02.png
│   │   │   ├── choose_shape01.png
│   │   │   ├── choose_shape02.png
│   │   │   ├── footer_shape01.png
│   │   │   └── footer_shape02.png
│   │   ├── project/
│   │   │   ├── project_img01.jpg
│   │   │   ├── project_img02.jpg
│   │   │   ├── project_img03.jpg
│   │   │   ├── project_img04.jpg
│   │   │   └── project_shape01.png
│   │   └── favicon.png
│   │
│   └── fonts/
│       └── flaticon files (eot, woff, woff2, ttf, svg)
│
└── README.md                 # This file
```

## Changes Made from PHP to HTML

### 1. **Removed PHP Dependencies**
   - Eliminated all `<?php ?>` tags
   - Removed `$page` variable logic
   - Removed `include_once()` statements

### 2. **Static Navigation**
   - Each page now has the complete header and footer embedded
   - Active menu states are hardcoded per page using `class="active"`

### 3. **File Extensions**
   - Changed all links from `.php` to `.html`
   - Updated all internal navigation links

### 4. **Character Encoding Fixes**
   - Fixed "Kol–1" (was showing as "Kolâ€"1")
   - Fixed "let's Talk" (was showing as "letâ€™s Talk")

## Deployment Instructions

### Option 1: Simple HTTP Server (for testing)

**Using Python:**
```bash
# Navigate to the website folder
cd maua-website

# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Then open your browser and go to `http://localhost:8000`

**Using Node.js (http-server):**
```bash
# Install http-server globally
npm install -g http-server

# Navigate to the website folder
cd maua-website

# Start server
http-server -p 8000
```

### Option 2: Upload to Web Server

1. **Upload all files** to your web hosting via FTP/SFTP
2. Ensure the folder structure is maintained
3. Set proper permissions (644 for files, 755 for directories)
4. Access via your domain name

### Option 3: GitHub Pages

1. Create a GitHub repository
2. Upload all files maintaining the folder structure
3. Go to Settings > Pages
4. Select your branch (usually `main`)
5. Your site will be live at `https://yourusername.github.io/repository-name`

## File Requirements

Make sure you have the following files in your `assets` directory (not included in this conversion):

### JavaScript Files (`assets/js/`)
- vendor/jquery-3.6.0.min.js
- bootstrap.bundle.min.js
- jquery.magnific-popup.min.js
- jquery.odometer.min.js
- jquery.appear.js
- gsap.js
- ScrollTrigger.js
- SplitText.js
- gsap-animation.js
- jquery.parallaxScroll.min.js
- swiper-bundle.js
- ajax-form.js
- wow.min.js
- aos.js
- main.js

### Images (`assets/img/`)
All image files as shown in the folder structure above

### Fonts (`assets/fonts/`)
- flaticon files (required for icons)

## Browser Compatibility

This website is compatible with:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Features

✅ Fully responsive design
✅ Pure HTML/CSS (no PHP required)
✅ No database needed
✅ Works on any static hosting
✅ Fast loading
✅ SEO friendly
✅ Mobile-friendly navigation
✅ Google Maps integration
✅ Animated elements (AOS library)
✅ Modern UI components

## Pages

1. **Home (index.html)** - Landing page with company overview
2. **Company Profile (profile.html)** - Detailed company information
3. **Our Businesses (businesses.html)** - Products and services
4. **Contact (contact.html)** - Contact information with Google Maps

## Support

For any issues or questions, please contact the development team.

## Credits

- **Company:** MAUA International Limited
- **Developed by:** Transinfo Solutions
- **Template:** Business Consulting HTML Template
- **Conversion:** PHP to Pure HTML/CSS

## License

All rights reserved by MAUA International Limited.
