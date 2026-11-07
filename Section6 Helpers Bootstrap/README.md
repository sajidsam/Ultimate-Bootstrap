# Section 6: Bootstrap Helpers

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap 5](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

[⬅ Back to Main README](../README.md)

---

## 📌 Overview

This section covers Bootstrap 5's helper utilities that solve specific UI challenges cleanly without requiring custom CSS. Topics include clearfix, colored links, link utilities, focus rings, icon links, ratio containers, positioning helpers, stacks, accessibility screen readers, stretched links, and text truncation.

---

## 📂 Directory Structure

```text
Section6 Helpers Bootstrap/
├── 01-clearfix/
├── 02-colors-bg/
├── 03-colored-links/
├── 04-link-util/
├── 05-focus-ring/
├── 06-icon-link/
├── 07-ratio/
├── 08-positions/
├── 09-stacks/
├── 10-visually-hidden/
├── 11-streched-link/
└── 12-text-truncate/
```

---

## 📖 Module Breakdown

| Module | Helper & Description | Classes Used |
| :--- | :--- | :--- |
| **`01-clearfix`** | **Clearfix**: Clears floated content inside a container to prevent container collapse. | `.clearfix` |
| **`02-colors-bg`** | **Color & Background Helpers**: Unified background and contrasting text color helpers. | `.text-bg-primary`, `.text-bg-success`, `.text-bg-dark` |
| **`03-colored-links`** | **Colored Links**: Contextual link colors with built-in hover and focus states. | `.link-primary`, `.link-secondary`, `.link-danger` |
| **`04-link-util`** | **Link Utilities**: Controlling link underline styles, offsets, and opacities. | `.link-offset-*`, `.link-underline-*`, `.link-underline-opacity-*` |
| **`05-focus-ring`** | **Focus Ring**: Accessible, custom-colored focus rings for interactive elements. | `.focus-ring`, `.focus-ring-primary`, `.focus-ring-success` |
| **`06-icon-link`** | **Icon Link**: Modern link layout designed for inline SVGs/icons with animated hover translations. | `.icon-link`, `.icon-link-hover` |
| **`07-ratio`** | **Ratios**: Proportional aspect ratio containers for responsive videos, iframes, and embeds. | `.ratio`, `.ratio-16x9`, `.ratio-4x3`, `.ratio-1x1`, `.ratio-21x9` |
| **`08-positions`** | **Positions**: Fixing or sticking elements relative to viewport boundaries. | `.fixed-top`, `.fixed-bottom`, `.sticky-top`, `.sticky-bottom` |
| **`09-stacks`** | **Stacks**: Instant vertical and horizontal flexbox stacks with spacing gap support. | `.vstack`, `.hstack`, `gap-2`, `gap-3` |
| **`10-visually-hidden`** | **Visually Hidden**: Hiding elements visually while keeping them accessible to screen readers. | `.visually-hidden`, `.visually-hidden-focusable` |
| **`11-streched-link`** | **Stretched Link**: Spreading an anchor tag's clickable area across its nearest relative parent container. | `.stretched-link` |
| **`12-text-truncate`** | **Text Truncation**: Truncating text overflow into an ellipsis on a single line. | `.text-truncate` |

---

## 🚀 How to Run

Open any folder (e.g., `Section6 Helpers Bootstrap/07-ratio/index.html`) in VS Code with Live Server.

