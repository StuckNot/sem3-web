# ☕ Brew Haven — A Beginner Web Design Reference

A small, beautiful café website built as a **teaching reference** for
Semester 3 Web Design students. Every file is heavily commented in plain
English, and new concepts are marked with `✨ NEW` so they're easy to spot.

## What it demonstrates

**Concepts students already know, reinforced:**
- Semantic tags (`header`, `nav`, `section`, `footer`)
- Headings, paragraphs, lists, anchors, tables, images
- `class` vs `id`, and inline vs global CSS

**New concepts, introduced gently:**
- CSS variables (custom properties)
- Flexbox layout
- A dark-mode toggle
- Hover effects & transitions
- A little JavaScript (a function + an array + `Math.random()`)
- External stylesheet (`<link rel="stylesheet">`)

## Files

| File | What it shows |
|------|---------------|
| `index.html` | All-in-one version — HTML, CSS (`<style>`) and JS in a single file |
| `cafe.html` + `style.css` | The **split** version — HTML links out to an external stylesheet |

The two versions render identically. The point is to show that *moving* the
CSS into its own file organizes the code without changing the page —
`cafe.html` is the bones, `style.css` is the clothes.

## Running it

Double-click `index.html` (or `cafe.html`) to open it in a browser.

To serve it the way the real web works, from this folder run:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000/index.html>.

---

Made with ☕ for the classroom.
