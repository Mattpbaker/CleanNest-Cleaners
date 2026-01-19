# Cleanest Cleaners Landing Page

A beautiful, supportive landing page for Cleanest Cleaners - a cleaning company specialized in serving elderly clients with companionship and specialized care.

## Features

- **Full-screen hero section** with warm, welcoming imagery
- **Editorial-style sections** for "Why Choose Us" and "For Families Who Care"
- **Interactive testimonials carousel** with smooth animations
- **Vertical timeline** for "How It Works" section
- **Unique service cards** with individual styling and hover effects
- **Responsive design** optimized for all devices
- **Warm color palette** matching the hero image tones

## Sections

- Hero section with company branding and CTAs
- Why Choose Cleanest Cleaners (editorial layout)
- For Families Who Care (editorial layout)
- Trusted by Families (testimonials carousel)
- How It Works (5-step timeline)
- Our Services (6 unique service cards)
- Contact form and information

## Tech Stack

- Pure HTML5, CSS3, and vanilla JavaScript
- No dependencies or build process required
- Fully static site ready for deployment

## Deployment

### Vercel Deployment

This project is ready for Vercel deployment:

1. **Connect your GitHub repository** to Vercel:
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Import the `CleanNest-Cleaners` repository

2. **Automatic deployment**:
   - Vercel will automatically detect the static site
   - The `vercel.json` configuration file is included
   - Your site will be live after the first deployment

3. **Custom domain** (optional):
   - Add your custom domain in Vercel project settings
   - Update DNS records as instructed

### Local Development

Simply open `index.html` in a web browser or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## Project Structure

```
CleanestCleaners/
├── index.html          # Main HTML file
├── styles.css          # All styles and responsive design
├── vercel.json         # Vercel deployment configuration
├── .gitignore          # Git ignore rules
└── README.md           # This file
```

## Color Palette

The site uses a warm, earthy color palette inspired by the hero image:
- **Primary Text**: `#16313a` (Dark teal)
- **Accent**: `#a68b5b` (Warm brown/gold)
- **Background**: `#faf8f5` (Warm off-white)
- **Surface**: `#ffffff` (White)
- **Muted Text**: `rgba(22, 49, 58, 0.78)` (Semi-transparent dark teal)

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile responsive (iOS Safari, Chrome Mobile)
- Accessibility features included (reduced motion support)

## License

All rights reserved.
