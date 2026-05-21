# YouTube Homepage Clone

A beautiful, modern, and pixel-perfect replica of the YouTube homepage layout. This project focuses on clean code, semantic HTML structures, and responsive CSS grids without relying on any JavaScript.

## Features

- **Smart Video Grid**: Automatically arranges videos into 4, 3, 2, or 1 columns depending on your screen size.
- **Fixed Navigation Panels**: The top header bar and left sidebar remain locked in place while the video feed scrolls smoothly underneath.
- **Fluid Search Bar**: A realistic center search layout that expands and scales dynamically based on window proportions.
- **Pure CSS Interactive Tooltips**: Hovering over navigation icons reveals a smooth pop-up label built completely with CSS.
- **Micro-Animations**: Features smooth scale-up transitions on video thumbnails and subtle background changes on link hovers.
- **Universally Hosted Media**: Swapped old, broken local file paths for clean vector avatar endpoints and live placeholder images.

## Project Structure

The project code is cleanly divided into two separate files to keep layout design and styling properties isolated:

- `index.html` - Contains the structural tags, text layout inputs, and content arrays.
- `style.css` - Contains the global layout alignments, flexbox rules, grid dimensions, and color themes.

## Built With

- **HTML5**: Used for semantic layout tags like headers, sections, paragraphs, and image placeholders.
- **CSS3 Grid & Flexbox**: Used to handle complex side-by-side positioning and multi-device screen responsiveness.
- **Google Fonts (Roboto)**: Integrated to perfectly match the typography engine used on the official desktop app.

## How to Run This Project Locally

1. **Download the code**: Clone this repository to your computer using your terminal or download the ZIP folder directly.
2. **Move files together**: Ensure both `index.html` and `style.css` are saved together in the exact same folder.
3. **Launch the app**: Double-click on the `index.html` file to instantly open it inside any modern web browser.

## Code Design Highlights

// Clears default browser padding so elements do not break out of place
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

// Automatically shifts grid rows based on display resolutions
grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));

// Smoothly cuts off long creator titles at exactly two lines
-webkit-line-clamp: 2;
