
# 📘 Community Library Website – README

This README explains all files, pages, and features of your Community Library Website project. Use this as documentation for submission or GitHub.

---

## 📂 Project Structure

```
project-folder/
│
├── index.html
├── catalog.html
├── events.html
├── account.html
├── help.html
├── admin.html
├── gallery.html  (if added)
├── services.html (if added)
├── style.css
│
└── assets/
      ├── Reading area.jpg
      ├── Digital library.jpeg
      ├── Events.jpeg
      ├── (your gallery images)
      └── videos/
```

---

## 🏠 1. index.html (Home Page)

**Purpose:** Welcome page of the library.

**Contains:**

* Header + navigation menu
* About section
* Library facilities section with images
* Footer with copyright

**Features:**

* Semantic HTML tags (header, nav, section, figure, footer)
* Skip to main content for accessibility

---

## 📚 2. catalog.html (Book Catalog)

**Purpose:** Displays available books.

**Contains:**

* List of books
* Category sections
* Possible search bar (optional)

**Key Elements:**

* `<section>` for categories
* `<table>` or `<ul>` for book lists

---

## 🎉 3. events.html (Library Events)

**Purpose:** Shows upcoming events.

**Contains:**

* Event name
* Date & time
* Description

**Key Elements:**

* Cards or list format
* Images for events

---

## 📝 4. account.html (Membership / Registration Form)

**Purpose:** Allows users to register.

**Contains:**

* Input fields: name, email, age, membership
* Submit/reset buttons

**Key Elements:**

* `<form>` with `<fieldset>`
* Required attributes

---

## ❓ 5. help.html (Help / FAQs)

**Purpose:** General information and FAQs for users.

**Contains:**

* FAQ list
* Contact information
* Support section

---

## 🛠️ 6. admin.html (Admin Page)

**Purpose:** Admin-only page to manage library info.

**Contains:**

* Admin table
* Buttons for updating records

**Key Elements:**

* Simple layout
* Clean navigation

---

## 🖼️ 7. gallery.html (Media Gallery)

**Purpose:** Displays images and videos in a clean layout.

**Contains:**

* Masonry/grid-style image gallery
* Hover animations (zoom/fade)
* Video player with poster image
* Light/dark theme toggle using CSS variables only
* `<picture>` for responsive images

---

## 🎨 style.css (External CSS)

**Purpose:** Styling for all pages.

**Contains:**

* Global styles (body, headings, fonts)
* Navigation bar styling
* Layout and spacing
* Buttons and forms
* Gallery grid + hover animations
* Light/dark mode using `:root` custom properties

Example variables:

```css
:root {
  --bg-color: #ffffff;
  --text-color: #222;
  --card-bg: #f5f5f5;
}
```

---

## 📁 assets/ (Images & Videos)

Store all images and videos here.

Examples:

* Reading area
* Digital library
* Event photos
* Gallery images
* Thumbnails for videos

🔗 GitHub Repository Link
https://tmahitha06.github.io/Library-site/
---
