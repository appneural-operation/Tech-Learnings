## **HTML Topics List**

### **1. Introduction & Basics**

* HTML kya hai?
* History of HTML
* Structure of HTML Document
* Doctype Declaration
* HTML Versions

### **2. Basic HTML Tags**

* `<html>`, `<head>`, `<body>`
* `<title>`
* `<meta>`
* `<link>` (CSS linking)
* `<style>`

### **3. Text Formatting & Typography**

* Headings: `<h1>` to `<h6>`
* Paragraph: `<p>`
* Line Break: `<br>`
* Horizontal Line: `<hr>`
* Bold, Italic, Underline: `<b>`, `<i>`, `<u>`
* Strong & Emphasis: `<strong>`, `<em>`
* Subscript & Superscript: `<sub>`, `<sup>`
* Blockquote: `<blockquote>`
* Preformatted Text: `<pre>`

### **4. Lists**

* Ordered List: `<ol>`
* Unordered List: `<ul>`
* List Item: `<li>`
* Description List: `<dl>`, `<dt>`, `<dd>`

### **5. Links & Navigation**

* Anchor Tag: `<a href="">`
* Internal Links
* External Links
* Email Links (`mailto:`)
* Anchor with target attribute (`_blank`, `_self`)

### **6. Images & Media**

* Image Tag: `<img>`
* Attributes: `src`, `alt`, `width`, `height`
* Image Maps: `<map>`, `<area>`
* Audio: `<audio>`
* Video: `<video>`
* Embedding YouTube/Vimeo

### **7. Tables**

* Table: `<table>`
* Table Row: `<tr>`
* Table Header: `<th>`
* Table Data: `<td>`
* Table Caption: `<caption>`
* Table Grouping: `<thead>`, `<tbody>`, `<tfoot>`
* Colspan & Rowspan

### **8. Forms**

* Form Tag: `<form>`
* Input Types: `text`, `password`, `email`, `number`, `date`, `checkbox`, `radio`, `file`, `submit`, etc.
* Textarea: `<textarea>`
* Select Dropdown: `<select>`, `<option>`
* Labels: `<label>`
* Fieldset & Legend: `<fieldset>`, `<legend>`
* Form Attributes: `action`, `method`, `autocomplete`, `required`

### **9. Semantic HTML**

* Header: `<header>`
* Footer: `<footer>`
* Section: `<section>`
* Article: `<article>`
* Aside: `<aside>`
* Nav: `<nav>`
* Main: `<main>`
* Figure & Figcaption: `<figure>`, `<figcaption>`

### **10. HTML5 Advanced Features**

* Canvas: `<canvas>`
* SVG: `<svg>`
* Audio & Video APIs
* Drag & Drop
* Local Storage & Session Storage (via JS)
* Web Workers (basic understanding)

### **11. Meta & SEO**

* Meta Tags: `<meta name="description">`, `<meta charset="">`
* Open Graph Tags
* Favicon: `<link rel="icon">`
* Robots: `<meta name="robots">`

### **12. Accessibility (a11y)**

* ARIA Attributes
* `alt` for images
* Keyboard navigation & focus
* Semantic tags for screen readers

### **13. HTML Best Practices**

* Proper indentation
* Commenting: `<!-- comment -->`
* Valid HTML & W3C validation
* Avoid deprecated tags

---

# Foundations (Beginner)

* What is HTML? elements, tags, attributes, comments
* Document skeleton: `<!doctype html>`, `<html>`, `<head>`, `<body>`
* Text & structure: headings, paragraphs, spans, divs, line breaks
* Links & navigation: `<a>`, `href`, `target`, relative vs absolute URLs
* Images: `<img>`, `alt`, responsive images (`srcset`, `sizes`)
* Lists: `<ul>`, `<ol>`, `<dl>` + list-style basics
* Metadata in `<head>`: `charset`, `viewport`, `title`, `meta`

# Semantics & Layout (Core)

* Semantic tags: `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`, `figure/figcaption`, `time`, `mark`
* Content grouping vs meaning: `div` vs semantic elements
* Tables: `table`, `thead/tbody/tfoot`, `tr/th/td`, `scope`, captions
* Forms (intro): `form`, `input`, `label`, `textarea`, `select`, `button`, `name/value`
* Media: `<audio>`, `<video>`, `<track>` (captions), `<picture>`
* Accessibility basics: headings order, alt text, label/controls, focus order

# Forms—Intermediate to Advanced

* Input types: `email`, `url`, `number`, `date`, `range`, `file`, `color`
* Built-in validation: `required`, `pattern`, `min/max`, `maxlength`, `novalidate`
* Grouping & hints: `fieldset`, `legend`, `placeholder`, `aria-describedby`
* Autocomplete & UX: `autocomplete`, `datalist`
* File uploads & multiple files, `accept` MIME types
* Custom controls (progressive enhancement) and constraint validation API (JS)

