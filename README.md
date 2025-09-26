# Sweet-Delight-Bakery-OG

#project overview
Sweet Delights Bakery is the name. Founded in 2024, Sweet Delights Bakery is a family-run bakery. It serves both walk-in clients and custom cake orders, specializing in artisanal bread, cakes, and pastries. 

 Mission: To provide freshly baked goods that are lovingly prepared using premium ingredients. 
vision: To be the premier neighbourhood bakery renowned for its inventiveness and client satisfaction.  
Target audience: Online shoppers, event planners, and locals. 

#part 2: desigh and Responsiveness
This phase of the project is focused on the visual appeal and user exprience of the website. major improvement and implementation included:

style sheet external: a fresh, outward look. To ensure a consistent look and feel throughout the website, a CSS file was made and linked to every HTML page.
CSS design:
*typograghy- To improve readability, unique typography styles were used for links, body text and headlines.
*layout-CSS a flexable , modarate layout that arranges content was made using grid and flexbox. efficiently across a range of screen sizes.
 
#Responsive design
#Screenshots:
#Desktop view:
<img width="1361" height="894" alt="Image" src="https://github.com/user-attachments/assets/0db47117-ba72-4580-9493-fe87d1b2dd11" />

<img width="1365" height="885" alt="Image" src="https://github.com/user-attachments/assets/df351219-9aa9-4f54-8067-d7f65eec23a1" />

<img width="1358" height="896" alt="Image" src="https://github.com/user-attachments/assets/3fb727d0-aebd-42e8-8b46-cca44b9e482f" /> 
#mobile view:
breakpoint:to ensure that the layout changes fluidly across desktop,tablet, and mobile devices,media queries were used to establish important breakpoints.
relative units:to ensure proportinality across various screens, relative units such as rem and percentage were utilized for font widths and sizes.
responsive images: the hero images on the webpage is now a CSS backgroun, which takes care of responsiveness on its own.


<img width="289" height="590" alt="Image" src="https://github.com/user-attachments/assets/de24ac99-23a9-4692-a970-d9fbe9555eed" />

<img width="279" height="586" alt="Image" src="https://github.com/user-attachments/assets/79984e33-a741-4bf1-a7a3-0b636209ccc3" />

#changelog
1. Stylesheet & Base Setup
Created external stylesheet style.css and linked it across all pages.
Defined base styles with consistent fonts (Poppins for body text, Playfair Display for headings).
Applied global reset (margin: 0; padding: 0; box-sizing: border-box;).
Chose bakery brand colours → pastel pink (#d87b7b), cream (#fff8f0), chocolate brown (#3a2e2e).
2. Typography
Applied hierarchy to headings (h1, h2, h3) using rem units.
Improved readability with increased line-height and letter-spacing.
Styled buttons and links with uppercase text, hover colour changes, and consistent font weight.
3. Layout Improvements
Used Flexbox for navigation bar and footer alignment.
Applied CSS Grid on the menu page → displays products in responsive cards.
Added padding and spacing to improve readability and balance.
4. Visual Styles
Introduced pastel backgrounds, shadows, and rounded corners for menu cards.
Added hover animations on cards, links, and buttons for interactivity.
Designed call-to-action buttons (e.g., Order Now) with accent colours.
5. Responsive Design
Added media queries for key breakpoints:
Desktop → 3-column product grid.
Tablet → 2-column grid.
Mobile → 1-column layout with stacked navigation.
Used relative units (rem, %) for flexible scaling of text and images.
6. Images & Accessibility
Added descriptive alt text to all bakery product images.
Implemented srcset and sizes for responsive image loading.
Ensured images auto-scale (width: 100%; height: auto;) to fit all screens.
7. Testing & Iteration
Tested across Chrome, Firefox, and Edge developer tools.
Verified responsiveness on desktop, tablet, and mobile.
Adjusted button sizes, spacing, and text readability for small screens.
Documented testing with screenshots (see /screenshots/ folder).

#File structure

sweet-delights-bakery/
│
├── index.html          # Home page
├── about.html          # About Us page
├── menu.html           # Menu page
├── contact.html        # Contact page
│
├── css/
│   └── style.css       # Main stylesheet
│
├── js/
│   └── script.js       # JavaScript for interactivity 
│
├── images/
│   ├── logo.png        # Bakery logo
│   ├── hero.jpg        # Hero banner image
│   └── products/       # Folder for menu item images
│
└── assets/
    └── fonts/          # Custom or external fonts

#Technologies used
HTMLS-for the websites structures
CSSs-for layout,styling,and mobile responsiveness

#How to view the website
To view the website ,open any of the HTML files (e.g index.html) in your web browser.

#Author
Name- Mathomu KF (ST10437796)
Module: Web development.



