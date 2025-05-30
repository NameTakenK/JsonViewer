# 🌈 JSON Viewer

A modern, lightweight, and interactive JSON Viewer that supports:

- ✅ Real-time Tree & Raw view modes
- 🌓 Light/Dark theme toggle
- 📏 Resizable layout with draggable center divider
- 🔍 Raw JSON syntax highlighting with custom styles
- ⚠️ Live error handling and display
- 🧊 Glassmorphism-style design

---

## 📁 Features

| Feature                 | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| 🌳 Tree View           | Interactive collapsible tree view powered by `jsoneditor`                   |
| 📄 Raw View            | Pretty-printed and syntax-highlighted raw JSON                              |
| 🌓 Theme Toggle        | Switch between light and dark mode instantly                                |
| 📏 Resizer             | Drag center divider to resize editor/view area                              |
| ⚠️ Error Display       | Invalid JSON will show an inline error message                              |
| 🎨 Highlighting        | Keys, strings, numbers, booleans, null values are all styled distinctly      |

---

## 🚀 Usage

1. Save the HTML content to a file, e.g., `index.html`.
2. Open it in your browser.
3. Start editing JSON on the left. The result will automatically appear on the right.
4. Use the 🌳 / 📄 tabs to switch views.
5. Click 🌓 to toggle dark/light mode.
6. Drag the vertical divider to resize panels.

---

## 🧩 Dependencies

- [jsoneditor v9.10.0](https://github.com/josdejong/jsoneditor)

Loaded via CDN:
```html
<script src="https://cdn.jsdelivr.net/npm/jsoneditor@9.10.0/dist/jsoneditor.min.js"></script>
<link href="https://cdn.jsdelivr.net/npm/jsoneditor@9.10.0/dist/jsoneditor.min.css" rel="stylesheet" />
