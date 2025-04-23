# Codepen-React 🖥️⚛️

Live Demo: [https://quirky-mirzakhani-12bdf3.netlify.app/](https://quirky-mirzakhani-12bdf3.netlify.app/)

## Overview

**Codepen-React** is a lightweight in-browser code playground inspired by CodePen. It allows users to write and preview HTML, CSS, and JavaScript code in real time using React and modern web technologies.

![Screenshot](./screenshot.png)

## Features

- 🧠 **Live Preview**: Instant rendering of HTML, CSS, and JavaScript code.
- 🎨 **Syntax Highlighting**: Monaco Editor integration for a smooth editing experience.
- 🔳 **Resizable Panels**: Three separate panels for HTML, CSS, and JS with a live output pane.
- 🌐 **Responsive Design**: Works seamlessly across devices and screen sizes.
- ⚛️ **Built with React**: Uses functional components and hooks.

## Tech Stack

- **React**
- **Monaco Editor** (via `@monaco-editor/react`)
- **Tailwind CSS** for styling
- **Netlify** for deployment

## Getting Started

1. Clone the repo:

   ```bash
   git clone https://github.com/harivilasp/Codepen-React.git
   cd Codepen-React
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

## Folder Structure

```
/src
  /components
    Editor.js         # Individual code editor for HTML/CSS/JS
    Preview.js        # Live output rendering
  App.js              # Main layout combining editors and preview
  index.js            # App entry point
  styles.css          # Tailwind and global styles
```

## Possible Improvements

- 📝 Add local storage or cloud sync for saving code
- 📁 Support for file-based project structure
- 🔍 Error highlighting or console logging
- 🧪 Unit tests for editor components

## License

MIT License

---

Created with ❤️ by [@harivilasp](https://github.com/harivilasp)
