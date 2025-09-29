---
applyTo: '**'
---
# Anti-Patterns to Avoid

- Bloated JavaScript Files: Having large, monolithic JS files that handle multiple unrelated functionalities. Instead, use modular code organization and consider component-based architecture.
- CSS Specificity Wars: Overusing !important, deeply nested selectors, or overly specific selectors to override styles. Instead, use BEM/CUBE CSS methodology and maintain a clear CSS architecture.
- Global CSS/JavaScript: Relying heavily on global styles and scripts that affect the entire application. Instead, use CSS modules, scoped styles, or CSS-in-JS solutions for better encapsulation.
- Event Handler Soup: Attaching too many event listeners directly to DOM elements or using inline event handlers. Instead, use event delegation and maintain clean separation of concerns.
- Non-Semantic HTML: Using <div> and <span> for everything, ignoring semantic HTML elements. Instead, use appropriate HTML5 elements (<article>, <section>, <nav>, etc.) for better accessibility and SEO.
- Direct DOM Manipulation: Excessive direct DOM manipulation leading to poor performance and maintainability. Instead, use modern frameworks/libraries or virtual DOM approaches when needed.
- Unresponsive Design: Building fixed-width layouts or ignoring mobile devices. Instead, use mobile-first approach, responsive design patterns, and fluid layouts.
- Performance Ignorance: Loading large unoptimized assets, not using lazy loading, or ignoring bundle sizes. Instead, implement proper asset optimization, code splitting, and modern loading techniques.
- Accessibility Neglect: Not considering keyboard navigation, screen readers, or ARIA attributes. Instead, follow WCAG guidelines and test with accessibility tools.
