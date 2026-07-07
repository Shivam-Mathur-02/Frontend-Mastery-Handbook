# CSS Flexbox - flex-grow

## Definition

`flex-grow` specifies how much a flex item should grow relative to the other flex items when there is extra space available inside the flex container.

It distributes **remaining free space**.

---

## Syntax

```css
.item{
    flex-grow:1;
}
```

---

## Default Value

```css
flex-grow:0;
```

Meaning:

The item will **not grow**.

---

## Browser Algorithm

1. Calculate initial width of all flex items.
2. Calculate remaining free space.
3. Read flex-grow values.
4. Distribute remaining space proportionally.

```
Initial Width
      ↓
Remaining Space?
      ↓
Yes
      ↓
flex-grow
      ↓
Final Width
```

---

## Example

```css
.container{
    display:flex;
    width:900px;
}

.item{
    width:100px;
    flex-grow:1;
}
```

Container Width

```
900px
```

Initial Width

```
100 + 100 + 100 = 300px
```

Remaining

```
600px
```

Grow Ratio

```
1 : 1 : 1
```

Each receives

```
200px
```

Final Width

```
300px
300px
300px
```

---

## Different Ratios

```css
.box1{
    flex-grow:1;
}

.box2{
    flex-grow:2;
}

.box3{
    flex-grow:1;
}
```

Ratio

```
1 : 2 : 1
```

Extra space is divided according to this ratio.

---

## Real World Uses

- Search bar
- Sidebar layout
- Dashboard
- Chat application
- Main content area

---

## Common Mistakes

❌ Thinking flex-grow changes container size.

❌ Thinking it works when there is no free space.

❌ Confusing width with flex-grow.

---

## Interview Questions

- What is the default value of flex-grow?
- How is free space distributed?
- Difference between width and flex-grow?