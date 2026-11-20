# Course 3: HTML, CSS & JavaScript

## Module 1: HTML Basics

### What I learned
- Structure of an HTML page: `<!DOCTYPE html>`, `<html>`, `<head>` (metadata like title and charset) and `<body>` (visible content)
- Common tags: headings (`h1`-`h6`), paragraph (`p`), image (`img`), unordered list (`ul`/`li`), link (`a`), table, and form
- Building a basic form with `fieldset`, `legend`, `label`, `input`, `textarea` and a submit `button`

### Important concepts
- `<head>` holds metadata; `<body>` holds what the user actually sees
- A page should have only one `<h1>`; use `<h2>` for sub-sections
- Every opening tag needs its closing tag (e.g. `<p>` needs `</p>`)
- Inside a `<table>`, only table elements (`tr`, `th`, `td`, `thead`, `tbody`) belong; a `<p>` or `<a>` must go outside it
- `<img>` needs a working `src` (a local file or a direct image URL, not a share link) and an `alt` text for accessibility
- Form basics: `label for="x"` connects to `input id="x"`, `required` makes a field mandatory, `action` and `method` decide where and how the data is sent (no backend yet, so it goes nowhere for now)

### Labs
- **Lab 1: First web page** (`labs/lab1-first-webpage/`)
  - Built a personal intro page with a heading, paragraph, image, list, projects table, GitHub link and a feedback form
  - Tags used: `h1`, `h2`, `p`, `img`, `ul`, `li`, `table`, `form`, `a`

### Mistakes I fixed
- Placed a `<p>` and `<a>` inside the `<table>`; moved them after `</table>`
- Left the first `<p>` unclosed
- Used a Google share link as the image source; switched to a local file in the same folder (`photo.jpeg`)
- Had two `<h1>` tags on one page; changed the second to `<h2>`
- A broken `<img>` line made part of the tag show up as plain text on the page

### Questions / doubts
- How does a form actually send data to a backend (`action` and `method`)? Will cover this when I reach Node.js and Express