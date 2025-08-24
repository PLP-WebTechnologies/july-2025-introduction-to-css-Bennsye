🧩 Week 4 Assignment: CSS Layouts & Responsive Web Design
Overview
This project is a responsive multi-section webpage built to demonstrate proficiency in modern CSS layout techniques, specifically Flexbox and CSS Grid. The layout is designed to adapt gracefully across different screen sizes, providing an optimal user experience on desktop, tablet, and mobile devices.

Features
Responsive Design: The layout adjusts seamlessly to various screen sizes using media queries.

CSS Grid: The main content area, which includes the primary content and a sidebar, is structured using CSS Grid for a robust two-dimensional layout.

Flexbox: The header and the section containing the cards are laid out using Flexbox to ensure flexible alignment and spacing.

Clean and Maintainable Code: Both index.html and style.css are well-structured and include detailed comments on every line to explain the purpose of each element and rule.

Project Structure
index.html: Contains the complete HTML5 structure of the webpage, including a header, navigation, main content, and footer.

style.css: Contains all the CSS rules, including global styles, Flexbox and Grid layouts, and responsive design breakpoints for mobile and tablet views.

How to View the Project
To view the project, simply open the index.html file in your web browser.

To see the responsiveness in action, resize your browser window to observe how the layout changes:

Desktop View: The main content and sidebar are displayed side-by-side.

Tablet View: The main content and sidebar stack vertically.

Mobile View: The navigation links and cards stack vertically, and the font size is adjusted for better readability.

Code Highlights
index.html
Header: The <header> element and its navigation (<nav>) are designed with Flexbox.

Main Content: The <main> element with the class grid-container is the primary example of CSS Grid.

Cards: The card-container <div> demonstrates Flexbox for aligning and wrapping elements.

style.css
header section: The display: flex; rule aligns the title and navigation links.

.grid-container section: The display: grid; and grid-template-columns: 2fr 1fr; rules create the two-column layout.

@media queries: Breakpoints are set at 768px (for tablets) and 480px (for mobile) to change the layout from columns to a single-column stack.
