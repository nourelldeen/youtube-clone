# YouTube Clone (HTML & CSS)

A static, pixel-inspired recreation of the YouTube homepage, built from scratch with **plain HTML and CSS** — no frameworks, no libraries. This project was built as hands-on practice after completing an HTML & CSS course, to apply layout, Flexbox, and CSS Grid concepts in a real interface.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## Demo

[📹 Download & Watch Demo Video](./attachments/Project-Vidoe-Demo.mov)

## Table of Contents

- [Features](#features)
- [Built With](#built-with)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Credits](#credits)
- [License](#license)

## Features

- Fixed header with logo, search bar, and voice search button
- Hover tooltips on header icons (search, voice search, create, notifications)
- Sidebar navigation with icon links: Home, Explore, Subscriptions, Originals, YouTube Music, Library
- Responsive video grid built with CSS Grid (`auto-fit` / `minmax`) — reflows cleanly from mobile to desktop widths
- Semantic HTML structure (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`) for accessibility and SEO
- Notification badge and channel avatar in the header

## Built With

- **HTML5** — semantic markup
- **CSS3** — Flexbox, Grid, responsive layout
- **[Google Fonts – Roboto](https://fonts.google.com/specimen/Roboto)**

## Project Structure

```
youtube-clone-html-css/
├── index.html
├── README.md
├── LICENSE
├── .gitignore
├── CSS Files/
│   ├── General.css      # Reset, base typography, global styles
│   ├── Header.css        # Header, search bar, tooltips, right-section icons
│   ├── Side_bar.css      # Left navigation sidebar
│   └── Video.css         # Video grid and card layout
└── attachments/
    ├── Icons/            # UI icons (search, menu, notifications, etc.)
    ├── Thumbnalls/        # Video thumbnail images
    └── pfp/              # Channel profile pictures
```

## Getting Started

No build step or dependencies required — it's plain HTML/CSS.

**Clone the repo:**

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

**Run it:**

Open `index.html` directly in your browser, or serve it locally:

```bash
npx serve .
```

## Credits

Built while learning from the **[HTML & CSS Full Course – Beginner to Pro](https://youtu.be/G3e-cpL7ofc)** by **Simon**. Thank you for such a clear, solid foundation in HTML and CSS — this project wouldn't exist without it.

## License

This project is licensed under the [MIT License](./LICENSE) — feel free to use it for learning purposes.
