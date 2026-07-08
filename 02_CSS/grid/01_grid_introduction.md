📄 File Name: 01_grid_introduction.md

# CSS Grid - Introduction

## What is CSS Grid?

CSS Grid is a two-dimensional layout system.

It allows us to design layouts in both:
- Rows
- Columns

Unlike Flexbox (one-dimensional), Grid controls horizontal and vertical layouts simultaneously.

---

## Why CSS Grid?

- Creates complex layouts easily
- Responsive design
- Less HTML
- Cleaner CSS
- Better readability

---

## Grid Container

A parent element becomes a Grid Container by using:

```css
.container{
    display:grid;
}
```

All direct children become Grid Items.

---

## Grid Item

Any direct child of a Grid Container.

Example

```html
<div class="container">
    <div>Item 1</div>
    <div>Item 2</div>
</div>
```

Here both divs are Grid Items.

---

## Key Points

✔ Grid creates rows and columns.

✔ Parent = Grid Container

✔ Children = Grid Items

✔ Grid is used for two-dimensional layouts.