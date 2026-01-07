# GitHub CodeCanvas Preview

**Preview `.codecanvas` files directly from GitHub repositories**

Many GitHub repositories now include `.codecanvas` files — a new visual, interactive format for project documentation. **GitHub CodeCanvas Preview** allows you to view and explore these files directly in your browser without cloning or downloading repositories.

If you try to open a `.codecanvas` file directly from GitHub, you'll only see the raw source code. GitHub serves it as plain text, so it cannot be rendered interactively. This tool fetches the file via a CORS proxy and renders it as a fully interactive code visualization.

---

## 🚀 Usage

To preview any `.codecanvas` file hosted on GitHub, simply prepend:

**`https://codecanvaspreview.github.io/?`**

to the raw URL of the file.

### Example:
https://codecanvaspreview.github.io/?https://raw.githubusercontent.com/SongDrop/openjkdf2/master/openjkdf2.codecanvas


### What It Does:
1. Loads the `.codecanvas` file via a CORS proxy
2. Parses the file's metadata and visual structure
3. Renders an interactive project canvas with file navigation, visual annotations, and live links
4. Enables direct exploration of the codebase structure without leaving the browser

---

## ✨ Features

- **Visual Project Navigation** – Interactive tree view of the codebase
- **Annotation Support** – Displays comments and documentation embedded in the `.codecanvas` file
- **Live File Links** – Click files to view them on GitHub
- **No Backend Required** – Runs entirely client-side
- **GitHub Integration** – Works with any public repository
- **Open Standard** – `.codecanvas` is an open file format for visual project documentation

---

## 👨‍💻 For Repository Maintainers

To add a `.codecanvas` file to your project:
1. Create a `.codecanvas` file using the [CodeCanvas VS Code Extension](https://marketplace.visualstudio.com/items?itemName=SongDrop.codecanvas)
2. Include it in your repository (typically alongside `README.md`)
3. Share preview links using:  
   `https://codecanvaspreview.github.io/?https://raw.githubusercontent.com/YOUR_USER/YOUR_REPO/main/YOUR_FILE.codecanvas`

---

## 🌐 Browser Support

GitHub CodeCanvas Preview works in modern browsers with JavaScript enabled, including:
- Google Chrome (latest)
- Mozilla Firefox (latest)
- Microsoft Edge (latest)
- Safari (latest)

---

## 🔧 Technical Details

This is a static client-side application that uses:
- CORS proxy to fetch GitHub resources
- HTML5 Canvas for visual rendering
- Vanilla JavaScript for parsing `.codecanvas` metadata
- No user data collection or tracking

---

## 📚 Similar Projects

This tool follows the same concept as:
- [htmlpreview.github.io](https://github.com/htmlpreview) – for previewing HTML files
- Historical services like rawgit.com

But it's specialized for the new `.codecanvas` visual documentation format.

---

## 📄 License

© 2025 Gabriel Majorsky  
Licensed under the MIT License

---

## 🤝 Contributing

This project is open source. Feel free to submit issues and pull requests on the [GitHub repository](https://github.com/codecanvaspreview/codecanvaspreview.github.com).

---

**Live at:** [https://codecanvaspreview.github.io](https://codecanvaspreview.github.io)
