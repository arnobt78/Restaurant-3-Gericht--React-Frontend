# Restaurant-3 Gericht - Modern React.js Frontend Restaurant Website (Design 3)

---

## Project Overview

Restaurant-3 Gericht is a modern, fully responsive restaurant website built using ReactJS. It showcases a premium restaurant experience with a clean design, interactive gallery, menu, chef's word, awards, and contact sections. The project is ideal for learning React component architecture, CSS styling, and building scalable web applications.

- **Live-Demo:** []()

---

## Table of Contents

- Project Overview
- Features
- Technology Stack
- Project Structure
- Components & Containers
- How to Run
- Usage & Walkthrough
- Reusing Components
- Keywords
- Conclusion
- Contact & Portfolio

---

## Features

- Responsive design for all devices
- Elegant UI with custom fonts and color palette
- Reusable React components
- Dynamic menu and awards sections
- Interactive gallery with scroll and Instagram icons
- Newsletter subscription form
- Chef's word and history sections
- Contact and working hours info
- Modern navigation bar with hamburger menu for mobile
- Modular CSS for each component
- Easy to extend and customize

---

## Technology Stack

- **ReactJS** (v17)
- **React Icons**
- **CSS Modules**
- **Create React App**
- **ESLint (Airbnb config)**
- **Jest & React Testing Library** (for testing)

---

## Project Structure

```bash
restaurant-3/
├── public/
│   ├── index.html
│   ├── favicon.ico
│   └── ...
├── src/
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   ├── index.css
│   ├── assets/         # Images & video assets
│   ├── components/     # Reusable UI components
│   ├── container/      # Page sections (AboutUs, Chef, Gallery, etc.)
│   ├── constants/      # Data & image imports
│   └── ...
├── package.json
├── README.md
└── ...
```

---

## Components & Containers

### Components (components)

- **Navbar**: Responsive navigation bar with links and hamburger menu.
- **SubHeading**: Section subheading with decorative spoon image.
- **MenuItem**: Displays menu items (title, price, tags).
- **FooterOverlay**: Footer background overlay.
- **Newsletter**: Email subscription form.

### Containers (container)

- **Header**: Hero section with restaurant intro.
- **AboutUs**: About and history of the restaurant.
- **SpecialMenu**: Dynamic menu for wines, beers, cocktails.
- **Chef**: Chef's word and signature.
- **Intro**: Video intro section.
- **Laurels**: Awards and recognitions.
- **Gallery**: Interactive photo gallery.
- **FindUs**: Contact and location info.
- **Footer**: Footer with contact, logo, working hours, and social links.

---

## How to Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/arnob-mahmud/restaurant-3.git
   cd restaurant-3
   ```

2. **Install dependencies:**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start the development server:**

   ```bash
   npm start
   # or
   yarn start
   ```

4. **Open in browser:**

   Visit [http://localhost:3000](http://localhost:3000)

---

## Usage & Walkthrough

- The app starts with a stylish navigation bar (`Navbar`) and a hero section (`Header`).
- Scroll to explore sections: About Us, Menu, Chef's Word, Video Intro, Awards, Gallery, Find Us, and Footer.
- Each section is a React component/container, styled with modular CSS.
- The menu and awards are dynamically rendered from data in data.js.
- The gallery uses scrollable images and Instagram icons for a modern feel.
- The newsletter form allows users to subscribe for updates.
- The footer provides contact info, working hours, and social media links.

---

## Reusing Components

All components are designed to be reusable. Example usage:

```jsx
import { MenuItem, SubHeading, Navbar } from './components';

<MenuItem title="Chapel Hill Shiraz" price="$56" tags="AU | Bottle" />
<SubHeading title="Today's Special" />
<Navbar />
```

To use in other projects, copy the component folder and update imports as needed. Each component is self-contained with its CSS.

---

## Keywords

ReactJS, Restaurant Website, Responsive Design, UI Components, CSS Modules, Modern Web App, Gallery, Menu, Awards, Newsletter, Navigation, Reusable Components, Frontend, JavaScript, Learning Project

---

## Conclusion

This project is a great starting point for learning ReactJS, building beautiful UIs, and understanding component-based architecture. Feel free to extend, customize, and use it for your own restaurant or portfolio projects!

---

## Happy Coding! 🎉

Feel free to use this Project Repository and extend this project further!

If you have any questions or want to share your work, reach out via GitHub or my portfolio at [https://arnob-mahmud.vercel.app/](https://arnob-mahmud.vercel.app/).

**Enjoy building and learning!** 🚀

Thank you! 😊

---
