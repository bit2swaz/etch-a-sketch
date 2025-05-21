# Etch-A-Sketch

A modern and interactive Etch-A-Sketch drawing application built with **HTML, CSS, and JavaScript**, featuring multiple drawing modes, responsive design, and a slick user interface with a theme toggle. Developed as part of [The Odin Project](https://www.theodinproject.com) curriculum, showcasing fundamental front-end development skills.

## Live Demo
[Play the Etch-A-Sketch](https://bit2swaz.github.io/etch-a-sketch/)

---

## Features
- **Dynamic Grid Generation:** Users can specify grid dimensions (1-100 squares per side) for a custom drawing canvas.
- **Versatile Drawing Modes:**
    - **Solid Color:** Draw with a single, user-selected color from a integrated color picker.
    - **Rainbow Mode:** Experience a burst of creativity as each interaction applies a new, random RGB color.
    - **Shading Mode:** Implement a progressive darkening effect where each interaction increases a square's opacity by 10%, achieving a fully colored square in ten hits.
- **Intuitive Interaction Modes:**
    - **Hover-to-Draw:** Default mode for casual drawing.
    - **Click & Drag:** Toggle to draw only when the mouse button is pressed and dragged, mimicking a real Etch-A-Sketch.
- **Eraser Tool:** Clear individual squares or the entire grid for precise adjustments or a fresh start.
- **Persistent Theme Toggle:** Seamlessly switch between light and dark modes, with user preference saved in local storage for a consistent experience across sessions.
- **Responsive & Adaptive UI:** The layout dynamically adjusts to various screen sizes, ensuring optimal usability on desktops, tablets, and mobile devices. The drawing grid resizes proportionally, avoiding scrollbars for a full canvas view.
- **Clean and Maintainable Codebase:** Structured HTML, well-organized CSS, and modular JavaScript for readability, extensibility, and ease of understanding.
- **Smooth Visuals:** Modern styling with subtle transitions and hover effects for an engaging user experience.

---

## Tech Stack
- **HTML5:** For semantic structure and content.
- **CSS3:** For modern styling, responsiveness, and visual effects (Flexbox for layout).
- **JavaScript (Vanilla):** For all interactive logic, DOM manipulation, and dynamic functionality.

---

## What I Learned
- **Advanced DOM Manipulation:** Dynamically creating, styling, and managing a large number of DOM elements (grid squares).
- **Event Handling Mastery:** Implementing complex event listeners for `mouseover`, `mousedown`, `mouseup`, `input`, and `click` to create interactive drawing experiences.
- **State Management:** Effectively tracking and managing application state (e.g., `isEraserMode`, `isClickAndDragMode`, `currentDrawingMode`, `data-hits`, `data-color`).
- **Responsive Design Principles:** Crafting a layout that adapts gracefully to different screen sizes while prioritizing key UI elements (grid and footer visibility).
- **CSS Layout Techniques:** Proficient use of Flexbox for dynamic and responsive component arrangement.
- **Conditional Logic & Algorithmic Thinking:** Implementing distinct drawing behaviors (solid, rainbow, shading) and interaction patterns.
- **User Preference Persistence:** Utilizing `localStorage` for enhanced user experience (theme saving).

---

## How to Run Locally
```bash
git clone [https://github.com/bit2swaz/etch-a-sketch.git](https://github.com/bit2swaz/etch-a-sketch.git)
cd etch-a-sketch
open index.html
```

---

