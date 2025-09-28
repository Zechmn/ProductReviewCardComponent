# Product Preview Card Component

## Overview

This is a Frontend Mentor challenge implementation that showcases a responsive product preview card component for a perfume product. The project demonstrates modern HTML5 and CSS3 techniques to create a clean, responsive card layout that adapts between mobile and desktop viewports. The component features semantic HTML structure, responsive images using the `<picture>` element, and CSS flexbox for layout management.

## Recent Changes

### September 28, 2025
- **CSS Code Quality Improvements**: Comprehensive refactoring to improve maintainability and accessibility
  - Added CSS custom properties for all colors and fonts to reduce code duplication
  - Improved responsive design with relative units (rem) instead of fixed pixels
  - Enhanced accessibility with proper `:focus-visible` styles for keyboard navigation
  - Added intermediate breakpoint for better medium-screen experience
  - Standardized formatting and eliminated inconsistent spacing throughout stylesheet
  - Fixed image layout to span full container height with no bottom padding

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **HTML Structure**: Semantic HTML5 with proper accessibility considerations using `<main>`, `<article>`, and `<picture>` elements
- **CSS Methodology**: Component-based styling with BEM-like naming conventions for maintainable code
- **Responsive Design**: Mobile-first approach using CSS flexbox and responsive images
- **Typography System**: Google Fonts integration with Montserrat and Fraunces font families
- **Layout Strategy**: Card-based component architecture with flexible content areas

### Design System
- **Color Palette**: HSL-based color system with primary green colors and neutral tones
- **Typography Scale**: Defined font weights (500, 700) and standardized font sizing
- **Spacing System**: Consistent use of CSS custom properties for colors and spacing
- **Component Structure**: Self-contained product card with image, content, and interactive elements

### Responsive Strategy
- **Breakpoint Management**: Multiple breakpoints using relative units (40rem, 48rem, 75rem) for fluid responsive behavior
- **Image Optimization**: Responsive images using `<picture>` element with separate mobile/desktop assets
- **Layout Adaptation**: Flexbox-based layout that stacks vertically on mobile and adapts for larger screens
- **Progressive Enhancement**: Enhanced padding and spacing for medium and large screens

### Browser Compatibility
- **CSS Reset**: Universal box-sizing and margin/padding reset for consistent rendering
- **Modern CSS**: Uses HSL colors, flexbox, and CSS3 properties with broad browser support
- **Progressive Enhancement**: Graceful degradation for older browsers

## External Dependencies

### Web Fonts
- **Google Fonts**: Montserrat (weights: 500, 700) and Fraunces (weight: 700) font families
- **Font Display**: Optimized loading with preconnect and display=swap for performance

### Assets
- **Images**: Product images optimized for mobile and desktop viewports
- **Icons**: Inline SVG for cart icon to ensure scalability and performance
- **Favicon**: 32x32 PNG favicon for browser tab identification

### Frontend Mentor Integration
- **Challenge Framework**: Built as a solution to Frontend Mentor's product preview card component challenge
- **Design Assets**: Follows provided style guide with specific color palette and typography requirements