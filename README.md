# 📄 PDF Viewer – JavaScript + PDF.js Based Web Viewer

A simple and lightweight **PDF Viewer** built with vanilla JavaScript and powered by Mozilla's **PDF.js** library. This web app enables users to view PDF files with page navigation support directly in the browser without needing third-party plugins.

## 🔍 Features

- 📚 View PDFs directly in the browser
- ⏮️ ⏭️ Navigate pages using Prev/Next buttons
- 📄 Page indicator showing current page and total pages
- ⚠️ Error handling for failed loads
- 🎨 Minimal and clean interface using CSS

## 🛠 Tech Stack

- **HTML5** – Layout structure
- **CSS3** – Styling the UI
- **JavaScript (ES6)** – Page rendering and navigation logic
- **[PDF.js](https://mozilla.github.io/pdf.js/)** – Rendering PDF content in `<canvas>`

## ⚙ How It Works

- Loads the PDF using `pdfjsLib.getDocument(url)`
- Renders each page on a `<canvas>` element
- Adds button controls to navigate between pages
- Displays page count and handles rendering queue smoothly

## ✨ Future Enhancements

- Upload custom PDF files
- Zoom in/out functionality
- Search within PDF
- Keyboard shortcuts (←, →)
- Mobile-friendly navigation
