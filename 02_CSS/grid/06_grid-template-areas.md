📄 File Name: 05_grid_template_areas.md

# grid-template-areas

## Purpose

Creates visual layouts using names instead of Grid Lines.

Example

```css
grid-template-areas:
"header header"
"sidebar main"
"footer footer";
```

---

## grid-area

Assigns a Grid Item to an area.

```css
.header{
    grid-area:header;
}
```

---

## Empty Cell

Use

```css
"."
```

Example

```css
grid-template-areas:
"header header"
". main";
```

---

## Advantages

✔ Easy to read

✔ Easy to maintain

✔ Professional layouts

✔ Visual representation of page structure

---

## Rules

- Names must match exactly.
- Every row must contain the same number of columns.
- '.' creates an empty cell.