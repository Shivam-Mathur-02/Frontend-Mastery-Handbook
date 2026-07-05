# CSS Position

## Values

- static
- relative
- absolute
- fixed
- sticky

---

## Static

Default position.

---

## Relative

Moves relative to its original position.

Stays in normal flow.

```css
position: relative;
left:20px;
```

---

## Absolute

Removed from normal flow.

Moves relative to the nearest positioned ancestor.

```css
.parent{
    position:relative;
}

.child{
    position:absolute;
    top:10px;
    right:10px;
}
```

---

## Fixed

Relative to viewport.

Examples

- Chat button
- Scroll to top

---

## Sticky

Behaves normally until a threshold.

Then sticks.

Example

Navigation bar.

---

## Common Mistakes

❌ Forgetting to set the parent to `position: relative`.

❌ Using position for spacing.

---

## Interview Questions

1. Difference between relative and absolute?
2. Difference between fixed and sticky?
3. Why do we make the parent relative?