# Accessibility (A11y)

* Semantic structure that supports screen readers
* Names, roles, states: `aria-*` (only when semantics aren’t enough)
* Forms + error messaging patterns (live regions)
* Keyboard navigation & focus management (`tabindex`, `accesskey`)
* Media captions/subtitles via `<track>`; transcripts
* Color/contrast is CSS, but understand HTML hooks and attributes

# Head & Metadata Mastery

* Favicons & app icons (multi-size, `manifest.json` pointer)
* Social/preview cards: Open Graph, Twitter Cards
* SEO essentials: meaningful titles, meta description, canonical links, language (`lang`), `hreflang`
* Robots & indexing: `robots` meta vs `robots.txt`
* Preloads & resource hints: `<link rel="preload" as="...">`, `prefetch`, `dns-prefetch`

# Images & Media—Pro Level

* Responsive images deep dive: `srcset`, `sizes`, `<picture>` + art direction
* Modern formats: AVIF/WebP; fallbacks
* Lazy loading: `loading="lazy"`, decoding, fetchpriority
* `<figure>` semantics for captions and credit

# Advanced Semantics & Data

* Microdata, RDFa, JSON-LD (structured data for SEO)
* `data-*` attributes for behavior hooks
* `<template>` & `<slot>` (for web components usage patterns)
* `<dialog>` element (modals) + accessibility considerations
* `<details>` / `<summary>` for disclosures
* Time, address, meter, progress—when to use them correctly

# Performance-Oriented HTML

* Minimal critical HTML, defer non-critical scripts
* Ordering of CSS/JS in the document
* Resource hints again (preload fonts/media correctly)
* Avoiding layout shifts with width/height attributes
* Using semantic HTML to reduce JS bloat

# Internationalization (i18n)

* `lang` on `<html>`, `dir="rtl"` where needed
* Character encoding (`utf-8`)
* Marking language changes inline
* Date/time formatting hooks (`<time>`)

# Security & Integrity

* `rel="noopener noreferrer"` on external links
* Subresource Integrity (SRI) for CDN assets
* Sandboxing iframes: `sandbox`, `allow`, `referrerpolicy`
* Forms & security headers (HTML hooks + server cooperation)

# Web Components & Modern HTML APIs (with light JS)

* Custom elements (HTML usage), Shadow DOM (slots), `<template>`
* Declarative Shadow DOM (server-rendered components)
* Declarative event listeners (spec is evolving—stay aware)

# Canvas, SVG & Graphics (HTML Integration)

* `<canvas>` for drawing (JS heavy, but HTML hosts it)
* Inline SVG vs `<img>` SVG; accessibility & styling hooks
* `<map>` image maps (rare but useful)

# PWA-Adjacent HTML

* Link to web app manifest
* Installability meta, theme color, `apple-touch-icon`
* Offline considerations (HTML structure for fallbacks)

# Email HTML (Specialist Topic)

* Table-based layouts, inline styles, limited tags
* Alt text, fallback content, safe attributes

---

## Practice Ladder (quick projects)

1. **Semantic Blog Page**: header/nav/main/article/aside/footer + proper headings.
2. **Product Table**: sortable columns (HTML first), captions, scoped headers.
3. **Accessible Form**: labels, hints, validation, error summary.
4. **Media Page**: responsive images with `<picture>`, video with captions.
5. **Docs Landing**: perfect head metadata, favicons, OG/Twitter cards, preload fonts.
6. **Disclosure UI**: `<details>`/`<summary>`, `<dialog>` with fallback content.
7. **Microdata/JSON-LD**: add Product or Article structured data.

## Quality Checklist (use every time)

* One `<h1>` per page; logical heading outline
* Landmark roles via real tags: `header`, `nav`, `main`, `footer`, etc.
* Every image with meaningful `alt` (or empty alt for decorative)
* Labels connected to inputs; keyboard reachable; visible focus
* Correct `lang`, charset, viewport; meta description present
* Width/height on images to prevent CLS; `loading="lazy"` when safe
* External links safe: `rel="noopener noreferrer"`
  
---

## 📝 **Basic Structure**

| Tag               | Purpose                                   |
| ----------------- | ----------------------------------------- |
| `<!DOCTYPE html>` | Declares document type                    |
| `<html>`          | Root element                              |
| `<head>`          | Metadata container                        |
| `<title>`         | Page title (in browser tab)               |
| `<meta>`          | Metadata (charset, viewport, description) |
| `<link>`          | External resources (CSS, icons)           |
| `<style>`         | Internal CSS                              |
| `<script>`        | JavaScript                                |
| `<body>`          | Main content of the page                  |

---

## 📝 **Text Content**

