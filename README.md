# 🎥 YouTube Homepage Clone

A beautiful, modern, and pixel-perfect replica of the YouTube desktop homepage layout. This project focuses on clean, semantic HTML structure and responsive CSS configurations without relying on any JavaScript! 🚀

## ✨ Features

- **📱 Smart Video Grid**: Automatically reshapes the layout into 4, 3, 2, or 1 columns depending on the size of your viewer's screen.
- **📌 Fixed Navigation Panels**: The top header bar and left sidebar remain completely locked in place while the video feed scrolls smoothly underneath.
- **🔍 Fluid Search Bar**: A realistic center search layout that expands and scales dynamically based on your window proportions.
- **💬 Pure CSS Interactive Tooltips**: Hovering over navigation icons reveals a smooth pop-up text label built completely with pure CSS.
- **🎬 Micro-Animations**: Features smooth scale-up transitions when you hover over video thumbnails and subtle background shifts on buttons.
- **🌐 Universally Hosted Media**: Swapped old, broken local drive file paths for live vector avatar endpoints and working thumbnail links.

## 📁 Project Structure

The project code is cleanly divided into two separate source files to keep your layout structure and design properties separated:

- `youtube.clone` (HTML part) - Contains the structural text tags, input boxes, and video content lists. 🦴
- `youtube.clone` (CSS part) - Contains the global positions, colors, hover transitions, and layout dimensions. 🎨

## 🛠️ Built With

- **🌐 HTML**: Used to create the main skeleton boxes, layout panels, text blocks, and images.
- **🎨 CSS Grid & Flexbox**: Used to handle complex side-by-side structures and multi-device fluid responsiveness.
- **🔤 Google Fonts (Roboto)**: Integrated to match the precise typography engine used on the official desktop app.

## 🚀 How to Run This Project Locally

1. **📥 Download the code**: Clone this repository to your computer using your terminal or download the ZIP folder directly.
2. **📂 Keep files together**: Ensure both your HTML `youtube.clone` and CSS `youtube.clone` files are saved inside the exact same folder.
3. **💻 Launch the app**: Open the HTML `youtube.clone` file inside any modern web browser (like Chrome, Edge, or Firefox) to view your creation!

## 💡 Code Design Highlights

// Clears default browser spacing so your layout containers never break out of alignment
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

// Automatically scales card columns up or down based on screen widths
grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));

// Smoothly cuts off extra long video title text at exactly two lines lengths
-webkit-line-clamp: 2;
