# Restaurant-3 Gericht - Modern React.js Frontend Restaurant Website (Design 3)

<img width="1362" height="807" alt="Screenshot 2025-07-30 at 15 57 02" src="https://github.com/user-attachments/assets/d9f0ec6f-ccb7-4505-a470-665ab157b6bb" />
<img width="1384" height="884" alt="Screenshot 2025-07-30 at 15 57 22" src="https://github.com/user-attachments/assets/fc1e2406-61f2-4716-aadf-2c7ff040fd59" />
<img width="1336" height="873" alt="Screenshot 2025-07-30 at 15 57 37" src="https://github.com/user-attachments/assets/3b3552bd-52ef-452a-b9e1-5cc890ccdac1" />
<img width="1292" height="773" alt="Screenshot 2025-07-30 at 15 57 50" src="https://github.com/user-attachments/assets/896d2550-d3d6-4ceb-9620-7fc655269c79" />
<img width="1420" height="878" alt="Screenshot 2025-07-30 at 15 58 06" src="https://github.com/user-attachments/assets/67b95060-db2a-4261-8bb5-2e18dd4915bc" />
<img width="1366" height="768" alt="Screenshot 2025-07-30 at 15 58 17" src="https://github.com/user-attachments/assets/46e2ddcd-05eb-481d-bfba-db95cc6e2e54" />
<img width="1369" height="687" alt="Screenshot 2025-07-30 at 15 58 28" src="https://github.com/user-attachments/assets/44b5986c-0f12-4af8-a181-1cc43b89a157" />
<img width="1272" height="708" alt="Screenshot 2025-07-30 at 15 58 37" src="https://github.com/user-attachments/assets/b02f5d0e-7ed1-48e0-9398-5b01a03aaa19" />
<img width="1193" height="762" alt="Screenshot 2025-07-30 at 15 58 50" src="https://github.com/user-attachments/assets/286236b9-5cc7-4a3a-85a1-d885bb2666fb" />

---

## Project Overview

Restaurant-3 Gericht is a modern, fully responsive restaurant website built using ReactJS. It showcases a premium restaurant experience with a clean design, interactive gallery, menu, chef's word, awards, and contact sections. The project is ideal for learning React component architecture, CSS styling, and building scalable web applications.

- **Live-Demo:** [https://restaurant-3-gericht.netlify.app/](https://restaurant-3-gericht.netlify.app/)

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
