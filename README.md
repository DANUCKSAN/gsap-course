# GSAP Velvet Pour Mojito Website

A modern and visually engaging cocktail landing page built with **React**, **Vite**, **GSAP**, and **Tailwind CSS**.
This project focuses on smooth scroll-based animations, animated text effects, responsive layouts, and a stylish bar/cocktail website experience.

## Overview

**Velvet Pour** is a premium cocktail-themed landing page designed to showcase creative frontend animation techniques using GSAP. The website includes animated hero text, parallax leaf movements, pinned scroll animations, cocktail menu interactions, and smooth section-based navigation.

The project is built as a frontend portfolio project to demonstrate modern UI development, animation handling, responsive design, and clean React component structure.

## Features

* Modern cocktail landing page design
* Smooth GSAP animations
* Scroll-triggered animations using GSAP ScrollTrigger
* Animated hero section with SplitText text animation
* Parallax leaf animations
* Pinned scroll-based video animation
* Cocktail and mocktail menu sections
* Interactive cocktail slider/menu
* Animated “About” and “The Art” sections
* Contact section with opening hours and social links
* Responsive design for desktop and mobile
* Clean component-based React structure
* Fast development setup using Vite
* Styled with Tailwind CSS

## Tech Stack

* React.js
* Vite
* JavaScript
* GSAP
* @gsap/react
* GSAP ScrollTrigger
* GSAP SplitText
* Tailwind CSS
* React Responsive
* ESLint

## Project Structure

```bash
gsap-velvet-pour-mojito-website/
├── constants/
│   └── index.js
├── public/
├── src/
│   ├── components/
│   │   ├── About.jsx
│   │   ├── Art.jsx
│   │   ├── Contact.jsx
│   │   ├── Hero.jsx
│   │   ├── Menu.jsx
│   │   ├── Navbar.jsx
│   │   └── cocktails.jsx
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── package-lock.json
├── vite.config.js
└── README.md
```

## Main Sections

### Navbar

The navigation bar includes smooth section links for:

* Cocktails
* About Us
* The Art
* Contact

It also includes a scroll-based background animation using GSAP.

### Hero Section

The hero section introduces the Mojito-themed landing page with animated text, decorative leaf images, and scroll-based animation effects.

### Cocktails Section

Displays popular cocktails and mocktails with country, detail, and price information.

### About Section

Highlights the brand experience with animated text, image grids, customer rating, and cocktail-focused content.

### The Art Section

Showcases the craft behind cocktail preparation using pinned scroll animations, masking effects, and animated feature lists.

### Menu Section

Includes an interactive cocktail menu where users can switch between different cocktail items and view recipe-style content.

### Contact Section

Displays bar location, contact details, opening hours, and social media links.

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/DANUCKSAN/gsap-velvet-pour-mojito-website.git
```

### 2. Navigate to the project folder

```bash
cd gsap-velvet-pour-mojito-website
```

### 3. Install dependencies

```bash
npm install
```

### 4. Run the development server

```bash
npm run dev
```

The project will run locally on:

```bash
http://localhost:5173
```

## Available Scripts

### Start development server

```bash
npm run dev
```

### Build for production

```bash
npm run build
```

### Preview production build

```bash
npm run preview
```

### Run linting

```bash
npm run lint
```

## Animation Highlights

This project uses GSAP to create advanced frontend animations such as:

* Text reveal animations
* Character-based title animation
* Scroll-triggered parallax movement
* Pinned video scroll animation
* Image mask scaling animation
* Section entrance animations
* Cocktail menu transition animations

## Responsive Design

The website uses responsive layout techniques and `react-responsive` to adjust animation behavior for mobile and desktop screens.

## Future Improvements

* Add a live deployment link
* Add more cocktail menu items
* Add real booking or reservation functionality
* Add a gallery section
* Add loading animation
* Improve accessibility
* Add SEO metadata
* Add form validation for the contact section
* Add dark/light theme support

## Author

**Danucksan**

GitHub: DANUCKSAN

## License

This project is open-source and available for learning and portfolio purposes.
