# Nike Frontend Clone

A responsive Nike website clone built as a personal project to practice and demonstrate Tailwind CSS skills. This project focuses purely on styling and responsive design without any backend functionality.

## About

This project is a pixel-perfect recreation of Nike's landing page interface, showcasing modern web development practices and advanced Tailwind CSS techniques. It serves as a demonstration of responsive design principles and component-based architecture.

## Technologies Used

- **React 19** - Modern React with functional components and hooks
- **Vite** - Fast build tool and development server
- **Tailwind CSS 3.4** - Utility-first CSS framework
- **JavaScript ES6+** - Modern JavaScript features

## Features

- Fully responsive design (mobile-first approach)
- Interactive product showcase with image switching
- Customer reviews section
- Newsletter subscription interface
- Product grid with cards
- Services showcase
- Modern hero section with statistics

## Installation and Setup

### Prerequisites

Make sure you have Node.js installed on your machine.

### Running the Project

1. Clone the repository:
```bash
git clone <repository-url>
cd Nike_Frontend_Clone
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

### Build for Production

```bash
npm run build
```

## Tailwind CSS Techniques Used

### Custom Utility Classes

The project extensively uses Tailwind's `@layer` directive to create reusable utility classes:

- **Custom padding classes**: `.padding`, `.padding-x`, `.padding-y` for consistent spacing
- **Typography utilities**: `.info-text` for standardized text styling
- **Container class**: `.max-container` for consistent max-width across sections

### Responsive Design Patterns

- **Mobile-first approach**: Using `sm:`, `md:`, `lg:`, `xl:` prefixes
- **Conditional visibility**: `max-lg:hidden` and `hidden max-lg:block` for responsive navigation
- **Flexible grids**: `grid lg:grid-cols-4 md:grid-cols-3 sm:grid-cols-2 grid-cols-1`
- **Responsive flexbox**: `flex xl:flex-row flex-col` for layout changes

### Advanced Tailwind Features

- **Custom color palette**: Extended color scheme with `coral-red`, `slate-gray`, `pale-blue`
- **Custom fonts**: Integration of Google Fonts (Palanquin and Montserrat)
- **Background utilities**: Custom background images and gradients
- **Shadow utilities**: Custom shadow classes for depth
- **Custom breakpoints**: Added `wide: 1440px` breakpoint

### Component Styling Techniques

- **Dynamic classes**: Conditional styling using template literals
- **State-based styling**: Active states with conditional border colors
- **Hover effects**: Interactive elements with hover transitions
- **Card components**: Consistent card styling across different sections

### Layout Techniques

- **CSS Grid**: Product grids and flexible layouts
- **Flexbox**: Navigation, hero section, and component alignment
- **Absolute positioning**: Overlay elements and floating components
- **Z-index management**: Layering for navigation and hero elements

### Typography and Spacing

- **Custom font sizes**: Extended font-size scale from `xs` to `8xl`
- **Line height control**: Precise typography with custom leading values
- **Consistent spacing**: Systematic use of padding and margin utilities
- **Text color variations**: Semantic color naming for better maintainability

## Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── Button.jsx
│   ├── Nav.jsx
│   ├── ServiceCard.jsx
│   ├── PopularProductCard.jsx
│   └── ...
├── sections/           # Page sections
│   ├── Hero.jsx
│   ├── PopularProducts.jsx
│   ├── Services.jsx
│   └── ...
├── assets/            # Static assets
│   ├── images/
│   └── icons/
├── constants/         # Data and configuration
└── index.css         # Global styles and Tailwind imports
```

## Key Learning Outcomes

Through this project, I practiced and implemented:

- **Responsive Design**: Mobile-first approach with breakpoint-specific styling
- **Component Architecture**: Reusable components with props-based styling
- **CSS Grid and Flexbox**: Modern layout techniques
- **Tailwind Configuration**: Custom theme extensions and utility classes
- **State Management**: React hooks for interactive components
- **Modern React**: Functional components with hooks
- **Build Tools**: Vite configuration and optimization

## Browser Support

This project supports all modern browsers including:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance Optimizations

- Vite's hot module replacement for fast development
- Optimized Tailwind CSS with purging unused styles
- Responsive images with proper sizing
- Minimal JavaScript bundle size

This project demonstrates proficiency in modern frontend development practices, responsive design principles, and advanced Tailwind CSS usage patterns.