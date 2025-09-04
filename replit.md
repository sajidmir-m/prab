# replit.md

## Overview

This is a personalized birthday greeting webpage for Randeep Kour. It's a single-page HTML application that creates an interactive and animated birthday celebration experience with floating balloons, confetti animations, dummy photo gallery, custom typography, and responsive design. The project is designed as a static web application that can be easily deployed and shared.

## Recent Changes

**September 4, 2025**: 
- Added interactive confetti animations with JavaScript that trigger automatically and on button click
- Created dummy photo gallery with three placeholder image sections featuring gradient backgrounds and decorative icons
- Enhanced cake icon with animated glowing candle effect using CSS keyframes
- Implemented floating balloon animations with staggered timing for better visual appeal

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Single Page Application**: Built as a standalone HTML file with embedded CSS and JavaScript
- **Styling Framework**: Uses Tailwind CSS via CDN for rapid styling and responsive design
- **Typography**: Custom Google Fonts integration (Dancing Script and Quicksand) for personalized aesthetic
- **Animation System**: CSS-based animations for floating balloon effects with staggered timing
- **Layout Strategy**: Responsive design using Tailwind's utility classes for mobile-first approach

### Design Patterns
- **Embedded Styling**: Custom CSS animations and font declarations embedded within the HTML head
- **CDN Dependencies**: External resources loaded via CDN for lightweight deployment
- **Animation Choreography**: Multiple balloon elements with coordinated float animations using CSS keyframes and animation delays

### Technical Decisions
- **No Build Process**: Chosen for simplicity and immediate deployment capability
- **Static Asset Strategy**: All styling and interactivity handled through embedded code and CDN resources
- **Performance Considerations**: Minimal external dependencies (only Tailwind CSS and Google Fonts)

## External Dependencies

### CDN Services
- **Tailwind CSS**: `https://cdn.tailwindcss.com` - CSS framework for styling and responsive design
- **Google Fonts API**: `https://fonts.googleapis.com/css2` - Custom typography (Dancing Script and Quicksand fonts)

### Font Resources
- **Dancing Script**: Decorative cursive font for headings and special text
- **Quicksand**: Clean sans-serif font for body text and readability

Note: This is a completely frontend-focused project with no backend infrastructure, databases, or server-side processing required.