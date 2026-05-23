# 🏷️ Tunz – Brand Showcase

> A fully responsive, single-file HTML webpage demonstrating personal and corporate brand identities — built with **pure HTML, CSS, and vanilla JavaScript**.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Live Preview](#live-preview)
- [Features](#features)
- [Brand Sections](#brand-sections)
- [HTML Elements Covered](#html-elements-covered)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Responsive Breakpoints](#responsive-breakpoints)
- [Design System](#design-system)
- [Accessibility](#accessibility)
- [Learning Outcomes](#learning-outcomes)
- [Assets & Credits](#assets--credits)
- [License](#license)

---

## Overview

**Tunz** is a comprehensive brand showcase webpage created as a full demonstration of core HTML concepts, semantic markup, and modern CSS layout techniques. It features four distinct brand identities — a personal brand, a university, a luxury hotel, and a car dealership — presented within a cohesive, production-quality design.

The project is intentionally built as a **single `.html` file** with no external CSS frameworks or JavaScript libraries, making it ideal as a learning reference for HTML fundamentals.

```
File:     brand_showcase.html
Size:     ~18KB (excluding external images)
Type:     Single-page HTML document
Stack:    HTML5 · CSS3 (inline) · Vanilla JS (inline)
```

---

## Live Preview

Open the file directly in any modern web browser — no server or build step required.

```bash
# macOS
open brand_showcase.html

# Windows
start brand_showcase.html

# Linux
xdg-open brand_showcase.html
```

---

## Features

| Feature | Details |
|---|---|
| ✅ Responsive Design | Fluid layouts from 320px to 1440px+ |
| ✅ Semantic HTML5 | Full use of landmark and content elements |
| ✅ Sticky Navigation | Frosted-glass navbar with smooth scroll links |
| ✅ Scroll Animations | IntersectionObserver-powered reveal effects |
| ✅ Animated Counters | Stats bar counts up on scroll into view |
| ✅ Interactive Form | Fieldsets, radio buttons, checkboxes, `<select>` with `<optgroup>` |
| ✅ Data Table | Full `<table>` with `<caption>`, `<thead>`, `<tbody>`, `<tfoot>` |
| ✅ FAQ Accordion | Native `<details>` / `<summary>` elements |
| ✅ Image Gallery | CSS Grid masonry-style layout with hover captions |
| ✅ External Fonts | Google Fonts — Playfair Display + DM Sans |
| ✅ Online Images | Unsplash CDN — no local assets needed |

---

## Brand Sections

### 1. 🙋 Personal Brand — *Alex Morgan*
A brand strategist and creative director profile featuring:
- Sticky profile card with photo, role, bio, and social links
- Animated skill bars (Brand Strategy, Visual Identity, Social Media, etc.)
- Career timeline using `<ol>`, `<time>`, and semantic markup
- Pull quote in a `<blockquote>` with `<cite>`

### 2. 🎓 Corporate Brand — *Meridian University*
An educational institution brand featuring:
- Campus hero image with accreditation badge overlay
- Grid of six academic programme cards with icons and duration
- Use of `<abbr>`, `<time>`, and descriptive `<figcaption>`
- Themed in a deep blue palette to differentiate from other sections

### 3. 🏨 Corporate Brand — *The Auric Pavilion Hotel*
A five-star hotel brand featuring:
- Full-width cinematic hero banner with overlaid text and CTA
- Three room type cards (Deluxe Suite, Presidential Suite, Garden Bungalow) with pricing
- Eight amenity tiles with emoji icons
- Star rating, nightly rates, and reservation call-to-action

### 4. 🚘 Corporate Brand — *Apex Motors Dealership*
A premium automotive dealership featuring:
- Four vehicle cards: BMW 5 Series, Mercedes GLE, Porsche 911, Rolls-Royce Ghost
- Car specs (engine, power, 0–100, drivetrain) in structured layout
- Type badges (Sedan, SUV, Sports, Ultra-Luxury) as overlaid labels
- Hover effects and enquiry call-to-action buttons

---

## HTML Elements Covered

### Document Structure
```html
<!DOCTYPE html>  <html>  <head>  <body>
<header>  <nav>  <main>  <section>  <article>
<aside>  <footer>  <div>  <span>
```

### Metadata (Head)
```html
<meta charset>  <meta name="viewport">  <meta name="description">
<meta name="keywords">  <meta name="author">
<meta property="og:title">  <meta property="og:type">
<title>  <link rel="preconnect">  <style>
```

### Headings & Text
```html
<h1>  <h2>  <h3>  <h4>  <h5>  <h6>
<p>  <strong>  <em>  <small>  <span>
<mark>  <ins>  <del>  <sub>  <sup>
<abbr>  <code>  <pre>  <kbd>  <samp>  <var>
```

### Semantic / Landmark
```html
<blockquote cite>  <cite>  <address>
<time datetime>  <details>  <summary>
<progress value max>  <meter value min max low high optimum>
```

### Lists
```html
<ul>  <ol>  <li>           <!-- Unordered & Ordered -->
<dl>  <dt>  <dd>           <!-- Description List -->
```

### Media & Figures
```html
<figure>  <figcaption>
<img src alt width height loading>
```

### Table
```html
<table>  <caption>
<thead>  <tbody>  <tfoot>
<tr>  <th scope>  <td>  <td colspan>
```

### Forms
```html
<form action method novalidate>
<fieldset>  <legend>
<label for>
<input type="text">    <input type="email">
<input type="tel">     <input type="radio">
<input type="checkbox">
<select>  <optgroup label>  <option>
<textarea rows>
<button type="submit">
```

### Links & Navigation
```html
<a href>  <a rel="noopener noreferrer">
<a aria-label>  <nav aria-label>
```

---

## Project Structure

```
brand_showcase.html
│
├── <head>
│   ├── Meta tags (charset, viewport, SEO, Open Graph)
│   ├── Google Fonts link
│   └── <style> — All CSS (variables, layout, components, responsive)
│
├── <body>
│   ├── <header>          → Sticky navigation bar
│   ├── <main>
│   │   ├── #hero         → Landing hero section
│   │   ├── #stats        → Key metrics bar (<aside>)
│   │   ├── #personal     → Personal brand (Alex Morgan)
│   │   ├── #school       → Meridian University
│   │   ├── #hotel        → The Auric Pavilion
│   │   ├── #cars         → Apex Motors
│   │   ├── #comparison   → Brand tier data table
│   │   ├── #elements     → HTML elements reference demo
│   │   ├── #gallery      → Image gallery grid
│   │   └── #contact      → Contact form + FAQ
│   └── <footer>          → Site footer with links
│
└── <script>              → Inline JS (scroll reveal + counters)
```

---

## Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- An internet connection (for Google Fonts and Unsplash images)

### Installation

1. **Download** the file `brand_showcase.html`
2. **Open** it in your browser — no installation, server, or dependencies needed

```bash
# Clone if part of a repository
git clone https://github.com/your-username/brandvault-showcase.git
cd brandvault-showcase

# Then simply open
open brand_showcase.html
```

### Editing the Content

All content and styles are in a single file. To customise:

| What to change | Where to find it |
|---|---|
| Colour palette | `:root` CSS variables at the top of `<style>` |
| Fonts | Google Fonts `<link>` in `<head>` + `--font-display` / `--font-body` variables |
| Hero text | `<section id="hero">` |
| Profile details | `<section id="personal">` → `.profile-card` |
| School info | `<section id="school">` |
| Hotel rooms | `<section id="hotel">` → `.rooms-grid` |
| Car listings | `<section id="cars">` → `.cars-grid` |
| Comparison table | `<section id="comparison">` → `<table>` |
| Contact form | `<section id="contact">` → `<form>` |

---

## Responsive Breakpoints

```css
/* Desktop — default, up to 1200px container */

@media (max-width: 1024px) {
  /* Footer collapses to 2 columns
     Personal section goes single-column */
}

@media (max-width: 768px) {
  /* Hero stacks vertically (image hidden)
     Stats bar → 2 columns
     All grids collapse to single column
     Navbar links hidden (mobile-friendly) */
}

@media (max-width: 480px) {
  /* Stats, skills, gallery → 1 column
     Amenities → 2 columns */
}
```

---

## Design System

### Colour Palette

| Token | Value | Usage |
|---|---|---|
| `--gold` | `#C9A84C` | Primary accent, headings, borders |
| `--gold-light` | `#E8C96A` | Hover states |
| `--dark` | `#0D0D0D` | Main background |
| `--dark2` | `#161616` | Alternate background |
| `--dark3` | `#1F1F1F` | Section backgrounds |
| `--surface` | `#252525` | Card surfaces |
| `--text` | `#F0EBE0` | Body text |
| `--muted` | `#9A9080` | Secondary text, labels |
| `--white` | `#FAFAF8` | Headings and highlights |

### Typography

| Role | Font | Weight |
|---|---|---|
| Display / Headings | Playfair Display (serif) | 400, 700, 900 |
| Body / UI | DM Sans (sans-serif) | 300, 400, 500, 600 |

### Spacing Scale
Spacing follows a base-8 system: `8px → 16px → 24px → 32px → 48px → 60px → 80px → 100px`

---

## Accessibility

The page is built with accessibility in mind:

- All images include descriptive `alt` attributes
- Interactive elements use `aria-label` where the visual label is absent
- Navigation uses `role="navigation"` and `aria-label`
- `<main>`, `<header>`, `<footer>`, `<aside>` provide ARIA landmark roles
- Form inputs are all associated with `<label>` via `for`/`id` pairs
- `<table>` uses `scope` attributes on `<th>` elements
- Colour contrast meets WCAG AA standards for gold-on-dark text
- `<progress>` and `<meter>` elements include `aria-label` attributes
- Focus states are inherited from browser defaults

---

## Learning Outcomes

This project covers the following HTML learning outcomes:

| # | Outcome | Demonstrated In |
|---|---|---|
| 1 | Document structure and DOCTYPE | `<html>`, `<head>`, `<body>` |
| 2 | Metadata and SEO tags | `<meta>` tags in `<head>` |
| 3 | Heading hierarchy | `<h1>` through `<h6>` in Elements section |
| 4 | Paragraph and inline text elements | Throughout all sections |
| 5 | Semantic landmark elements | `<header>`, `<nav>`, `<main>`, `<footer>` etc. |
| 6 | Lists (ordered, unordered, description) | Skills, timeline, footer, FAQ |
| 7 | Hyperlinks and navigation | `<a>` throughout; breadcrumb nav |
| 8 | Images and figures | All brand sections; gallery |
| 9 | Tables with full structure | Brand tier comparison section |
| 10 | HTML Forms | Contact section |
| 11 | Semantic text elements | `<time>`, `<address>`, `<abbr>`, `<mark>` etc. |
| 12 | Interactive elements | `<details>` / `<summary>` FAQ accordion |
| 13 | Progress & measurement | `<progress>`, `<meter>` |
| 14 | Quotation and citation | `<blockquote>`, `<cite>` |
| 15 | Code representation | `<pre>`, `<code>`, `<kbd>`, `<samp>`, `<var>` |
| 16 | Responsive design (meta viewport) | `<meta name="viewport">` + CSS media queries |
| 17 | Accessibility best practices | `aria-*` attributes, `role`, `alt`, `scope` |
| 18 | Open Graph / social meta tags | `<meta property="og:...">` in `<head>` |

---

## Assets & Credits

### Images
All images are sourced from [Unsplash](https://unsplash.com) via their free CDN and are used under the [Unsplash License](https://unsplash.com/license).

| Image | Source |
|---|---|
| Workspace hero | `photo-1497366216548-37526070297c` |
| Personal profile | `photo-1560250097-0b93528c311a` |
| University campus | `photo-1562774053-701939374585` |
| Hotel exterior | `photo-1566073771259-6a8506099945` |
| Deluxe suite | `photo-1631049307264-da0ec9d70304` |
| Presidential suite | `photo-1582719478250-c89cae4dc85b` |
| Garden bungalow | `photo-1586023492125-27b2c045efd7` |
| BMW 5 Series | `photo-1617814076367-b759c7d7e738` |
| Mercedes GLE | `photo-1549317661-bd32c8ce0db2` |
| Porsche 911 | `photo-1503376780353-7e6692767b70` |
| Rolls-Royce Ghost | `photo-1555215695-3004980ad54e` |
| Hotel aerial | `photo-1541746972996-4e0b0f43e02a` |
| Students on campus | `photo-1523050854058-8df90110c9f1` |
| Car showroom | `photo-1492144534655-ae79c964c9d7` |
| Strategy meeting | `photo-1552664730-d307ca884978` |
| Branding moodboard | `photo-1600880292203-757bb62b4baf` |

### Fonts
- [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) — Google Fonts (OFL License)
- [DM Sans](https://fonts.google.com/specimen/DM+Sans) — Google Fonts (OFL License)

---

## License

This project is released for **educational and personal use**.

```
MIT License

Copyright (c) 2024 Tunz Studio

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

<div align="center">

Made with ❤️ using pure HTML · **Tunz Studio** · Lagos, Nigeria

</div>
