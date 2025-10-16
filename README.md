# Markdown to HTML Converter

This is a static web application that converts Markdown text to HTML and renders it on the page. It uses the `marked` library for Markdown parsing and `highlight.js` for syntax highlighting of code blocks.

## How it works

1.  The `index.html` file contains basic HTML structure.
2.  It includes the `marked.min.js` and `highlight.min.js` libraries from CDNs.
3.  A predefined Markdown string is converted to HTML using `marked.parse()`.
4.  The resulting HTML is injected into the `#markdown-output` div.
5.  `highlight.js` is then used to apply syntax highlighting to any code blocks within the rendered HTML.

## Files

*   `index.html`: The main HTML file for the application.
*   `README.md`: This file.
*   `LICENSE`: The MIT License.
