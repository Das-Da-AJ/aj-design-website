# AJ design - Company Website

A professional landing page for AJ design, an early-stage app development company.

## Overview

This is a static website built with HTML, CSS, and JavaScript. It's designed to be:
- **Low cost**: No backend required, can be hosted on any static hosting service
- **Professional**: Modern, clean design that establishes credibility
- **Responsive**: Works on all devices (desktop, tablet, mobile)
- **Fast**: Lightweight and optimized for quick loading

## Features

- **Hero Section**: Eye-catching introduction with call-to-action buttons
- **About Section**: Company information and core values
- **Services Section**: Overview of app development services offered
- **Contact Section**: Contact form and information
- **Responsive Navigation**: Mobile-friendly menu with smooth scrolling
- **Modern Design**: Clean, professional aesthetic

## Setup Instructions

### Local Development

1. **Clone or download** this repository to your local machine

2. **Open the website**:
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (if you have http-server installed)
     npx http-server
     ```
   - Then visit `http://localhost:8000` in your browser

### Deployment Options

Since this is a static website, you can host it on any static hosting service:

#### Free Options:
- **GitHub Pages**: Push to a GitHub repository and enable Pages
- **Netlify**: Drag and drop the folder or connect a Git repository
- **Vercel**: Connect your Git repository for automatic deployments
- **AWS S3 + CloudFront**: Upload to S3 bucket and configure CloudFront

#### Paid Options:
- **AWS S3 + CloudFront**: Very low cost for static sites
- **Google Cloud Storage**: Similar to AWS S3
- **Azure Static Web Apps**: Free tier available

### Customization

#### Update Contact Email
1. Open `index.html`
2. Find the line: `<a href="mailto:contact@ajdesign.dev">contact@ajdesign.dev</a>`
3. Replace `contact@ajdesign.dev` with your actual email address

#### Form Submission
The contact form currently shows an alert message. To make it functional, you can:

1. **Use a form service** (easiest):
   - [Formspree](https://formspree.io/) - Free tier available
   - [Netlify Forms](https://www.netlify.com/products/forms/) - If hosting on Netlify
   - [EmailJS](https://www.emailjs.com/) - Send emails directly from JavaScript

2. **Add a backend**:
   - Create an API endpoint to handle form submissions
   - Send emails using services like SendGrid, Mailgun, or AWS SES

#### Customize Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #e74c3c;
    --accent-color: #f39c12;
    /* ... */
}
```

## File Structure

```
AJ design website/
├── index.html      # Main HTML file
├── styles.css      # All styling
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Notes

- This is a static website with no backend requirements
- The contact form needs to be connected to a service or backend to actually send emails
- All content can be easily customized by editing the HTML file
- The design is responsive and works on all screen sizes

## Future Enhancements

Consider adding:
- Portfolio/Projects section (when you have completed projects)
- Blog section (for SEO and thought leadership)
- Testimonials section (when you have clients)
- Integration with analytics (Google Analytics, etc.)
- SEO optimization (meta tags, Open Graph, etc.)

## License

This website is for AJ design company use.
