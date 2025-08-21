# Delicious Bites Restaurant — “Love at First Bite!”

Welcome to **Delicious Bites**, a single-page, responsive restaurant site crafted using HTML and CSS (plus minimal JS). This README provides you with an overview of the project, how to run it, and the key features and concepts woven into it.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Live Demo](#live-demo)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [Key Features](#key-features)
- [Installation & Usage](#installation--usage)
- [Contributing](#contributing)
- [Credits](#credits)

---

## Project Overview

Delicious Bites is a visually appealing, cleanly coded, and responsive restaurant web page. It showcases multiple sections including:

- A **hero section** featuring an autoplaying, muted video
- **Menu specials** and a full menu table
- **Embedded recipe videos** via YouTube
- A **gallery grid** of images
- An **order form** integrated with **Google Forms & Google Sheets** (sortable by date/time for easy management)
- A **contact form** powered by Web3Forms where the **owner receives direct email notifications** upon each submission
- **Google Maps embed** for the physical location
- **Sticky header, smooth scrolling, and hover effects** for great user experience

Designed to highlight modern front-end development practices, this project is perfect for demonstrations and tutorials.

---

## Live Demo

Check it out at:  
**[https://delicious-bites-ukaz.onrender.com/](https://delicious-bites-ukaz.onrender.com/)**

---

## Technologies Used

- **HTML5** — Semantic structure (`header`, `section`, `main`, `footer`)
- **CSS3** — Styling with:
  - CSS Custom Properties (e.g., `--color-primary`)
  - Flexbox & Grid layouts
  - `rem` units for scalable sizing
  - `box-sizing: border-box` to simplify layout math
  - Media queries for responsiveness
  - Hover effects & transitions
- **JavaScript (minimal)** — for mobile menu toggle and form behavior
- **External Resources**:
  - Google Fonts: Inter & Roboto
  - Font Awesome: Social icons
  - Web3Forms: for contact form submission with direct email alerts
  - Google Forms + Sheets: order form integration with sortable backend data
  - YouTube embeds: recipe videos
  - Google Maps iframe: physical location

---

## File Structure

```css
/ (root)
│
├── index.html — Main HTML page
├── thankyou.html — Redirect page after successful form submission
├── css/
│ └── styles.css — Core stylesheet
├── images/ — Hero, gallery, menu images
├── media/
│ └── cooking.mp4 — Hero video
├── favicon.png — Site icon
└── README.md — This documentation
```

---

## Key Features

| Feature                    | Description                                                                          |
| -------------------------- | ------------------------------------------------------------------------------------ |
| **Hero Video**             | Full-width autoplaying, muted video enhancing visual appeal                          |
| **Menu Section**           | Special highlights and full menu in a styled table                                   |
| **Recipes Section**        | Embedded YouTube videos for richer content                                           |
| **Gallery**                | Responsive image grid with hover zoom                                                |
| **Order Form**             | Google Forms integration, results stored in Google Sheets, sortable by date/time     |
| **Contact Form**           | Web3Forms-powered form; site owner receives direct email notifications (e.g., Gmail) |
| **Thank You Page**         | Users redirected to `thankyou.html` after submission                                 |
| **Sticky Header**          | Navigation remains visible while scrolling                                           |
| **Scroll Behavior**        | Smooth scrolling to page sections                                                    |
| **Accessibility & Layout** | `rem` for scalable typography; `box-sizing: border-box` for layout control           |
| **Responsive Design**      | Mobile-first adjustments using media queries                                         |

---

## Installation & Usage

1. **Clone or Download** this repository.
2. **Open `index.html`** in your browser to preview the site.
3. **For the contact form to work**:
   - Replace the placeholder access key with your actual **Web3Forms access key**.
   - Ensure your email is connected to receive notifications.
4. **For order form**:
   - Connect a Google Form to a Google Sheet to capture and sort customer orders.
5. Optional Enhancements:
   - Serve videos and images via a CDN or compress them further.
   - Add lazy loading to heavy media for improved performance.
   - Implement more JavaScript features such as mobile menu animations.

---

## Contributing

This project is ideal for learning and teaching purposes. Feel free to:

- Fork the repo
- Improve accessibility (alt texts, ARIA attributes)
- Add error handling for the form
- Optimize performance (e.g., lazy loading, compression)
- Enhance the design with animations or dark mode

---

## Credits

- **Font Awesome** — for social media icons
- **Web3Forms** — for backend-less form handling with email notifications
- **Google Fonts (Inter, Roboto)** — for typography
- **Google Forms + Sheets** — for order management & sorting
- **YouTube & Google Maps** — integrated for recipes & location

---

Thank you for exploring **Delicious Bites Restaurant — “Love at First Bite!”**
