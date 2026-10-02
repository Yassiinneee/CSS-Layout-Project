# 🏥 Docplanner Website Reproduction

A professional, responsive healthcare platform landing page developed from scratch using **HTML5 and CSS3**.

This project was created as part of a front-end development checkpoint focused on website reproduction, semantic HTML, responsive layouts, CSS architecture, visual design and best practices.

> **Educational Project:** This is an independent educational reproduction inspired by the Docplanner website reference. It is not an official Docplanner product and is not affiliated with Docplanner.

---

# 📋 Table of Contents

- [Project Overview](#-project-overview)
- [Objectives](#-objectives)
- [Features](#-features)
- [Technologies](#-technologies)
- [Project Structure](#-project-structure)
- [Page Sections](#-page-sections)
- [Responsive Design](#-responsive-design)
- [Design System](#-design-system)
- [Accessibility](#-accessibility)
- [Images](#-images)
- [Installation](#-installation)
- [Running the Project](#-running-the-project)
- [Testing](#-testing)
- [Best Practices](#-best-practices)
- [Future Improvements](#-future-improvements)
- [Author](#-author)
- [License](#-license)

---

# 📌 Project Overview

The goal of this project is to reproduce the structure and visual experience of a modern healthcare platform using only standard front-end technologies.

The project demonstrates how a professional landing page can be developed without relying on Bootstrap, Tailwind CSS or JavaScript frameworks.

The implementation includes:

- Responsive navigation
- Hero section
- Healthcare service cards
- Platform statistics
- Global office locations
- Real city photography
- Career call-to-action
- Professional footer
- Responsive layouts
- Hover animations
- Accessibility features

---

# 🎯 Objectives

The main objectives of this checkpoint are to demonstrate the ability to:

1. Analyze an existing webpage.
2. Divide the interface into logical sections.
3. Create semantic HTML5.
4. Build reusable CSS components.
5. Use Flexbox.
6. Use CSS Grid.
7. Implement responsive layouts.
8. Create interactive hover states.
9. Apply professional spacing and typography.
10. Organize a front-end project professionally.

---

# ✨ Features

## Navigation

The navigation contains:

- Brand logo
- About Us
- Departments
- Careers

The header uses a sticky layout so the navigation remains accessible while scrolling.

---

## Hero Section

The hero section contains:

- Healthcare icon
- Main heading
- Supporting content
- Responsive typography

The design focuses on simplicity and readability.

---

## Healthcare Services

Three main service cards are provided:

### 👤 Patients

A dedicated area representing healthcare services for patients.

### 🩺 Doctors

A dedicated area representing tools and services for doctors.

### 🏥 Clinics

A dedicated area representing solutions for healthcare organizations.

Each card includes:

- Icon
- Category
- Heading
- Description
- Call-to-action
- Hover animation

---

# 🌍 Global Platform

The platform section contains four statistical cards:

```text
13+       Countries

20M+      Patients

10M+      Appointments

100K+     Healthcare professionals
```

The statistics are presented as UI content for the educational reproduction and should not be interpreted as current official Docplanner statistics.

---

# 🌎 Office Locations

The project contains six beautiful city cards:

| City | Country |
|---|---|
| Warsaw | 🇵🇱 Poland |
| Barcelona | 🇪🇸 Spain |
| Istanbul | 🇹🇷 Turkey |
| Mexico City | 🇲🇽 Mexico |
| Rome | 🇮🇹 Italy |
| Lisbon | 🇵🇹 Portugal |

Each card contains:

- City photograph
- Country badge
- City name
- Country name
- Career link
- Image zoom animation
- Card hover animation

---

# 🖼️ Images

City images are stored locally:

```text
images/
└── cities/
    ├── warsaw.jpg
    ├── barcelona.jpg
    ├── istanbul.jpg
    ├── mexico-city.jpg
    ├── rome.jpg
    └── lisbon.jpg
```

Using local images instead of remote image URLs provides several advantages:

- Better project portability
- No dependency on external image URLs
- Better control over image quality
- Easier GitHub deployment
- More predictable loading
- Better long-term project stability

### Image recommendations

Recommended dimensions:

```text
1200 × 800 px
```

Recommended format:

```text
JPG
WebP
```

For production, WebP or AVIF can be considered for improved performance.

---

# 🧱 Project Structure

```text
docplanner-clone/
│
├── index.html
│
├── css/
│   └── style.css
│
├── Screenshots
│
└── README.md
```

---

# 🛠️ Technologies

| Technology | Purpose |
|---|---|
| HTML5 | Semantic structure |
| CSS3 | Styling |
| CSS Grid | Responsive layouts |
| Flexbox | Alignment |
| CSS Variables | Design system |
| Media Queries | Responsive design |
| Git | Version control |
| GitHub | Repository hosting |
| VS Code | Development environment |

No framework is required.

---

# 🎨 Design System

The project uses CSS custom properties.

Example:

```css
:root {
    --primary: #00b39b;
    --secondary: #3d83df;
    --dark: #1f2937;
    --text: #5f6b7a;
    --background-soft: #f6f8fa;
}
```

This approach provides:

- Consistent colors
- Easier maintenance
- Reusable design values
- Faster theme modifications
- Cleaner CSS

---

# 📱 Responsive Design

The interface supports multiple screen sizes.

## Desktop

```text
1200px+
```

Three-column cards and the complete desktop layout are displayed.

## Tablet

```text
768px – 991px
```

The layout adapts to two-column structures.

## Mobile

```text
≤ 700px
```

The website switches to a single-column layout.

## Small Mobile

```text
≤ 420px
```

Typography, navigation and image heights are further optimized.

---

# 🎞️ Animations

The project includes lightweight CSS animations.

### Service cards

```css
transform: translateY(-8px);
```

### City images

```css
transform: scale(1.08);
```

### Office cards

```css
transform: translateY(-8px);
```

### Links

The arrows move smoothly when the user hovers over the link.

These animations are implemented entirely with CSS.

---

# ♿ Accessibility

Accessibility has been considered throughout the implementation.

The project uses:

- Semantic HTML
- Descriptive image `alt` attributes
- Proper heading hierarchy
- Accessible navigation
- Keyboard focus indicators
- Reduced-motion support
- Logical page sections

Example:

```html
<img
    src="images/cities/warsaw.jpg"
    alt="Warsaw skyline in Poland"
>
```

---

# ⚡ Performance

The project intentionally avoids unnecessary dependencies.

There is:

- No frontend framework
- No CSS framework
- No external UI library
- No package manager requirement
- No unnecessary JavaScript

City images use:

```html
loading="lazy"
```

which allows images below the initial viewport to load lazily.

---

# 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/docplanner-clone.git
```

Enter the project directory:

```bash
cd docplanner-clone
```

Open the project:

```bash
code .
```

---

# ▶️ Running the Project

Because this is a static HTML/CSS project, no Node.js installation is required.

The simplest solution is to open:

```text
index.html
```

directly in your browser.

For development, using VS Code Live Server is recommended.

---

# 🔥 Live Server

Install the VS Code extension:

```text
Live Server
```

Then:

1. Open `index.html`.
2. Right-click inside the file.
3. Select **Open with Live Server**.
4. The website will open in your browser.

---

# 🧪 Testing Checklist

Before submitting the project:

- [ ] Header displays correctly.
- [ ] Navigation links work.
- [ ] Hero section is responsive.
- [ ] Service cards display correctly.
- [ ] Platform statistics display correctly.
- [ ] All six city images load correctly.
- [ ] City cards have hover effects.
- [ ] Country badges are visible.
- [ ] Footer displays correctly.
- [ ] No horizontal scrolling exists.
- [ ] Mobile layout works.
- [ ] Tablet layout works.
- [ ] Desktop layout works.
- [ ] Images have meaningful `alt` text.
- [ ] No console errors exist.
- [ ] No broken image paths exist.

---

# 🔎 Browser Testing

Recommended browsers:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

Recommended viewport testing:

```text
1920 × 1080
1440 × 900
1280 × 720
1024 × 768
768 × 1024
390 × 844
375 × 667
360 × 800
```

---

# 📐 CSS Architecture

The stylesheet is organized into clearly separated sections:

```text
01. Design System
02. Reset
03. Global
04. Header
05. Hero
06. Services
07. Platform
08. Offices / City Cards
09. Careers
10. Footer
11. Tablet
12. Mobile
13. Small Mobile
14. Accessibility
15. Reduced Motion
```

This organization improves maintainability and makes debugging easier.

---

# 💡 Best Practices Applied

## Semantic HTML

The project uses:

```html
<header>
<nav>
<main>
<section>
<article>
<footer>
```

instead of creating the entire page with generic `<div>` elements.

---

## CSS Variables

Colors and design values are centralized.

---

## Responsive Design

The interface adapts to different viewport sizes.

---

## Reusable Components

Service cards, statistics cards and city cards use reusable CSS patterns.

---

## Accessibility

Focus states and reduced-motion preferences are supported.

---

## Performance

Images are loaded lazily and unnecessary dependencies are avoided.

---

# 🔐 Security Considerations

This project is a static educational frontend.

A future production implementation should additionally consider:

- HTTPS
- Content Security Policy
- Secure external resources
- Input validation
- Output encoding
- XSS protection
- Secure authentication
- API security
- Dependency security

---

# 🔮 Future Improvements

Possible future improvements include:

- Mobile hamburger menu
- JavaScript interactions
- Search functionality
- Language selector
- Dark mode
- Real appointment system
- Contact form
- Authentication
- Backend API
- Database integration
- Dynamic city data
- CMS integration
- Accessibility auditing
- Lighthouse optimization
- Automated testing
- CI/CD deployment

---

# 📊 Lighthouse Targets

Future production optimization can target:

| Category | Target |
|---|---:|
| Performance | 90+ |
| Accessibility | 90+ |
| Best Practices | 90+ |
| SEO | 90+ |

These are development targets, not guaranteed scores.

---

# 📚 Reference

The project was developed using the website reference supplied in the checkpoint instructions:

```text
https://www.docplanner.com/
```

An alternative educational reference was also provided:

```text
https://docplanner-gomycode.onrender.com/
```

---

# 👨‍💻 Author

## Yassine Kaltoum

**Network & Software Engineer**

Areas of interest:

- Software Engineering
- Web Development
- Network Engineering
- Systems Engineering
- Cybersecurity

---

# 📄 License

This project is intended for educational purposes.

The implementation is an independent learning project inspired by the provided website reference and does not represent an official Docplanner application.

---

# ⭐ Project Status

```text
Status       : Completed
Project Type : Front-End Educational Project
Level        : Professional Student Implementation
HTML         : HTML5
CSS          : CSS3
JavaScript   : Not required
Framework    : None
Responsive   : Yes
Accessibility : Included
Images       : Local city photography
```

---

# 🚀 Development Workflow

```text
Website Analysis
       ↓
Layout Planning
       ↓
Semantic HTML5
       ↓
CSS Design System
       ↓
Flexbox + CSS Grid
       ↓
Responsive Design
       ↓
City Photography
       ↓
Hover Animations
       ↓
Accessibility
       ↓
Browser Testing
       ↓
Git / GitHub
       ↓
Professional Documentation
```

---

## 🎓 Checkpoint Completion

This project demonstrates the core front-end skills required for the checkpoint:

```text
HTML Structure          ✅
CSS Styling             ✅
Div / Section Layout    ✅
Flexbox                 ✅
CSS Grid                ✅
Responsive Design       ✅
Beautiful Images        ✅
Hover Effects           ✅
Semantic HTML           ✅
Accessibility           ✅
Professional README     ✅
GitHub Ready            ✅
```
