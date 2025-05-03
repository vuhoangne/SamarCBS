# Samar - Creative Agency Website

## 📌 Overview

**Samar** is a modern, responsive website template designed for a creative agency. It showcases services, portfolios, blogs, and more with a visually appealing design, animations, and interactive elements. The template uses **HTML**, **CSS**, and **JavaScript**, along with various libraries to enhance functionality and user experience.

## ✨ Features

- **Responsive Design**: Adapts seamlessly to various screen sizes (desktop, tablet, mobile).
- **Interactive Animations**: Powered by Animate.css and WOW.js for engaging transitions and effects.
- **Carousel Slider**: Implemented using Owl Carousel for blog posts and other dynamic content.
- **Portfolio Gallery**: Integrated with Fancybox for a lightbox image viewing experience.
- **Smooth Scrolling**: Back-to-top button for easy navigation.
- **Newsletter Subscription**: Form with a gradient-styled submit button.
- **Counter Animation**: Displays statistics with an animated counter effect using jQuery CountUp.
- **Custom Styling**: Gradient buttons, hover effects, and modern typography with Google Fonts (Roboto).

## 🛠 Technologies Used

- **HTML5**: Semantic markup for structure.
- **CSS3**: Custom styles with flexbox, grid, and animations.
- **JavaScript**: jQuery for DOM manipulation and plugin integration.

### 🔧 Libraries and Frameworks

- FontAwesome 6.2.0 for icons.
- Line Awesome for additional iconography.
- Flaticon for custom icons.
- Owl Carousel for sliders.
- Fancybox 5.0 for portfolio lightbox.
- Animate.css 4.1.1 for animations.
- WOW.js for scroll-triggered animations.
- jQuery CountUp for counter animations.
- Google Fonts (Roboto) for typography.

### 🌐 External Resources

- CDN-hosted libraries (e.g., jQuery, FontAwesome, Fancybox)
- Local assets for images and custom scripts

## 📁 Project Structure

```
samar/
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
│   ├── ...
│   ├── bg2.png
│   ├── bg4.png
│   └── ...
├── js/
│   ├── owl.carousel.min.js
│   ├── countUp/
│   │   └── jquery.countup.js
│   └── back-to-top/
│       └── assets/
│           └── js/
│               ├── main.js
│               └── util.js
└── index.html
```

## 🧾 Installation

1. **Clone or Download the repository**:
   ```bash
   git clone <repository-url>
   ```

2. **Navigate to the project directory**:
   ```bash
   cd samar
   ```

3. **Open `index.html` in a web browser**:
   - Use a local server (e.g., Live Server in VS Code) for best results.
   - Alternatively, host the files on a web server.

## 🚀 Usage

### 🖼️ Customization

- Replace images in the `img/` folder with your own.
- Update content in `index.html` (text, links, portfolio items).
- Modify `css/style.css` for custom colors, fonts, or layouts.

### 🎨 Adding Portfolio Items

- Update the portfolio section in `index.html`.
- Ensure images are added to the `img/` folder and referenced correctly.

### 📝 Blog Posts

- Modify blog items in the blog section of `index.html`.
- Update the Owl Carousel settings if needed.

### 📧 Newsletter Form

- Connect to a backend service (e.g., Formspree, Mailchimp) via the `<form>` `action` attribute.

## 🎨 CSS Highlights

- **Global Reset**: Ensures consistent styling across browsers.
- **Gradient Buttons**: Used for a modern look (e.g., "Get A Quote", "Get Started").
- **Hover Effects**: Applied to portfolio items, service cards, and navigation links.
- **Grid Layouts**: Used for portfolio and services sections.
- **Background Images**: Decorative visuals like `bg2.png`, `bg17.png`.

## ⚙️ JavaScript Highlights

### Owl Carousel

```js
$(".owl-carousel").owlCarousel({
  loop: true,
  margin: 30,
  nav: false,
  dots: false,
  responsive: {
    0: { items: 1 },
    600: { items: 2 },
    1000: { items: 3 }
  }
});
```

### Fancybox

```js
Fancybox.bind("[data-fancybox]", {});
```

### Counter Animation

```js
$(".counter").countUp();
```

### WOW.js

```js
new WOW().init();
```

## 📱 Responsive Design

### Breakpoints

- **Mobile (<576px)**: Single-column layouts.
- **Tablet (576px–992px)**: Two-column layouts.
- **Desktop (>992px)**: Full multi-column layouts.

### Key Adjustments

- Blog grid collapses responsively.
- Image/text scaling across devices.
- Navigation menu can be improved with a mobile toggle.

## 🐞 Known Issues

- **Owl Carousel Dots/Nav**: Currently disabled.
- **Newsletter Form**: Requires backend to function.
- **Image Loading**: Ensure proper image paths.
- **Blog Section CSS Conflict**: Class mismatch (`.blog-section` vs `.blog`, `.blog_content`).

## 🔮 Future Improvements

- Add a hamburger menu for mobile.
- Implement form validation & backend integration.
- Add pagination or load-more for blog section.
- Optimize images (WebP, lazy loading).
- Include a contact form section.

## 👨‍🎓 Credits

- **Author**: Le Nguyen Vu Hoang  
- **Course**: CyberSoft  
- **Icons**: FontAwesome, Line Awesome, Flaticon  
- **Images**: Placeholder images (replace for production use)

## 📝 License

This project is for educational purposes and part of a **CyberSoft** homework assignment.  
**All rights reserved © 2025 HomeworkCBS**
