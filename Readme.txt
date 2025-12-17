Personal Portfolio Website - Param Sharma

Overview
This is the personal portfolio website of Param Sharma, built using HTML5 and CSS3

The portfolio contains 4 pages:
- Home – Introduction and navigation
- About Me – Personal introduction, photo, and video
- Projects – Project showcase with multiple entries
- Contact – Contact form with validation rules

The site is responsive, modern in design, and uses a global background image with content boxes for readability.

Site Structure
- index.html – Home page  
- about.html – About Me page with image and embedded video  
- projects.html – Project portfolio (5 placeholder projects)  
- contact.html – Contact form with input validation  
- style.css – Stylesheet with modern design, gradients, and media queries  
- background-website.jpg – Background image used across all pages  

Design Details

Viewport Sizes (Media Queries)
I used 3 responsive breakpoints:
- Mobile: up to 600px (stacked navigation, smaller fonts, tighter padding)  
- Tablet: 601px – 900px (medium font sizes, moderate spacing)  
- Laptop/Desktop: 901px and above (larger text, wider layout)  

Gradients
- Buttons use a linear gradient for a modern look:  
  css
  background: linear-gradient(135deg, #3182ce, #2b6cb0);

Color Scheme

Dark Navy (`#1a202c`) for header/footer
Light Gray-Blue (`#f0f4f8`, `#d9e2ec`) for backgrounds
White (`#ffffff`) for content boxes
Blue (`#3182ce`, `#2b6cb0`) for buttons and highlights

Background

A global background image `background-website.jpg` is applied to every page.
Content boxes (`section`, `article`, `form`) use semi-transparent white backgrounds to keep text readable.

Features

Responsive navigation
About Me page with photo + video (45–60s placeholder video)
Projects page with multiple entries
Contact form with validation:

 Name required
 Email must be valid format
 Phone must be 10 digits (`pattern="[0-9]{10}"`)
 Comments required
Sticky footer with email & copyright
Modern styling (shadows, hover effects, transitions)


Validation and Testing

All validation checks were performed and passed:

HTML Validation with [W3C Markup Validator](http://validator.w3.org/)
CSS Validation with [W3C CSS Validator](http://jigsaw.w3.org/css-validator/)
Link Checker with [W3C Link Checker](http://validator.w3.org/checklink)
Spell Check – no errors found
Accessibility tested with [WAVE](http://wave.webaim.org/)

Author

Param Sharma
Email: [theparamsharma@gmail.com]




