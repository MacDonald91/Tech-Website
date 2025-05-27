# Tech Website

## Overview

Welcome to the repository for my personal tech website! This project serves as a central hub for showcasing my portfolio, sharing my insights on technology, and providing a way for others to connect with me. It's built using standard web technologies: HTML for structure, CSS for styling, and vanilla JavaScript for interactivity.

---

## Features

* **Multi-page Layout:** Organized content across `index.html`, `products.html`, and `tech.html`.
* **Portfolio Showcase:** (Presuming `products.html` or `tech.html` serves this purpose) A section to display projects or technical insights.
* **Responsive Design:** Styled with CSS to ensure a good user experience across desktops, tablets, and mobile devices.
* **Interactive Elements:** Basic JavaScript for dynamic behaviors (e.g., navigation toggles, simple animations).
* **Modern Aesthetics:** Utilizes CSS gradients for text and background effects, and includes smooth hover transitions.

---

## Technologies Used

* **HTML5:** For structuring the content of all pages (`index.html`, `products.html`, `tech.html`).
* **CSS3:** For styling the entire website (`styles.css`), including Flexbox, CSS Grid, and media queries for responsiveness.
* **JavaScript (ES6+):** For adding interactivity and dynamic features (`app.js`).
* **Font Awesome:** For scalable vector icons.
* **Google Fonts (Kumbh Sans):** For custom typography.

---

## Getting Started

To view this project locally, simply open the HTML files in your web browser.

### Prerequisites

* A modern web browser (e.g., Chrome, Firefox, Edge, Safari).

### Viewing the Project

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    cd HTML-CSS-WEBSITE-V!-YT
    ```
    *(Replace `https://github.com/your-username/your-repository-name.git` with the actual URL of your GitHub repository once you create it.)*

2.  **Open `index.html`:**
    Navigate to the `HTML-CSS-WEBSITE-V!-YT` folder and double-click `index.html` (or `products.html`, `tech.html`) to open it in your default web browser.

---

## Issues Faced and Troubleshooting with Gemini

Developing this website came with its share of challenges, and I often turned to Gemini for help in troubleshooting and understanding complex concepts. Here are a few key issues we worked through:

* **Responsive Image Sizing in CSS:**
    * **Issue:** I struggled to make images (`<img>` tags) scale correctly across different screen sizes without distorting or overflowing their containers. Images would sometimes look too large on mobile or too small on desktop, or they would break the layout.
    * **Troubleshooting with Gemini:** Gemini helped me understand the fundamental CSS properties for responsive images. We focused on `max-width: 100%;` and `height: auto;` applied directly to the `<img>` tags. This ensures that images never exceed the width of their parent container while maintaining their aspect ratio. We also discussed using the `<picture>` element and `srcset` attribute for serving different image resolutions, though the primary focus was on basic CSS responsiveness.
* **Structuring Multi-Page Navigation with JavaScript:**
    * **Issue:** As the project grew with multiple HTML pages (`index.html`, `products.html`, `tech.html`), managing navigation links and potentially highlighting the active page became cumbersome. I also faced challenges with common header/footer elements across pages.
    * **Troubleshooting with Gemini:** Gemini guided me on how to effectively link between static HTML pages. For JavaScript-based navigation (like a hamburger menu on mobile), we explored event listeners (`addEventListener`) for toggling classes (e.g., `active` or `open`) on navigation elements in `app.js`. For highlighting active pages, we discussed using simple JavaScript to check `window.location.pathname` against the page's URL and then applying a specific CSS class to the corresponding navigation link. We also touched upon the idea of including common HTML snippets (like headers/footers) across pages, though for a pure static site, this often involves copy-pasting or build tools if it becomes too repetitive.
* **CSS Specificity and Cascading Conflicts:**
    * **Issue:** I often found that my CSS rules weren't applying as expected, or that one rule was overriding another in an unintended way. This made debugging styles difficult.
    * **Troubleshooting with Gemini:** Gemini helped me understand CSS specificity (ID > Class > Element) and the cascading nature of stylesheets. We went through examples of how to correctly target elements using selectors, and how to use the browser's developer tools (Inspect Element) to identify which rules were being applied and why. This fundamental understanding significantly improved my ability to write predictable and maintainable CSS. We also discussed the importance of organizing `styles.css` logically to minimize conflicts.

---

## Contributing

As this is a personal project, direct contributions are not actively sought at the moment. However, if you find any issues or have suggestions, feel free to open an issue in this repository.

---

## Copyright

© 2025 MacDonaldIndustries. All Rights Reserved.

---

## Contact

* **Your Name:** Alasdair MacDonald
* **LinkedIn:** [Alasdair MacDonald's LinkedIn](http://www.linkedin.com/in/alasdair-macdonald-60b178326)
* **GitHub Project:** [Link to your GitHub Repository](https://github.com/your-username/HTML-CSS-WEBSITE-V!-YT) *(Remember to update this with your actual GitHub repo URL once created)*


---

## Acknowledgements

* Gemini AI for invaluable troubleshooting and guidance throughout the development process.
