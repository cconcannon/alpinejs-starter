# AlpineJS Starter

This is a starter repo for building web pages out of plain old HTML, JavaScript, and CSS. There's no build process and there are no external dependencies. The `elements.html` page provides examples of the kinds of elements that can be built using the vendored [AlpineJS](https://alpinejs.dev/) and [Tailwind CSS](https://tailwindcss.com/) frameworks.

The repo serves as a very quick and easy launch point to build and deploy a static single-page site on Github Pages in minutes with the help of an agentic coding tool. There's enough context already here, and modern LLM's are sufficiently knowledgeable in their training corpus for the LLM to make informed decisions about using HTML, AlpineJS, and Tailwind CSS for element layout, styling, and reactivity.

## Instructions

1. clone this repo or copy the contents
2. edit `index.html` and vibe code something beautiful
3. push to Github and configure repo settings to publish a page from the main branch root folder

## Files

### `elements.html`
The main demonstration page containing examples of all AlpineJS features:
- **x-data**: Reactive data management
- **x-on/@click**: Event handling (click, double-click, hover)
- **x-text**: Dynamic text content
- **x-show**: Conditional visibility
- **x-model**: Two-way data binding for forms
- **x-for**: List rendering with filtering
- **Advanced features**: Computed properties, dropdowns, tabs, modals, image gallery, and form validation

### `alpine.js`
The AlpineJS framework (v3.x) - downloaded locally from CDN for offline development.

### `tailwind.js`
Tailwind CSS browser version (v4) - provides utility-first CSS styling without requiring a build process.

## Features Demonstrated

### Basic Reactivity
- Counter with increment/decrement/reset buttons
- Dynamic message display

### Event Handling
- Click, double-click, and hover events
- Event tracking and display

### Form Controls
- Text inputs with live preview
- Email validation
- Color picker
- Range slider
- Checkboxes and radio buttons

### Dynamic Lists
- Todo list with add/remove functionality
- Search/filter capability
- Checkbox state management

### UI Components
- Dropdown menu with click-outside detection
- Tab navigation
- Modal dialogs
- Image gallery with lightbox
- Shopping cart with computed totals
- Form with validation

## Technologies

- **AlpineJS 3.x**: Lightweight reactive framework
- **Tailwind CSS 4**: Utility-first CSS framework (browser version)
- **No build tools required**: Everything runs directly in the browser

## Browser Compatibility

Works in all modern browsers that support ES6+ JavaScript features.

## License

This is a starter/demo project intended for learning purposes.