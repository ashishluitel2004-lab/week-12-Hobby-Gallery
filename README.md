# week-12-Hobby-Gallery
This project is a hobby gallery web application built as part of the week 12 assignment focusing on javascript arrays and loops
# Week 12 Assignment: Hobby Gallery (Arrays & Loops)

A clean, interactive web application built to demonstrate the practical application of JavaScript arrays, zero-based indexing, event listeners, and basic error debugging.

## 🚀 Features
- **Dynamic Image Switching:** Uses a JavaScript array to hold and cycle through a list of hobby image URLs.
- **Index Out-of-Bounds Protection:** Implements an `if` statement logical check that automatically resets the image tracker back to `0` when the end of the array is reached, successfully preventing `undefined` broken link errors.
- **Console Tracking:** Outputs current tracking indices and source assets live to the Developer Tools Console for real-time validation and grading.
- **Separation of Concerns:** Clean architecture separating structure (`index.html`), styling (`style.css`), and functional logic (`script.js`).

## 📁 File Structure
```text
├── index.html       # Structural template with the core container, image tag, and action button.
├── style.css        # Modern, centered flexbox card layout with interactive element transitions.
├── script.js        # Logic engine containing image arrays, state trackers, and click event bindings.
└── screenshot.png   # Required browser submission screenshot featuring an active, error-free developer console.
