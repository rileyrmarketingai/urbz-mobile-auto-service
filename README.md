# Urbz Mobile Auto Service Website

A modern, conversion-optimized website for Urbz Mobile Auto Service and Repair Shop in Stockton, CA.

## Features

- **Responsive Design**: Fully responsive across all devices (mobile, tablet, desktop)
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Conversion Optimized**: Strategic CTAs, online booking form, and trust-building elements
- **SEO Ready**: Semantic HTML, meta tags, and proper heading structure
- **Fast Loading**: Optimized CSS and vanilla JavaScript for performance
- **Accessibility**: WCAG compliant with proper ARIA labels and semantic markup

## Pages

1. **Home (index.html)**: Hero section, services preview, testimonials, booking form
2. **About (about.html)**: Company story, values, team information, service area
3. **Services (services.html)**: Detailed service descriptions, pricing philosophy, comparison
4. **Contact (contact.html)**: Contact form, location info, FAQ, emergency service

## Key Features

### Online Booking
- 24/7 online booking form
- Service type selection
- Mobile or in-shop location choice
- Instant submission with validation

### Trust Building
- 4.6-star rating prominently displayed
- Real customer testimonials
- Lifetime warranty on parts
- Transparent pricing information

### Mobile-First Design
- Optimized for mobile searches
- Touch-friendly navigation
- Fast loading on all devices
- Responsive images and layouts

### Conversion Elements
- Multiple strategic CTAs
- Click-to-call buttons
- Online booking forms
- Service comparison tools
- FAQ section

## Technology Stack

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **Vanilla JavaScript**: No dependencies, fast loading
- **Google Fonts**: Inter font family
- **Mobile Responsive**: Media queries for all screen sizes

## Color Scheme

- Primary: #FF6B35 (Orange)
- Secondary: #1A1A2E (Dark Blue)
- Accent: #FFD700 (Gold)
- Background: #F8F9FA (Light Gray)
- Text: #1A1A1A (Dark Gray)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Setup Instructions

1. Upload all files to your web server
2. Ensure directory structure is maintained:
   - /css/styles.css
   - /js/main.js
   - /images/ (for future images)
3. Update contact information if needed
4. Test all forms and links
5. Configure form submission endpoint (currently logs to console)

## Customization

### Update Contact Information
Edit the following in all HTML files:
- Phone: (209) 555-1234
- Email: paccoiwan@yahoo.com
- Address: 1045 Adelbert Ave, Stockton, CA 95215

### Update Colors
Edit CSS variables in `css/styles.css`:
```css
:root {
    --primary-color: #FF6B35;
    --secondary-color: #1A1A2E;
    /* etc. */
}
```

### Add Real Images
Replace placeholder divs with actual images in the `/images/` directory.

## Performance Optimization

- Minify CSS and JavaScript for production
- Optimize and compress images
- Enable gzip compression on server
- Implement caching headers
- Consider CDN for static assets

## SEO Recommendations

- Submit sitemap to Google Search Console
- Set up Google My Business
- Add schema markup for local business
- Optimize meta descriptions
- Add Open Graph tags for social sharing
- Create blog for content marketing

## Form Integration

Currently, forms log data to console. To integrate with a backend:

1. **Option 1**: Use a form service (Formspree, Netlify Forms, etc.)
2. **Option 2**: Connect to your own backend API
3. **Option 3**: Use email service (EmailJS, SendGrid, etc.)

Update the form submission handlers in `js/main.js`.

## Analytics

Add Google Analytics or similar tracking:
```html
<!-- Add before </head> -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-ID"></script>
```

## Support

For questions or support, contact the development team.

## License

© 2025 Urbz Mobile Auto Service. All rights reserved.
