# CSS Flexbox - flex-basis

## Definition

`flex-basis` specifies the initial size of a flex item before free space is distributed or removed.

Think of it as the starting size.

---

## Syntax

```css
.item{
    flex-basis:200px;
}
```

---

## Default Value

```css
flex-basis:auto;
```

Meaning

Use the element's natural size (width or content size).

---

## Browser Algorithm

```
flex-basis

↓

Initial Width

↓

flex-grow

↓

flex-shrink

↓

Final Width
```

---

## Example

```css
.item{
    flex-basis:200px;
    flex-grow:1;
}
```

Three Items

```
200px
200px
200px
```

Total

```
600px
```

Container

```
900px
```

Remaining

```
300px
```

Each receives

```
100px
```

Final Width

```
300px
300px
300px
```

---

## width vs flex-basis

| width | flex-basis |
|--------|------------|
| General CSS property | Flexbox property |
| Works everywhere | Only Flex Items |
| Preferred width | Initial Main Axis size |

---

## Important Rule

```css
width:200px;
flex-basis:300px;
```

Inside Flexbox

```
flex-basis wins.
```

---

## Real World Uses

- Cards
- Sidebar
- Search Bar
- Dashboard
- Pricing Cards

---

## Common Mistakes

❌ Thinking flex-basis is final width.

❌ Using width instead of flex-basis in Flexbox.

---

## Interview Questions

- Default value?
- Difference between width and flex-basis?
- Which property wins?