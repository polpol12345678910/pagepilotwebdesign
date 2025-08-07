# WalkerMade - Local Web Design Service

## Overview

WalkerMade is a modern, green-themed website for a local web design service that helps small businesses get online. Built with vanilla HTML, CSS, and JavaScript, it features a clean design with soft textures, background shapes, icons, and subtle animations. The site emphasizes friendly, local service with honest messaging and transparent pricing.

## User Preferences

Preferred communication style: Simple, everyday language.
Design preferences: Green color palette (greens, greys, white), clean modern layout with personality, soft textures and background shapes, hover effects and gentle animations, mobile-friendly design.

## System Architecture

This is a client-side only static website with no backend services. The architecture follows a simple three-tier frontend structure:

1. **Structure Layer (HTML)**: Semantic HTML5 markup with multi-page structure - separate pages for Home, About, Pricing, and Contact
2. **Presentation Layer (CSS)**: Modern CSS with green color palette, background shapes, textures, and subtle animations
3. **Behavior Layer (JavaScript)**: Vanilla JavaScript for interactive features and form handling

## Key Components

### Frontend Architecture
- **Multi-Page Design**: Separate HTML files for Home (index.html), About (about.html), Pricing (pricing.html), and Contact (contact.html)
- **Green Theme CSS**: Custom CSS using CSS custom properties for green color palette (primary: #059669, accent: #10b981)
- **Vanilla JavaScript**: Pure JavaScript for DOM manipulation, animations, and form interactions

### Design System
- **Typography**: Inter font family from Google Fonts
- **Icons**: Font Awesome 6.4.0 with palette icon for branding
- **Color Scheme**: Green-themed palette (greens, greys, white) with CSS custom properties
- **Visual Elements**: Background shapes, soft textures, hover effects, and gentle animations
- **Responsive Design**: Mobile-first approach with hamburger navigation

### Content Structure
- **Hero Section**: "Professional websites made simple" tagline with crafted messaging
- **About Section**: Personal story with founder quote and feature list
- **Pricing Section**: Four-tier pricing including Custom plan (Basic £200, Standard £450, Premium £700, Custom "Let's Talk")
- **Contact Section**: Email contact at hello@walkermade.co.uk with Tally form integration

### Interactive Features
- **Mobile Navigation**: Hamburger menu with toggle functionality
- **Multi-Page Navigation**: Direct navigation between separate HTML pages
- **Dynamic Navbar**: Background changes on scroll
- **Hover Effects**: Gentle animations on cards and buttons
- **Contact Form**: Supports both local validation and external form services

### File Structure
- **index.html**: Homepage with hero section and introductory content
- **about.html**: About page with company story, founder quote, and feature list
- **pricing.html**: Pricing page with three-tier package structure and detailed features
- **contact.html**: Contact page with form and business contact information
- **styles.css**: Shared CSS file with green theme and responsive design
- **script.js**: JavaScript file for navigation, form handling, and interactions

## Data Flow

Since this is a static website, data flow is minimal:

1. **User Interactions**: Click events trigger JavaScript functions
2. **Navigation**: Smooth scrolling to page sections via anchor links
3. **Form Data**: Contact form appears to collect user information (backend integration needed)
4. **Visual Feedback**: CSS transitions and JavaScript provide immediate UI responses

## External Dependencies

### CDN Resources
- **Google Fonts**: Inter font family for typography
- **Font Awesome**: Version 6.4.0 for icons via CDN

### No Backend Dependencies
- No database connections
- No server-side processing
- No API integrations currently implemented

## Deployment Strategy

### Current State
- **Static Hosting Ready**: Can be deployed to any static hosting service
- **No Build Process**: Direct deployment of HTML/CSS/JS files
- **CDN Dependent**: Relies on external CDNs for fonts and icons

### Recommended Hosting Options
- GitHub Pages
- Netlify
- Vercel
- Traditional web hosting
- AWS S3 static hosting

### Recent Changes (August 2025)
- **Complete Rebranding**: Changed from PagePilot to WalkerMade with walkermade.co.uk domain
- **SEO Optimization**: Updated all page titles to "WalkerMade | Web Design & Branding"
- **Meta Tags**: Added consistent meta descriptions and Open Graph tags across all pages
- **Hero Content**: Updated main heading to "Web Design for Small Businesses, Built in the UK"
- **Messaging Update**: Removed aviation-themed content ("take off", plane icons) in favor of professional web design messaging
- **Contact Integration**: Updated email to hello@walkermade.co.uk with Tally form popup
- **Pricing Expansion**: Added fourth "Custom" pricing tier for bespoke projects
- **Icon Update**: Changed from plane-departure to palette, then to laptop-code icon throughout site for better web design representation
- **Mobile Optimization**: Fixed text width issues on mobile devices for better readability

### Future Considerations
- **Contact Form**: Currently uses Tally form integration for quote requests
- **Performance**: Consider bundling and minification for production
- **SEO**: Meta tags updated, consider structured data and sitemap
- **Analytics**: Integration with Google Analytics or similar tracking

### Development Notes
- All styling uses modern CSS features (custom properties, flexbox)
- Mobile-responsive design implemented
- Cross-browser compatibility considerations present
- Brand consistency maintained across all four pages