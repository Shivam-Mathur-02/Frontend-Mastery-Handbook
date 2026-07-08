📄 File Name: grid_cheatsheet.md

# CSS Grid Cheat Sheet

## Create Grid

```css
display:grid;
```

---

## Columns

```css
grid-template-columns:200px 1fr;
```

---

## Rows

```css
grid-template-rows:100px 200px;
```

---

## Fraction

```css
1fr
2fr
```

---

## Repeat

```css
repeat(3,1fr)
```

---

## Gap

```css
gap:20px;
row-gap:20px;
column-gap:20px;
```

---

## Grid Item Placement

```css
grid-column:1/3;

grid-row:1/3;
```

---

## Span

```css
grid-column:1/span 2;
```

---

## Grid Areas

```css
grid-template-areas:
"header header"
"sidebar main"
"footer footer";
```

Assign

```css
grid-area:header;
```

---

## Responsive Grid

```css
repeat(auto-fit,minmax(250px,1fr));
```

---

## Item Alignment

```css
justify-items:center;

align-items:center;

place-items:center;
```

---

## Grid Alignment

```css
justify-content:center;

align-content:center;
```

---

# Flexbox vs Grid

| Flexbox | Grid |
|----------|------|
| One-dimensional | Two-dimensional |
| Row OR Column | Rows AND Columns |
| Component Layout | Page Layout |

---

## Professional Responsive Grid

```css
.container{
    display:grid;
    grid-template-columns:
    repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}
```