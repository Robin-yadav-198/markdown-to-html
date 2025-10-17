# Markdown Viewer

A simple, single-page web application that dynamically fetches and renders Markdown content from an `input.md` file into a responsive HTML page using Tailwind CSS and Marked.js.

## Features

*   **Markdown to HTML Conversion:** Utilizes the [Marked.js](https://marked.js.org/) library to convert Markdown syntax into HTML.
*   **Responsive Design:** Built with [Tailwind CSS](https://tailwindcss.com/) for a modern and responsive user interface that adapts to various screen sizes.
*   **Single-File Application:** All necessary HTML, CSS (via CDN), and JavaScript (via CDN and inline) are contained within a single `index.html` file for easy deployment and sharing.
*   **Dynamic Content Loading:** Fetches `input.md` asynchronously from the same directory, allowing for easy updates to the content without modifying the `index.html` file.

## Getting Started

To use this Markdown Viewer, follow these simple steps:

1.  **Save the files:** Ensure `index.html` and `input.md` are saved in the same directory.
2.  **Open `index.html`:** Open `index.html` in your web browser.

The `index.html` page will automatically fetch the content of `input.md`, convert it to HTML, and display it.

## File Structure

```
.
├── index.html
└── input.md
```

## Technologies Used

*   **HTML5:** For the page structure.
*   **Tailwind CSS:** For styling and responsiveness.
*   **Marked.js:** For Markdown parsing.
*   **JavaScript (ES6+):** For dynamic content loading and manipulation.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.