# Bootstrap 5 Learning & Project Repository

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap 5](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 📌 Overview

This repository contains a comprehensive, hands-on learning roadmap and practical projects built with **Bootstrap 5.3**. It covers core grid layouts, content styling, interactive forms, UI components, modern helper utilities, extensive atomic utility classes, and real-world multi-page web applications.

---

## 🛠️ Tech Stack & Tools

- **HTML5**: Semantic markup structuring
- **CSS3**: Custom gradients, glassmorphism backdrop filters, variables, and scoped overrides
- **Bootstrap 5.3**: Responsive grid, utilities, layout components, and JS modules
- **JavaScript**: Popper.js and Bootstrap bundle for interactive components (dropdowns, modals, collapses)

---

## 🌐 Live Demos & Deployments

| Project | Live Demo Link | Platform |
| :--- | :--- | :--- |
| **Project 1: EMS 2.0 (Employee Management System)** | [![Live Demo](https://img.shields.io/badge/Live_Demo-Visit_EMS_2.0-0070F3?style=for-the-badge&logo=vercel&logoColor=white)](https://ems-web-kappa.vercel.app/) | Vercel |
| **Project 2: BLOG 2.0 (Modern Blog Platform)** | [![Live Demo](https://img.shields.io/badge/Live_Demo-Visit_BLOG_2.0-0070F3?style=for-the-badge&logo=vercel&logoColor=white)](https://blog-app-jet-ten-12.vercel.app/) | Vercel |

---

## 📂 Folder Structure

```text
Bootstrap/
├── Section1 Bootstrap/
│   └── 01-hello-world/
│       └── index.html
├── Section2 Layout/
│   ├── 01-container/
│   ├── 02-grid-options/
│   ├── 03-nested-rows/
│   ├── 04-column-vertical/
│   ├── 05-column-horizontal/
│   ├── 06-column-wrap/
│   ├── 07-recording-offset/
│   ├── 08-margin-utilities/
│   ├── 09-gutters/
│   └── 10-horizontal-gutter/
├── Section3 Contents/
│   ├── 01-typography/
│   ├── 02-inline-text-elm/
│   ├── 03-blockquotes/
│   ├── 04-lists/
│   ├── 05-images-in-bootstrap/
│   ├── 06-tables-in-bootstrap/
│   ├── 07-table-alignment-nesting/
│   └── 08-figures-in-bootstrap/
├── Section4 Forms/
│   ├── 01-forms/
│   ├── 02-form-control/
│   ├── 03-checks-radios/
│   ├── 04-range/
│   ├── 05-input-groups/
│   ├── 06-floating-labels/
│   ├── 07-form-layout/
│   ├── 08-horizontal-forms/
│   ├── 09-auto-sizing-forms/
│   ├── 10-inline-forms/
│   └── 11-form-validation/
├── Section5 Components/
│   ├── 01/ to 05/            # Accordions, Alerts, Badges, Breadcrumbs
│   ├── 06/                   # Buttons & Button Grids (index.html, button.html)
│   ├── 07/ to 09/            # Button Groups, Toolbars, Sizing
│   └── 10/ to 26/            # Component Practice Modules
├── Section6 Helpers Bootstrap/
│   ├── 01-clearfix/
│   ├── 02-colors-bg/
│   ├── 03-colored-links/
│   ├── 04-link-util/
│   ├── 05-focus-ring/
│   ├── 06-icon-link/
│   ├── 07-ratio/
│   ├── 08-positions/
│   ├── 09-stacks/
│   ├── 10-visually-hidden/
│   ├── 11-streched-link/
│   └── 12-text-truncate/
├── Section7 Utilities/
│   ├── 01-backgrounds/ to 04-bg-opacity/
│   ├── 05-border/ to 10-rounded-border/
│   ├── 11-text-color/ & 12-text-opacity/
│   ├── 13-display-inline/ to 15-display-in-print/
│   ├── 16-flex/ to 28-flex-media-object/
│   ├── 29-responsive-float/ & 30-interactions/
│   ├── 31-link-opacity/ to 33-color-links/
│   ├── 34-object-fit/ & 35-object-fit-responsive/
│   ├── 36-opacity/ & 37-overflow/
│   ├── 38-postion/ to 42-pos-exm-two/
│   ├── 43-shadow/
│   ├── 44-sizing/ & 45-gap/
│   ├── 46-text-align/ to 55-text-decoration/
│   ├── 56-vertical-alignment/
│   ├── 57-visibility/
│   └── 58-z-index/
├── Section8 Project One/
│   ├── index.html            # Authentication / Login Page
│   ├── dash.html             # Main EMS Admin Dashboard
│   ├── employees-list.html   # Employee Directory with Modals & Table
│   └── jobs-list.html        # Job Management Directory
├── Section9 Project Two/
│   ├── img/
│   │   ├── Banner.jpg        # Hero Header Banner Image
│   │   └── post-image.jpg    # Featured Post Thumbnail Image
│   ├── default.html          # Default Layout Template
│   ├── index.html            # Blog Homepage with Hero Banner & Posts Grid
│   ├── page.html             # Single Static Page Template
│   ├── posts.html            # Single Article Details & Comments Section
│   ├── search.html           # Search Results & Filter Page
│   └── style.css             # Custom Styles & Glassmorphism Navigation
└── Section10 Project Three/
    ├── index.html            # Project 3 Workspace Entry
    └── styles.css            # Project 3 Custom Stylesheet
```

---

## 📖 Sections Breakdown

### Section 1: Bootstrap Setup & Basics
- **01-hello-world**: Bootstrap 5 setup via CDN (`bootstrap.min.css` & `bootstrap.bundle.min.js`), viewport meta configuration, and starter boilerplate testing.

---

### Section 2: Layout & Grid System
Deep dive into Bootstrap's 12-column responsive grid engine and containers:
- **Containers**: Responsive fixed `.container` vs fluid `.container-fluid`.
- **Grid Options**: Responsive column scaling (`col-sm`, `col-md`, `col-lg`, `col-xl`).
- **Nested Rows**: Nesting rows inside existing columns for complex layouts.
- **Alignment Utilities**: Vertical alignment (`align-items-*`) and horizontal justification (`justify-content-*`).
- **Column Wrapping & Offsets**: Multi-row wrapping, column offset classes (`offset-md-*`), and visual reordering (`order-*`).
- **Margin Auto Utilities**: Flex-based spacing inside grid rows (`ms-auto`, `me-auto`).
- **Gutters**: Controlling horizontal (`gx-*`), vertical (`gy-*`), and unified (`g-*`) spacing between columns.

---

### Section 3: Contents
Styling foundational typography and HTML content elements:
- **Typography & Inline Elements**: Display headings (`display-1` to `display-6`), lead text (`.lead`), mark, text strike, small, and bold text.
- **Blockquotes**: Quotations styling and cite footers (`.blockquote-footer`).
- **Lists**: Unstyled lists (`.list-unstyled`) and inline list items (`.list-inline`).
- **Images & Figures**: Fluid responsive images (`.img-fluid`), thumbnails (`.img-thumbnail`), and figure captions.
- **Tables**: Striped, bordered, borderless, dark, hoverable tables, and vertically aligned table cells (`.align-middle`).

---

### Section 4: Forms
Modern, accessible, and responsive form components:
- **Form Controls & Sizing**: Standard input controls, sizing (`.form-control-lg`, `.form-control-sm`), and disabled/readonly states.
- **Checks, Radios & Switches**: Custom styled checkboxes, radio buttons, and toggle switches (`.form-switch`).
- **Range & Input Groups**: Range sliders and prepend/append input addons (`.input-group-text`).
- **Floating Labels**: Animated floating placeholder labels (`.form-floating`).
- **Form Layouts**: Horizontal forms, auto-sizing columns, inline forms, and responsive form grids.
- **Form Validation**: Native HTML5 and custom client-side validation states (`.was-validated`, `.is-valid`, `.is-invalid`, `.valid-feedback`, `.invalid-feedback`).

---

### Section 5: Components
Interactive, reusable Bootstrap UI components:
- **Accordions (`01`)**: Collapsible accordion panels (`.accordion`, `.accordion-item`, `.accordion-button`).
- **Alerts & Links (`02`)**: Contextual alert boxes (`.alert-*`) with styled inline hyperlinks (`.alert-link`).
- **Dismissible Alerts (`03`)**: Interactive dismissible alerts with smooth fade transitions (`.alert-dismissible`, `.btn-close`).
- **Badges (`04`)**: Notification counters, contextual badges, and pill tags (`.badge`, `.rounded-pill`).
- **Breadcrumbs (`05`)**: Navigation trail indicators for page hierarchy (`.breadcrumb`, `.breadcrumb-item`).
- **Buttons & Grids (`06`)**: Contextual and outline buttons (`.btn-*`, `.btn-outline-*`), size variants (`.btn-lg`, `.btn-sm`), and full-width block buttons via grid wrappers (`d-grid gap-2`).
- **Button Groups & Toolbars (`07`, `08`)**: Grouping buttons together (`.btn-group`), combining multiple button groups with input groups into unified toolbars (`.btn-toolbar`).
- **Button Sizing & Orientation (`09`)**: Large/small button groups and vertical stacking (`.btn-group-vertical`).
- **Practice Modules (`10` to `26`)**: Component hands-on practice modules.

---

### Section 6: Helpers Bootstrap
Specialized helper classes that streamline common UI tasks:
- **Clearfix**: Clearing floated elements with `.clearfix`.
- **Color & Background Helpers**: Text and background color styling helper utilities.
- **Colored Links & Link Utilities**: Underline styling, link offset, and hover states (`.link-offset-*`, `.link-underline-*`).
- **Focus Ring & Icon Link**: Accessible focus outlines and animated icon links.
- **Ratio**: Responsive 16:9, 4:3, and 1:1 aspect ratio containers for videos and iframes (`.ratio`).
- **Position Helpers**: Sticky (`.sticky-top`) and fixed (`.fixed-top`, `.fixed-bottom`) elements.
- **Stacks**: Vertical (`.vstack`) and horizontal (`.hstack`) flex stack wrappers.
- **Visually Hidden**: Screen reader-only utility (`.visually-hidden`).
- **Stretched Link**: Making an entire card or containing block clickable (`.stretched-link`).
- **Text Truncation**: Single-line text ellipsis helper (`.text-truncate`).

---

### Section 7: Utilities
Comprehensive reference of Bootstrap 5 atomic utility classes:
- **Backgrounds & Borders**: Color palettes, gradients, opacity control, border widths, colors, and rounded corners (`rounded-pill`, `rounded-circle`).
- **Colors & Opacity**: Contextual text colors and text opacity utilities.
- **Display & Visibility**: Display modes (`d-none`, `d-block`, `d-flex`, `d-print-none`), visibility toggling.
- **Flexbox Mastery**: Complete flex utilities including direction (`flex-row`, `flex-column`), justify content, align items, self alignment, flex fill, grow/shrink, auto-margins, wrapping, order, and media objects.
- **Object Fit & Overflow**: Object-fit responsive controls (`object-fit-cover`, `object-fit-contain`), overflow clipping and scrollbars.
- **Positioning**: Absolute/relative positions, centering utilities (`translate-middle`), coordinate offsets (`top-0`, `start-50`, etc.), and z-index layers.
- **Spacing & Sizing**: Width/height percentage classes (`w-100`, `h-100`, `mw-100`), auto margins, and gap utilities.
- **Typography Utilities**: Text alignment, wrapping, line breaks, text transform (uppercase, lowercase, capitalize), font weights, italics, line height, and monospace fonts.

---

### Section 8: Project One - EMS 2.0 (Employee Management System)

[![Live Demo](https://img.shields.io/badge/Live_Demo-Visit_EMS_2.0-0070F3?style=for-the-badge&logo=vercel&logoColor=white)](https://ems-web-kappa.vercel.app/)

A complete, responsive multi-page administrative web application built using Bootstrap 5:
- **`index.html` (Authentication)**: Clean login page featuring floating labels, remember-me checkbox, gradient text branding, and shadow cards.
- **`dash.html` (Dashboard)**: Central operations dashboard equipped with:
  - Dark responsive top navigation bar with collapse toggle and profile dropdown.
  - Key performance metric cards (Employees count, Open Jobs, Pending Applications).
  - Quick action buttons and recent activities list.
- **`employees-list.html` (Employee Directory)**:
  - Tabular list of registered employees with status badges.
  - Interactive "Add Employee" modal with structured form inputs.
  - Action buttons for editing, viewing, and deleting employee records.
  - Responsive pagination controls.
- **`jobs-list.html` (Job Postings Management)**:
  - Active job positions overview table with department tags and application counts.
  - "Add Job" modal form for posting new openings.
  - Filterable layout and management actions.

---

### Section 9: Project Two - BLOG 2.0 (Modern Responsive Blog Platform)

[![Live Demo](https://img.shields.io/badge/Live_Demo-Visit_BLOG_2.0-0070F3?style=for-the-badge&logo=vercel&logoColor=white)](https://blog-app-jet-ten-12.vercel.app/)

A full-featured, responsive multi-page modern blog platform:
- **`index.html` (Homepage)**:
  - Fixed-top frosted glass navbar with search bar and mobile toggle (`custom-nav` with backdrop blur).
  - Hero banner with custom gradient branding (`BLOG2.0`).
  - Featured article feed with category tags, author metadata, read-more links, and pagination.
  - Interactive newsletter subscription modal trigger.
  - Sidebar with author profile card, category pills, tags, and search widget.
- **`posts.html` (Single Post)**:
  - Formatted article view with full headers, typography hierarchy, blockquotes, and featured post media.
  - Author bio box with avatar and profile summary.
  - Comment submission form with real-time responsive discussion threads.
- **`page.html` (Static Page)**:
  - Clean generic page template suited for static content (About Us, Privacy Policy, Terms).
- **`search.html` (Search Results)**:
  - Search query header with matching post card results, sidebar filters, and pagination.
- **`default.html` (Default Layout Template)**:
  - Base blueprint combining navigation, hero header, loop area, sidebar, and multi-column footer.
- **`style.css`**:
  - Custom CSS styling featuring multi-stop gradient branding (`.brand-gradient`), responsive cover banner (`.banner-holder`), and glassmorphism navbar (`.custom-nav`).
- **`img/`**:
  - Project image assets (`Banner.jpg`, `post-image.jpg`).

---

### Section 10: Project Three - Setup & Workspace
- **`index.html` & `styles.css`**: Clean starter workspace and custom stylesheet ready for Project Three development.

---

## 🚀 How to Run & Preview

1. **Clone or Download** the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/Bootstrap.git
   ```
2. **Open in VS Code**:
   ```bash
   code .
   ```
3. **Launch in Browser**:
   - Right-click any `.html` file (e.g., `Section9 Project Two/index.html` or `Section8 Project One/dash.html`) and select **Open with Live Server**, or double-click the file in File Explorer to open it in your default web browser.
