# Newsletter Sign-Up Page

A responsive newsletter sign-up page built with **HTML5 and CSS3**. The project features a clean two-column desktop layout that adapts to mobile devices, along with interactive form styling and responsive design.

## Live Demo

[View Live Demo](https://ishratalib.github.io/NewsLetterCard/)

## Technologies Used

* **HTML5** — Page structure and form elements
* **CSS3** — Styling, layout, and responsive design
* **CSS Flexbox** — Page and content layout
* **CSS Media Queries** — Responsive design
* **CSS Pseudo-elements** — Custom feature-list icons
* **CSS Pseudo-classes** — `:hover`, `:focus`, and `:not(:placeholder-shown)`
* **SVG** — Illustration and list icons
* **HTML5 Form Validation** — Email validation and required fields

---

## Features

* Newsletter email sign-up form
* Built-in email validation using HTML5
* Required email field validation
* Interactive input focus state
* Gradient button hover effect
* Button styling changes when the user enters text
* Responsive design for desktop, tablet, and mobile
* Custom SVG illustration
* Custom feature-list icons
* Card shadow and rounded-corner design
* Responsive layout using CSS media queries

---

## Project Structure

```text
Newsletter Sign-Up/
│
├── index.html
├── main.css
│
└── images/
    ├── illustration-sign-up-desktop.svg
    └── icon-list.svg
```

---

## File Overview

### `index.html`

Contains the main structure of the newsletter page, including:

* Newsletter heading
* Newsletter description
* Feature list
* Email input
* Subscribe button
* Newsletter illustration

The email field uses native HTML5 validation:

```html
<input
  type="email"
  id="email"
  placeholder="email@company.com"
  required
/>
```

### `main.css`

Contains the styling for the complete page, including:

* Desktop layout
* Flexbox positioning
* Typography
* Colors
* Form styling
* Input states
* Button hover effects
* Shadows
* Border radius
* Responsive breakpoints

The project uses media queries at:

```text
768px
320px
```

to adjust the layout for smaller screens.

### `images/`

Contains the SVG assets used by the page:

* `illustration-sign-up-desktop.svg` — Main newsletter illustration
* `icon-list.svg` — Icons displayed beside the feature-list items

---

## How to Run Locally

This is a **static frontend project**, so no PHP, Node.js, database, or backend setup is required.

### 1. Clone the Repository

Open your terminal and run:

```bash
git clone "YOUR_REPOSITORY_URL"
```

**For example:**

```bash
git clone https://github.com/Ishratalib/NewsLetterCard.git
```

Then move into the project folder:

```bash
cd NewsLetterCard
```

You can also download the project as a ZIP file and extract it.

### 2. Open the Project

Make sure the following files and folder remain together:

```text
index.html
main.css
images/
```

The image paths in the project depend on this folder structure.

### 3. Run the Project

You can simply open:

```text
index.html
```

directly in your browser.

For development, **VS Code Live Server** is recommended:

1. Open the project folder in VS Code.
2. Install the **Live Server** extension.
3. Right-click `index.html`.
4. Select **Open with Live Server**.
5. The project will open in your browser.

---

## Responsive Design

The page adapts to different screen sizes using CSS media queries.

### Desktop

The newsletter content and illustration are displayed side by side.

### Mobile

The layout changes to a vertical design, with the illustration positioned above the newsletter content.

The responsive design adjusts:

* Page layout
* Image height
* Heading size
* Padding
* Card border radius
* Shadows

---

## Interactive Styling

The email input has multiple visual states.

### Focus State

When the user clicks inside the input, the input border changes.

```css
.signup-form input:focus
```

### Typed State

When the user enters text, the input changes its border, background, and text styling using:

```css
.signup-form input:not(:placeholder-shown)
```

The subscribe button also changes to a gradient when the input contains text.

### Hover State

When the user hovers over the subscribe button, a gradient background and shadow effect are applied.

---

## Form Validation

The project uses **native HTML5 form validation** rather than JavaScript.

The email field includes:

```html
type="email"
required
```

The browser checks that:

* The email field is not empty.
* The entered value follows an email format.

> **Note:** This project currently provides the frontend newsletter form and validation. It does not include a backend for storing newsletter subscriptions or sending emails.

---

## Project Purpose

This project was built to practice:

* HTML5 structure
* Form creation
* CSS Flexbox
* Responsive web design
* CSS media queries
* CSS pseudo-classes
* CSS pseudo-elements
* HTML5 form validation
* SVG assets
* Interactive UI states
* Responsive layout adjustments

---

## Author

**Ishrat Talib**

Frontend Web Development Project
