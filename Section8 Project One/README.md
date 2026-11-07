# Section 8: Project One — EMS 2.0 (Employee Management System)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap 5](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

[⬅ Back to Main README](../README.md)

---

## 🌐 Live Demo

[![Live Demo](https://img.shields.io/badge/Live_Demo-Visit_EMS_2.0-0070F3?style=for-the-badge&logo=vercel&logoColor=white)](https://ems-web-kappa.vercel.app/)

**Live URL**: [https://ems-web-kappa.vercel.app/](https://ems-web-kappa.vercel.app/)

---

## 📌 Overview

**EMS 2.0** is a full-featured, responsive administrative web application built with **Bootstrap 5.3**. It simulates an enterprise employee and job management dashboard with authentication, analytics cards, employee directories, and vacancy management.

---

## 📸 Screenshots & Interface Previews

| 🔐 Login Authentication | 📊 Admin Operations Dashboard |
| :---: | :---: |
| [![EMS Login](ReadmeImages/emsLogIn.png)](https://ems-web-kappa.vercel.app/) | [![EMS Dashboard](ReadmeImages/emsMain.png)](https://ems-web-kappa.vercel.app/) |

| 👥 Employee Directory & Modal Form | 💼 Job Postings & Hiring Directory |
| :---: | :---: |
| [![EMS Employees](ReadmeImages/emsEmp.png)](https://ems-web-kappa.vercel.app/) | [![EMS Jobs](ReadmeImages/emsJob.png)](https://ems-web-kappa.vercel.app/) |

---

## 📂 Directory Structure

```text
Section8 Project One/
├── ReadmeImages/
│   ├── emsLogIn.png          # Login Screen Preview
│   ├── emsMain.png           # Dashboard Preview
│   ├── emsEmp.png            # Employees Table & Modal Preview
│   └── emsJob.png            # Jobs Directory Preview
├── index.html                # Authentication Login Page
├── dash.html                 # Central Admin Dashboard
├── employees-list.html       # Employee Directory Table & Modal
└── jobs-list.html            # Job Openings Directory
```

---

## 📖 Page Architecture & Features

### 1. `index.html` — Authentication Page
- Centered card layout using grid utilities (`row justify-content-center`, `col-md-4`).
- Floating input fields (`.form-floating`) for username and password.
- "Remember Me" checkbox with custom styling.
- Linear gradient brand header (`.brand-gradient`).
- Shadow styling with `.shadow-lg`.

### 2. `dash.html` — Operations Dashboard
- Dark fixed navbar with branding, mobile toggle collapse, and avatar dropdown.
- Performance metric cards displaying active employee counts, open positions, and applicants.
- Quick action buttons (Add Employee, Post Job).
- Recent activity data table.

### 3. `employees-list.html` — Employee Directory
- Filterable and responsive data table with striped rows (`.table-striped`, `.table-hover`).
- Contextual badge indicators for employment status (Active, On Leave, Remote).
- Interactive Bootstrap Modal (`#add_employee`) with structured inputs for employee details.
- Edit, View, and Delete action button groups.
- Responsive pagination controls.

### 4. `jobs-list.html` — Job Vacancy Management
- Job positions directory with department tags, location badges, and applicant counters.
- "Add Job" modal form for publishing new openings.
- Responsive table layout with action buttons.

---

## 🚀 How to Run Locally

1. Open `Section8 Project One` in VS Code.
2. Right-click `index.html` and select **Open with Live Server**.
3. Log in to navigate through `dash.html`, `employees-list.html`, and `jobs-list.html`.

