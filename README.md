# TaskFlow - Responsive Landing Page

A clean, modern, and fully responsive SaaS landing page built as part of my frontend development assignment.

## Tech Stack & Framework Choice

- **React (Vite):** Chosen for its fast development server (HMR), component-based architecture, and efficient state management (e.g., managing the mobile navigation toggle with `useState`).
- **CSS3:** Custom CSS with Media Queries for responsive design and precise layout control.

## Project Structure

```text
src/
├── components/
│   ├── Navbar.jsx       # Responsive header with interactive mobile hamburger menu
│   ├── Hero.jsx         # Catchy introduction and call-to-action (CTA)
│   ├── Features.jsx     # Grid layout displaying key product values
│   ├── Pricing.jsx      # Pricing plans presented in a clean card design
│   └── Footer.jsx       # Footer with copyright and links
├── App.jsx              # Main application entry point assembling all components
├── App.css              # Global styles and responsive breakpoints
└── main.jsx             # React DOM rendering