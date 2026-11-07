# Section 1: Bootstrap Getting Started

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Bootstrap 5](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

[⬅ Back to Main README](../README.md)

---

## 📌 Overview

This section covers the fundamental setup and installation of **Bootstrap 5.3**. It demonstrates how to initialize a modern HTML5 document, configure the viewport meta tag for responsive scaling, and link the official Bootstrap CSS and JavaScript bundle via jsDelivr CDN.

---

## 📂 Directory Structure

```text
Section1 Bootstrap/
└── 01-hello-world/
    └── index.html
```

---

## 📖 Module Breakdown

### `01-hello-world`
- **File**: `index.html`
- **Concepts**:
  - Proper HTML5 `<!DOCTYPE html>` setup.
  - Responsive viewport meta tag: `<meta name="viewport" content="width=device-width, initial-scale=1.0">`.
  - Linking Bootstrap 5 stylesheet in the `<head>`:
    ```html
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css">
    ```
  - Linking the Bootstrap JavaScript Bundle (which includes Popper) before the closing `</body>`:
    ```html
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"></script>
    ```
  - Rendering basic typography and containers to verify that CSS reset and styles are successfully applied.

---

## 🚀 How to Run

1. Open `Section1 Bootstrap/01-hello-world/index.html` in VS Code.
2. Right-click and choose **Open with Live Server**, or open the file directly in any web browser.

