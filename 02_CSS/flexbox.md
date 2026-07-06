# CSS Flexbox

## What is Flexbox?

Flexbox (Flexible Box Layout) is a CSS layout model designed for building one-dimensional layouts.

It arranges items either:

- Horizontally (Row)
- Vertically (Column)

---

## Why was Flexbox introduced?

Before Flexbox developers used:

- float
- inline-block
- table layouts
- positioning

These techniques were difficult to maintain and were not responsive.

Flexbox provides a clean and flexible way to align, distribute and size elements.

---

## Flex Container

The parent element becomes a Flex Container.

```css
.container{
    display:flex;
}
```

---

## Flex Items

The direct children of a Flex Container become Flex Items.

```html
<div class="container">
    <div>Item 1</div>
    <div>Item 2</div>
    <div>Item 3</div>
</div>
```

---

## Main Axis and Cross Axis

Default (`flex-direction: row`)

```
Main Axis  →
Cross Axis ↓
```

When `flex-direction: column`

```
Main Axis  ↓
Cross Axis →
```

Remember:

- justify-content → Main Axis
- align-items → Cross Axis

Never memorize horizontal or vertical.

Always think in terms of axes.

---

## flex-direction

Default

```css
flex-direction:row;
```

Other values

```css
row
row-reverse
column
column-reverse
```

---

## Best Practices

- Use Flexbox for one-dimensional layouts.
- Use semantic HTML with Flexbox.
- Think in Main Axis and Cross Axis.
- Prefer Flexbox over floats for layouts.

---

## Common Mistakes

❌ Forgetting `display:flex`

❌ Applying Flexbox properties to child elements instead of the container

❌ Thinking justify-content always means horizontal

---
---

# CSS Flexbox

## What is Flexbox?

Flexbox (Flexible Box Layout) is a CSS layout model designed for building one-dimensional layouts.

It arranges items either:

- Horizontally (Row)
- Vertically (Column)

---

## Why was Flexbox introduced?

Before Flexbox developers used:

- float
- inline-block
- table layouts
- positioning

These techniques were difficult to maintain and were not responsive.

Flexbox provides a clean and flexible way to align, distribute and size elements.

---

## Flex Container

The parent element becomes a Flex Container.

```css
.container{
    display:flex;
}
```

---

## Flex Items

The direct children of a Flex Container become Flex Items.

```html
<div class="container">
    <div>Item 1</div>
    <div>Item 2</div>
    <div>Item 3</div>
</div>
```

---

## Main Axis and Cross Axis

Default (`flex-direction: row`)

```
Main Axis  →
Cross Axis ↓
```

When `flex-direction: column`

```
Main Axis  ↓
Cross Axis →
```

Remember:

- justify-content → Main Axis
- align-items → Cross Axis

Never memorize horizontal or vertical.

Always think in terms of axes.

---

## flex-direction

Default

```css
flex-direction:row;
```

Other values

```css
row
row-reverse
column
column-reverse
```

---

## Best Practices

- Use Flexbox for one-dimensional layouts.
- Use semantic HTML with Flexbox.
- Think in Main Axis and Cross Axis.
- Prefer Flexbox over floats for layouts.

---

## Common Mistakes

❌ Forgetting `display:flex`

❌ Applying Flexbox properties to child elements instead of the container

❌ Thinking justify-content always means horizontal

---
---

# justify-content

## Purpose

Controls the alignment and distribution of Flex Items along the Main Axis.

Requires:

```css
display:flex;
```

---

## Values

### flex-start

```
HTML CSS JS
```

---

### center

```
      HTML CSS JS
```

---

### flex-end

```
               HTML CSS JS
```

---

### space-between

```
HTML      CSS      JS
```

No space at container edges.

---

### space-around

```
 HTML    CSS    JS
```

Half space at edges.

---

### space-evenly

```
 HTML    CSS    JS
```

Equal spacing everywhere.

---

## Best Practices

Use

- space-between → Navigation bars
- center → Buttons, Login pages
- space-evenly → Menus
- flex-start → Default layouts

---

## Common Mistakes

❌ Using justify-content without display:flex

❌ Thinking justify-content always works horizontally

---

## Interview Questions

1. What does justify-content control?
2. Difference between space-between and space-evenly?
3. Why doesn't justify-content work without display:flex?

---
---

# align-items

## Purpose

Aligns Flex Items along the Cross Axis.

---

## Values

### stretch (default)

Items stretch to fill the Cross Axis.

---

### flex-start

Items align to the beginning.

---

### center

Items align to the center.

---

### flex-end

Items align to the end.

---

## Important

Default axes

```
Main Axis  →
Cross Axis ↓
```

Column direction

```
Main Axis ↓

Cross Axis →
```

justify-content

↓

Main Axis

align-items

↓

Cross Axis

---

## Common Mistakes

❌ Forgetting container height

❌ Confusing Main Axis with Horizontal

❌ Using align-items for Main Axis alignment

---

## Interview Questions

1. Difference between justify-content and align-items?
2. Why doesn't align-items:center always work?
3. What is the default value?

---
---

# gap

## Purpose

Creates spacing between Flex Items.

---

## Example

```css
.container{
    display:flex;
    gap:20px;
}
```

---

## Advantages over Margin

- Cleaner code
- No edge spacing
- No :last-child fixes
- Easier maintenance

---

## row-gap

Creates spacing between rows.

---

## column-gap

Creates spacing between columns.

---

## gap

Shortcut for both.

---

## Best Practices

Use gap whenever spacing is needed between Flex or Grid items.

---

## Common Mistakes

❌ Applying gap to child elements

❌ Combining margin and gap for the same spacing

---

## Interview Questions

1. Why is gap preferred over margin?
2. Does gap create spacing at container edges?
3. Difference between gap, row-gap and column-gap?

---
---

# flex-wrap

## Purpose

Controls whether Flex Items stay on one line or move onto multiple lines.

---

## Default

```css
flex-wrap:nowrap;
```

Items remain on one line.

---

## wrap

```css
flex-wrap:wrap;
```

Items automatically move to the next row when needed.

---

## wrap-reverse

Rows are stacked in reverse order.

---

## Common Usage

- Product cards
- Image galleries
- Skills section
- Team members
- Dashboard widgets

---

## Best Practices

Combine with:

```css
display:flex;
gap:20px;
```

---

## Common Mistakes

❌ Forgetting wrap

❌ Using margins instead of gap

---

## Interview Questions

1. Default value of flex-wrap?
2. Difference between wrap and wrap-reverse?
3. Give a real-world use case.