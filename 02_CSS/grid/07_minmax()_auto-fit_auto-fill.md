📄 File Name: 06_minmax_auto_fit_auto_fill.md

# Responsive Grid

## minmax()

Defines minimum and maximum size.

Syntax

```css
minmax(min,max)
```

Example

```css
minmax(250px,1fr)
```

Meaning

Minimum = 250px

Maximum = remaining available space.

---

## auto-fit

Automatically creates as many columns as fit.

Empty columns collapse.

Existing items stretch.

Example

```css
grid-template-columns:
repeat(auto-fit,minmax(250px,1fr));
```

---

## auto-fill

Creates as many columns as possible.

Empty columns remain.

Items do not stretch into those empty columns.

---

## Difference

auto-fit

✔ Empty tracks collapse

✔ Items stretch

auto-fill

✔ Empty tracks remain

✔ Grid structure preserved

---

## Professional Formula

```css
grid-template-columns:
repeat(auto-fit,minmax(250px,1fr));
```

Used for:

- Portfolio
- Gallery
- Products
- Dashboard