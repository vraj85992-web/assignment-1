# Student Portal

A simple college Student Portal webpage built with **HTML** and introductory **CSS** as a lab assignment.

**Author:** Vijay Raj
**Student ID:** 26BCS10792
**Program:** CS&AI, 1st Year
**Email:** vijay.26bcs10792@sst.scaler.com

---

## Overview

The page lets a student:

1. View their profile
2. See their skills
3. View their weekly class schedule
4. Register for a course

## Project Structure

```text
.
├── student-portal.html   # The complete page (HTML + CSS in a <style> element)
└── README.md
```

## How to Run

No installation or build step is needed.

1. Download `student-portal.html`.
2. Double-click it, or right-click and choose **Open with** your browser.

## Features

### HTML

- Complete document structure: `<!DOCTYPE html>`, `<html>`, `<head>`, `<title>`, `<body>`
- Semantic layout: `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`
- Navigation links (Home, Profile, Courses, Register) that jump to sections on the same page
- **Student Profile** table using `<th>` and `<td>`
- **My Skills** unordered list
- **Weekly Schedule** table (Monday to Friday)
- **Course Registration** form with:
  - Text inputs for name and student ID, and an email input
  - Course `<select>` dropdown with a default "Select Course" option
  - Radio buttons for learning mode (Online / Offline), grouped with a shared `name`
  - Checkboxes for known skills (HTML, CSS, JavaScript, Python)
  - Submit and Reset buttons
  - `<label>` elements linked to every control

### CSS

- `color` and `background-color` properties
- **Element selectors:** `body`, `h1`, `h2`, `header`, `footer`, `th`
- **Class selectors:** `.highlight` (important info) and `.badge` (bonus badge)
- **ID selector:** `#student-name`

### Bonus

A **Top Performer** badge next to the student's name, built with a `<span>` and the `.badge` class.

## Lab Rules Followed

- HTML and CSS only
- No JavaScript
- No Bootstrap, Tailwind, or other CSS frameworks
- No Flexbox or Grid

## Verification Checklist

- [x] All sections are visible
- [x] Tables display correctly
- [x] Form controls work
- [x] Radio buttons behave as one group
- [x] CSS colors are applied
- [x] No obvious HTML errors

## Resources

- [MDN Web Docs](https://developer.mozilla.org/) for HTML and CSS syntax reference
