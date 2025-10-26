# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a JavaScript portfolio containing 5 standalone web development projects demonstrating various vanilla JavaScript concepts and techniques. Each project is self-contained in its own directory with HTML, CSS, and JavaScript files.

## Project Structure

Each project follows a consistent structure:
- `index.html` - Main HTML file with inline styles or external CSS references
- `js/app.js` - Main JavaScript application logic
- `css/` - Stylesheets (when present)
- `assets/` or `img/` - Static assets (when present)

### Projects

1. **16-PROYECTO-EnviarEmail** - Email form validation and submission simulator
   - Form validation with real-time feedback
   - Email format validation
   - Submit/reset functionality with loading states

2. **17-PROYECTO-Buscador** - Car search/filter application
   - `js/db.js` contains static car data array
   - Multi-criteria filtering (brand, year, price, doors, transmission, color)
   - Dynamic DOM manipulation for search results

3. **19-PROYECTO-LocalStorage** - Tweet-like application with LocalStorage persistence
   - CRUD operations for tweet-like messages
   - LocalStorage integration for data persistence
   - Dynamic HTML generation

4. **20-PROYECTO-Carrito-LS** - Shopping cart with LocalStorage
   - Add/remove items from cart
   - LocalStorage persistence
   - Dynamic cart total calculation

5. **23-PROYECTO-Prototypes-Seguro** - Insurance quote calculator
   - Constructor functions and prototypes
   - Insurance premium calculation based on car brand, year, and type
   - Demonstrates prototype-based inheritance

## Development Patterns

- **Vanilla JavaScript**: All projects use pure JavaScript without frameworks
- **Event-driven architecture**: Heavy use of `addEventListener` for user interactions
- **LocalStorage integration**: Projects 19 and 20 demonstrate browser storage patterns
- **Form validation**: Real-time validation with visual feedback
- **Dynamic DOM manipulation**: Creating and updating HTML elements programmatically

## Common Code Patterns

- Constructor functions with prototype methods (Project 23)
- Object-based state management (email object in Project 16)
- Array filtering and manipulation for search functionality
- JSON serialization for LocalStorage operations
- Error handling and user feedback systems

## Running Projects

Each project can be run by opening the `index.html` file directly in a web browser. No build process or package manager is required.

## CSS Frameworks Used

- **Tailwind CSS**: Project 16 (email form)
- **Skeleton CSS**: Projects 17 and 19 
- **Custom CSS**: All projects include custom styling

No testing framework, build tools, or package management is configured for this portfolio.