| Tag            | Purpose                |
| -------------- | ---------------------- |
| `<h1>`–`<h6>`  | Headings (1–6)         |
| `<p>`          | Paragraph              |
| `<span>`       | Inline grouping        |
| `<br>`         | Line break             |
| `<hr>`         | Horizontal rule        |
| `<pre>`        | Preformatted text      |
| `<code>`       | Inline code snippet    |
| `<blockquote>` | Quoted block           |
| `<q>`          | Short inline quotation |
| `<abbr>`       | Abbreviation           |
| `<cite>`       | Citation               |
| `<address>`    | Contact info           |

---

## 🔗 **Links & Navigation**

| Tag      | Purpose                     |
| -------- | --------------------------- |
| `<a>`    | Anchor link                 |
| `<nav>`  | Navigation section          |
| `<base>` | Base URL for relative links |

---

## 🖼 **Images & Media**

| Tag            | Purpose                      |
| -------------- | ---------------------------- |
| `<img>`        | Image                        |
| `<figure>`     | Container for image/media    |
| `<figcaption>` | Caption for figure           |
| `<picture>`    | Responsive images            |
| `<video>`      | Video content                |
| `<audio>`      | Audio content                |
| `<track>`      | Captions/subtitles for media |
| `<source>`     | Additional media sources     |
| `<embed>`      | Embed external content       |
| `<iframe>`     | Inline frame                 |

---

## 📝 **Lists**

| Tag    | Purpose                |
| ------ | ---------------------- |
| `<ul>` | Unordered list         |
| `<ol>` | Ordered list           |
| `<li>` | List item              |
| `<dl>` | Definition list        |
| `<dt>` | Definition term        |
| `<dd>` | Definition description |

---

## 📊 **Tables**

| Tag          | Purpose              |
| ------------ | -------------------- |
| `<table>`    | Table container      |
| `<caption>`  | Table caption        |
| `<thead>`    | Table header section |
| `<tbody>`    | Table body section   |
| `<tfoot>`    | Table footer section |
| `<tr>`       | Table row            |
| `<th>`       | Header cell          |
| `<td>`       | Data cell            |
| `<colgroup>` | Column group         |
| `<col>`      | Column definition    |

---

## 📝 **Forms & Inputs**

| Tag          | Purpose                    |
| ------------ | -------------------------- |
| `<form>`     | Form container             |
| `<input>`    | Input field                |
| `<label>`    | Input label                |
| `<textarea>` | Multi-line text input      |
| `<select>`   | Dropdown list              |
| `<option>`   | Option in dropdown         |
| `<optgroup>` | Group of options           |
| `<button>`   | Button                     |
| `<fieldset>` | Group related fields       |
| `<legend>`   | Caption for fieldset       |
| `<datalist>` | Autocomplete list          |
| `<output>`   | Output value               |
| `<progress>` | Progress bar               |
| `<meter>`    | Scalar measurement (gauge) |

---

## 🗂 **Semantic & Layout**

| Tag         | Purpose                   |
| ----------- | ------------------------- |
| `<header>`  | Page/section header       |
| `<footer>`  | Page/section footer       |
| `<main>`    | Main content              |
| `<section>` | Thematic grouping         |
| `<article>` | Independent content block |
| `<aside>`   | Sidebar content           |
| `<div>`     | Generic block container   |

---

## 🧩 **Interactive Elements**

| Tag                     | Purpose                 |
| ----------------------- | ----------------------- |
| `<details>`             | Disclosure widget       |
| `<summary>`             | Summary for details     |
| `<dialog>`              | Dialog box/modal        |
| `<menu>`                | Context or toolbar menu |
| `<menuitem>` (obsolete) | Menu items              |

---

## 🗄 **Scripting**

| Tag          | Purpose               |
| ------------ | --------------------- |
| `<script>`   | JavaScript            |
| `<noscript>` | Fallback for no JS    |
| `<template>` | HTML template content |
| `<slot>`     | Web components slot   |
| `<canvas>`   | Graphics drawing area |

---

## 🖼 **Graphics & SVG**

| Tag                                            | Purpose                  |
| ---------------------------------------------- | ------------------------ |
| `<svg>`                                        | Scalable Vector Graphics |
| `<path>`, `<circle>`, `<rect>`, `<line>`, etc. | Shapes inside SVG        |
| `<use>`                                        | Reuse SVG content        |
| `<defs>`                                       | Definitions for SVG      |

---

## 🛡 **Metadata & Head Stuff**

| Tag       | Purpose               |
| --------- | --------------------- |
| `<meta>`  | Metadata              |
| `<base>`  | Base URL              |
| `<link>`  | External CSS, favicon |
| `<style>` | Internal CSS          |

---

## 🛡 **Obsolete/Deprecated (still seen sometimes)**

| Tag                | Purpose                         |
| ------------------ | ------------------------------- |
| `<center>`         | Center text (deprecated)        |
| `<font>`           | Font styling (deprecated)       |
| `<big>`, `<small>` | Font size changes (deprecated)  |
| `<acronym>`        | Abbreviation (use `<abbr>` now) |

---

