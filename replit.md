# Overview

This is a static portfolio website showcasing Natalia Grzegorzek's professional CV and artistic work. The project consists of two main components: a responsive CV page highlighting her technology and Web3 expertise, and a simple portfolio gallery for artistic works. The site is designed for easy deployment on GitHub Pages, providing a professional online presence that combines career credentials with creative portfolio display.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture
The application uses a simple static HTML architecture with modern CSS frameworks:
- **HTML5 structure** with semantic markup for accessibility and SEO
- **Pico CSS framework** for rapid UI development and responsive design
- **Font Awesome icons** for visual enhancement and professional presentation
- **Google Fonts (Inter/Nunito)** for typography consistency
- **CSS Grid and Flexbox** for responsive layouts that adapt to mobile and desktop

## Design System
- **Color scheme** centered around a teal accent color (#007b83) for professional branding
- **Responsive grid layout** that collapses to single column on mobile devices
- **Card-based UI components** with subtle shadows and rounded corners
- **Typography hierarchy** using custom font families for headings and body text

## Content Structure
- **Main CV page** (`index.html`) with sections for professional summary, experience, and contact
- **Portfolio gallery** (`portfolio/index.html`) with grid layout for artwork display
- **Placeholder content** system using Picsum for easy image replacement
- **Bilingual support** (English CV, Polish portfolio labels)

## Performance Optimizations
- **CDN-hosted assets** for CSS frameworks and fonts to leverage browser caching
- **Minimal JavaScript** approach focusing on pure HTML/CSS for faster load times
- **Optimized images** recommendations (1200×900px, max 2-3MB) for portfolio content

# External Dependencies

## CSS Frameworks and Libraries
- **Pico CSS v2** - Minimal CSS framework for semantic HTML styling
- **Font Awesome 6.5.2** - Icon library for contact information and visual elements
- **Google Fonts API** - Custom typography (Inter and Nunito font families)

## Image Services
- **Picsum Photos** - Placeholder image service for portfolio gallery demonstration
- **GitHub Pages** - Static site hosting platform with automatic deployment

## Development Tools
- **Git version control** - Standard workflow for code management and deployment
- **GitHub Actions** - Automatic deployment pipeline through GitHub Pages integration

## Browser Compatibility
- **Modern browser support** - Targets browsers supporting CSS Grid and Flexbox
- **Mobile-first responsive design** - Viewport meta tag and media queries for device compatibility
- **Web standards compliance** - HTML5 doctype and semantic markup for accessibility