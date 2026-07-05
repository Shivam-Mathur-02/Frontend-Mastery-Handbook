# CSS Box Model

## What is the Box Model?

Every HTML element is treated as a rectangular box by the browser.

```
+-----------------------------+
|           Margin            |
|  +-----------------------+  |
|  |       Border          |  |
|  |  +-----------------+  |  |
|  |  |    Padding      |  |  |
|  |  | +-------------+ |  |  |
|  |  | |  Content    | |  |  |
|  |  | +-------------+ |  |  |
|  |  +-----------------+  |  |
|  +-----------------------+  |
+-----------------------------+
```

## Components

### Content
The actual text, image or child elements.

### Padding
Space between the content and the border.

```css
padding: 20px;
```

### Border

```css
border: 2px solid black;
```

### Margin

Space outside the element.

```css
margin: 20px;
```

---

## box-sizing

Default

```css
box-sizing: content-box;
```

Recommended

```css
*{
    box-sizing: border-box;
}
```

---

## Best Practices

- Use `padding` for internal spacing.
- Use `margin` for spacing between elements.
- Apply `box-sizing: border-box` globally.

---

## Common Mistakes

❌ Using padding instead of margin.

❌ Forgetting `box-sizing`.

---

## Interview Questions

1. Difference between margin and padding?
2. What is `box-sizing`?
3. Why do developers prefer `border-box`?

---

## Cheat Sheet

- Margin → Outside spacing
- Border → Surrounds padding/content
- Padding → Inside spacing
- Content → Actual data