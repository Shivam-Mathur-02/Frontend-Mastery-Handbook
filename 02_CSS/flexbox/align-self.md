# CSS Flexbox - align-self

## Definition

`align-self` overrides the container's `align-items` value for a single flex item.

---

## Syntax

```css
.item{
    align-self:flex-end;
}
```

---

## Default Value

```css
align-self:auto;
```

Meaning

Follow the value of `align-items`.

---

## Values

```css
auto
flex-start
center
flex-end
stretch
```

---

## align-items vs align-self

| align-items | align-self |
|--------------|------------|
| Applies to all flex items | Applies to one flex item |
| Set on container | Set on flex item |

---

## Example

```css
.container{
    display:flex;
    height:300px;
    align-items:center;
}

.special{
    align-self:flex-end;
}
```

Only `.special` moves.

---

## Works On

Cross Axis only.

Never affects the Main Axis.

---

## Real World Uses

- Featured Pricing Card
- Chat Messages
- Dashboard Widgets
- Highlighted Cards

---

## Common Mistakes

❌ Applying align-self to container.

❌ Expecting it to work on Main Axis.

❌ Confusing align-items with align-self.

---

## Interview Questions

- Default value?
- Difference between align-items and align-self?
- Can it affect the Main Axis?