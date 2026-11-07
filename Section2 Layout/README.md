# Section 2: Layout & Grid System

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap 5](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

[⬅ Back to Main README](../README.md)

---

## 📌 Overview

This section covers Bootstrap's powerful 12-column flexbox grid system, responsive containers, breakpoint management, column wrapping, auto margins, reordering, alignment, and gutter spacing.

---

## 📂 Directory Structure

```text
Section2 Layout/
├── 01-container/
├── 02-grid-options/
├── 03-nested-rows/
├── 04-column-vertical/
├── 05-column-horizontal/
├── 06-column-wrap/
├── 07-recording-offset/
├── 08-margin-utilities/
├── 09-gutters/
└── 10-horizontal-gutter/
```

---

## 📖 Module Breakdown

| Module | Core Concepts & Classes |
| :--- | :--- |
| **`01-container`** | `.container`, `.container-fluid`, and breakpoint-specific containers (`.container-sm`, `.container-md`, `.container-lg`, `.container-xl`, `.container-xxl`). Includes window resize behavior demonstrations. |
| **`02-grid-options`** | Understanding the 12-column grid model. Using `.row` and proportional column sizing across devices (`col`, `col-sm-6`, `col-md-4`, `col-lg-3`). |
| **`03-nested-rows`** | Nesting child rows and columns inside existing parent column containers for multi-level layouts without breaking grid boundaries. |
| **`04-column-vertical`** | Vertical column alignment: `.align-items-start`, `.align-items-center`, `.align-items-end` on rows, and individual column alignment via `.align-self-*`. |
| **`05-column-horizontal`** | Horizontal distribution: `.justify-content-start`, `.justify-content-center`, `.justify-content-end`, `.justify-content-between`, `.justify-content-around`, and `.justify-content-evenly`. |
| **`06-column-wrap`** | Wrapping behavior when cumulative column widths exceed 12 units. Creating multi-line grid structures within a single row. |
| **`07-recording-offset`** | Reordering columns visually with `.order-1` to `.order-5`, `.order-first`, `.order-last`, and column offsetting with `.offset-*` and `.offset-md-*`. |
| **`08-margin-utilities`** | Flexbox-powered auto margins inside grid rows to push columns to the far left or right (`.ms-auto`, `.me-auto`). |
| **`09-gutters`** | Controlling spacing and padding between columns and rows using unified gutter utility classes (`.g-0` to `.g-5`). |
| **`10-horizontal-gutter`** | Independent control of horizontal gutters (`.gx-0` to `.gx-5`) and vertical gutters (`.gy-0` to `.gy-5`) for custom responsive gaps. |

---

## 🚀 How to Run

Open any subfolder's `index.html` (e.g., `Section2 Layout/01-container/index.html`) in VS Code and view in browser using Live Server.

