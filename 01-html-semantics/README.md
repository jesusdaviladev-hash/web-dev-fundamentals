# HTML5 Semantic Elements

## Why This Matters
Semantic HTML provides meaning to your content, not just structure.  
It improves accessibility, SEO, and code readability, and helps assistive technologies understand your page.

Using semantic elements correctly is a strong signal of solid fundamentals.

---

## Core Semantic Elements

### `<header>`
- Represents introductory content
- Often contains a logo, heading, or navigation
- Can be used inside sections and articles

### `<nav>`
- Contains major navigation links
- Should not be used for every group of links

### `<main>`
- Represents the main content of the page
- Only **one `<main>` per page**

### `<section>`
- Groups related content by theme
- Should usually contain a heading

### `<article>`
- Self-contained content
- Examples: blog post, card, news item

### `<aside>`
- Secondary or related content
- Examples: sidebar, related links

### `<footer>`
- Footer for a page or section
- Can contain metadata, links, or copyright

---

## Accessibility Essentials
- Use `<label>` with `for` attributes for form inputs
- Provide meaningful `alt` text for images
- Maintain logical heading order (`h1 → h2 → h3`)
- Ensure keyboard navigation works

---

## Common Mistakes
- Overusing `<div>` instead of semantic elements
- Using multiple `<main>` elements
- Skipping heading levels
- Missing labels on form inputs

---

## Key Takeaways
- Semantic HTML improves usability and accessibility
- Screen readers rely on proper semantics
- Clean structure makes code easier to maintain
