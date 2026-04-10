# iOS Club Landing Page

A modern, Apple-inspired landing page for the iOS Club — a student community focused on building real iOS apps and shipping them to the App Store.

## Project Description

This project is a responsive landing page designed to attract college students interested in iOS development. The page features a sleek dark theme with Apple-inspired design elements, including custom cursors, animated backgrounds, and smooth scroll interactions. It serves as both an informational hub and a registration portal for the iOS Club.

The landing page showcases the club's activities, member projects, team information, upcoming events, and provides a streamlined registration process for new members.

## Features

- **Responsive Design**: Fully responsive layout that works across desktop, tablet, and mobile devices
- **Interactive Elements**:
  - Custom animated cursor with hover effects
  - Particle-based background animation using Canvas API
  - Smooth scroll reveal animations
  - Animated statistics counters
  - Mobile hamburger menu
  - FAQ accordion
  - Back-to-top button

- **Content Sections**:
  - Hero section with club branding and call-to-action
  - About section highlighting club activities and technologies
  - Project showcase featuring member-built apps
  - Member testimonials carousel
  - Team member profiles
  - Upcoming events calendar
  - Comprehensive FAQ section
  - Registration form with validation

- **Registration System**: Interactive form that collects member information and provides instant feedback
- **Navigation**: Sticky navigation with active section highlighting
- **Accessibility**: Proper ARIA labels and keyboard navigation support

## Setup Instructions

Since this is a static website, no complex setup is required:

1. **Clone or download** the project files to your local machine
2. **Open** `landing_page.html` in any modern web browser
3. The page will load with all interactive features enabled

### Browser Requirements
- Modern browsers with ES6+ support
- Canvas API support for background animations
- Intersection Observer API for scroll animations
- CSS Grid and Flexbox support

### Optional: Local Development Server
For a more realistic development experience, you can serve the files using a local server:

```bash
# Using Python (if installed)
python -m http.server 8000

# Using Node.js (if installed)
npx serve .

# Then open http://localhost:8000/landing_page.html
```

## Tech Stack Used

- **HTML5**: Semantic markup and accessibility features
- **CSS3**: 
  - Custom properties (CSS variables) for theming
  - Flexbox and CSS Grid for layouts
  - CSS animations and transitions
  - Backdrop filters and blend modes
  - Responsive design with media queries

- **Vanilla JavaScript (ES6+)**:
  - Canvas API for particle animations
  - Intersection Observer for scroll-triggered animations
  - DOM manipulation for interactive elements
  - Event handling for user interactions
  - Form validation and submission handling

### Fonts Used
- SF Pro Display (Apple's system font)
- JetBrains Mono (monospace font for code elements)
- Instrument Serif (decorative serif font)

### Design Inspiration
- Apple.com design language
- Dark mode aesthetics
- Minimalist UI with subtle animations
- iOS/macOS design patterns