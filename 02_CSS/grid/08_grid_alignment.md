📄 File Name: 07_grid_alignment.md

# Grid Alignment

## Item Alignment

### justify-items

Moves Grid Items horizontally inside their cells.

```css
justify-items:center;
```

Values

- start
- center
- end
- stretch (default)

---

### align-items

Moves Grid Items vertically inside their cells.

```css
align-items:center;
```

---

### place-items

Shortcut

```css
place-items:center;
```

Equivalent to

```css
justify-items:center;
align-items:center;
```

---

## Grid Alignment

### justify-content

Moves the entire Grid horizontally inside the container.

---

### align-content

Moves the entire Grid vertically inside the container.

---

## Difference

Item Alignment

- justify-items
- align-items
- place-items

Moves Grid Items.

Grid Alignment

- justify-content
- align-content

Moves the entire Grid.

---

## Summary Table

| Property | Purpose |
|----------|---------|
| justify-items | Horizontal alignment of items |
| align-items | Vertical alignment of items |
| place-items | Centers items in both directions |
| justify-content | Horizontal alignment of entire Grid |
| align-content | Vertical alignment of entire Grid |