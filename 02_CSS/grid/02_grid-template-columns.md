📄 File Name: 02_grid_columns_rows.md

# Grid Columns and Rows

## grid-template-columns

Defines:

- Number of columns
- Width of each column

Example

```css
grid-template-columns:200px 200px;
```

Creates two columns.

---

## fr Unit

Fraction of remaining available space.

Example

```css
grid-template-columns:1fr 2fr 1fr;
```

Ratio

1 : 2 : 1

---

## repeat()

Cleaner syntax.

Instead of

```css
100px 100px 100px;
```

write

```css
repeat(3,100px);
```

---

