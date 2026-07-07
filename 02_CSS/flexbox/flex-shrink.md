# CSS Flexbox - flex-shrink

## Definition

`flex-shrink` determines how much a flex item should shrink when there is not enough space inside the flex container.

It distributes **negative free space**.

---

## Syntax

```css
.item{
    flex-shrink:1;
}
```

---

## Default Value

```css
flex-shrink:1;
```

Meaning:

Every item is allowed to shrink.

---

## Browser Algorithm

```
Container Width

↓

Enough Space?

↓

No

↓

Read flex-shrink

↓

Remove width proportionally
```

---

## Example

Container

```
600px
```

Three Boxes

```
300px
300px
300px
```

Need

```
900px
```

Missing

```
300px
```

Shrink Ratio

```
1 : 1 : 1
```

Final Width

```
200px
200px
200px
```

---

## Different Ratios

```css
.box1{
    flex-shrink:1;
}

.box2{
    flex-shrink:2;
}

.box3{
    flex-shrink:1;
}
```

Ratio

```
1 : 2 : 1
```

Box2 shrinks twice as much.

---

## flex-shrink:0

```css
.item{
    flex-shrink:0;
}
```

Meaning

The item will never shrink.

---

## Real World Uses

- Logo
- Sidebar
- Profile Picture
- Login Button

---

## Common Mistakes

❌ Thinking shrink always happens.

❌ Confusing width with shrink.

❌ Forgetting the default value is 1.

---

## Interview Questions

- Default value?
- Difference between grow and shrink?
- When do we use shrink:0?