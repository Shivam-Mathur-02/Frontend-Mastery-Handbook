📄 File Name: 04_grid_lines_grid_column_grid_row.md

# Grid Lines, grid-column & grid-row

## Grid Lines

If there are

- 2 columns → 3 vertical lines
- 3 columns → 4 vertical lines
- 4 columns → 5 vertical lines

Rule

Grid Lines = Columns + 1

---

## grid-column

Defines where a Grid Item starts and ends.

Example

```css
grid-column:1/3;
```

Starts at Line 1

Ends at Line 3

Occupies Columns 1 and 2.

---

## grid-row

Works exactly like grid-column but vertically.

Example

```css
grid-row:1/3;
```

Occupies Rows 1 and 2.

---

## span

Instead of

```css
grid-column:1/3;
```

write

```css
grid-column:1/span 2;
```

Meaning

Start at Line 1

Occupy 2 columns.

---

## Remember

Grid Line ≠ Column

Always think using Grid Lines.