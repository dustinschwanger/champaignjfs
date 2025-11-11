# Champaign County Department of Job & Family Services Website

This is the official website for Champaign County Department of Job & Family Services, providing information and resources for residents of Champaign County, Ohio.

## Features

- **WCAG 2.2 AA Compliant**: Fully accessible website meeting international accessibility standards
- **Responsive Design**: Mobile-friendly layout that works on all devices
- **USWDS Framework**: Built using the U.S. Web Design System for consistency and accessibility
- **Interactive Chat Widget**: Help users find information quickly
- **Service Information**: Comprehensive details about all DJFS services
- **Contact Information**: Easy access to office locations, hours, and contact methods

## Accessibility Features

This website has been designed to be 100% WCAG 2.2 Level AA compliant:

- Keyboard navigation support
- Screen reader compatibility
- Focus management and visual focus indicators
- Proper ARIA labels and roles
- Color contrast ratios meeting WCAG standards
- Touch target sizes meeting WCAG 2.2 requirements (44x44px minimum)
- Reduced motion support
- Text spacing customization support

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **CSS Framework**: USWDS 3.7.1
- **Icons**: Font Awesome 6.4.0
- **Server**: Node.js with Express

## Local Development

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```
4. Open your browser to `http://localhost:3000`

## Deployment to Railway

This site is configured for easy deployment on Railway:

1. Push your code to GitHub
2. Connect your GitHub repository to Railway
3. Railway will automatically detect the Node.js project and deploy it
4. The site will be available at your Railway-provided URL

### Environment Variables

No environment variables are required for basic operation.

## Project Structure

```
.
├── index.html          # Main homepage
├── styles.css          # Custom styles
├── server.js           # Express server for production
├── package.json        # Node.js dependencies
├── public/             # Public assets (images)
│   ├── adoption.png
│   ├── child-care.jpg
│   ├── child-protective.png
│   ├── child-support.png
│   ├── food-assistance.jpg
│   ├── job.png
│   ├── medicaid.jpg
│   └── workforce.png
├── hero.png           # Hero section background
├── logo.png           # Site logo
└── favicon_1.ico      # Favicon
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contact

**Champaign County Department of Job & Family Services**
- Address: 1512 S. US Highway 68, Suite N100, Urbana, OH 43078
- Phone: (937) 484-1500
- Toll-Free: 1-800-837-4290
- Email: CHAMPAIGN_COUNTY_JFS@jfs.ohio.gov
- Hours: Monday-Friday, 8:00 AM – 4:30 PM

## License

© 2025 Champaign County Department of Job & Family Services. All rights reserved.
