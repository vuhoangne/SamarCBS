Samar Agency Website
Overview
This project is a responsive, modern website for Samar Agency, a fictional digital services company. The website showcases the agency's services, portfolio, blog, and contact information. It is built using HTML, CSS, and JavaScript, with various libraries and frameworks to enhance functionality and user experience.
Features

Responsive Design: Optimized for desktop, tablet, and mobile devices.
Interactive Carousel: Displays key services with animations and a call-to-action button.
Portfolio Section: Showcases recent projects with a lightbox gallery using Fancybox.
Blog Section: Highlights latest news with an Owl Carousel for smooth navigation.
Animated Elements: Uses Animate.css and WOW.js for engaging animations.
Back-to-Top Button: Smooth scrolling to the top of the page.
Newsletter Signup: A form for users to subscribe to updates.
Social Media Integration: Links to social media profiles in the footer.

Technologies Used

HTML5: Structure of the website.
CSS3: Styling, including custom animations and gradient effects.
JavaScript: Interactivity and dynamic content.
jQuery: Simplifies DOM manipulation and event handling.
External Libraries:
FontAwesome (6.2.0): Icons for navigation and footer.
Line Awesome: Additional icons for lists and features.
Flaticon: Custom icons for services and features.
Google Fonts (Roboto): Typography.
Fancybox (5.0): Lightbox for portfolio images.
Owl Carousel: Blog post slider.
Animate.css (4.1.1): CSS animations.
WOW.js: Triggers animations on scroll.
CountUp.js: Animated counters for statistics.
jQuery Waypoints: Triggers animations when elements enter the viewport.



File Structure
samar-agency/
├── css/
│   ├── flaticon/
│   │   └── flaticon.css
│   ├── owl.carousel.min.css
│   ├── owl.theme.default.min.css
│   └── style.css
├── img/
│   ├── logo.png
│   ├── logo-2.png
│   ├── logo-white.png
│   ├── pic1.jpg
│   ├── pic1_1.jpg
│   ├── ... (other images)
│   ├── bg2.png
│   ├── bg4.png
│   ├── bg14.png
│   ├── bg15.png
│   ├── bg17.png
│   ├── pattern2.png
│   ├── pattern3.png
│   └── br.png
├── js/
│   ├── owl.carousel.min.js
│   ├── countUp/
│   │   └── jquery.countup.js
│   ├── back-to-top/
│   │   ├── assets/
│   │   │   ├── js/
│   │   │   │   ├── main.js
│   │   │   │   └── util.js
├── index.html
└── README.md

Installation

Clone or Download: Clone this repository or download the ZIP file.
Extract Files: Unzip the project folder if downloaded.
Serve the Website:
Use a local server (e.g., VS Code Live Server, XAMPP, or Node.js http-server).
Alternatively, open index.html directly in a browser (note: some features may not work due to local file restrictions).


Ensure Internet Connection: The website relies on CDN-hosted libraries (e.g., jQuery, FontAwesome).

Usage

Navigation: Use the header menu to navigate to different sections (Home, Services, Blog, etc.).
Portfolio: Click the plus icon on portfolio images to view them in a lightbox.
Blog Slider: The blog section uses Owl Carousel for sliding through posts.
Newsletter: Enter an email address in the footer form to simulate subscribing (form is not functional without a backend).
Back-to-Top: Click the arrow button in the bottom-right corner to scroll to the top.

Customization

Images: Replace images in the img/ folder with your own (maintain filenames or update HTML/CSS references).
Colors: Modify the gradient colors in style.css (search for #f55f8d and #f8ae56).
Content: Update text in index.html for services, portfolio, blog, etc.
Fonts: Change the Google Font in the <head> section or add new fonts.
Animations: Adjust WOW.js and Animate.css classes in index.html or modify keyframes in style.css.

Notes

The website assumes all images and assets are in the correct img/ and css/ folders.
Some animations (e.g., counters, WOW.js) require scrolling to trigger.
The newsletter form is static and requires a backend for functionality.
Ensure CDN links are accessible; if offline, download and host libraries locally.

Credits

Author: Le Nguyen Vu Hoang
Course: Homework - Samar - CyberSoft
Assets: Images and icons from Flaticon, FontAwesome, and Line Awesome.
Libraries: jQuery, Fancybox, Owl Carousel, Animate.css, WOW.js, CountUp.js.

License
Copyright © 2025 HomeworkCBS. All rights reserved.
