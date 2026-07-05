# CSS Specificity

## Priority

Inline Style = 1000

ID = 100

Class = 10

Element = 1

---

Example

```css
#title{
    color:red;
}

.title{
    color:blue;
}

h1{
    color:green;
}
```

Output:

```
Red
```

---

## Rules

- ID beats Class.
- Class beats Element.
- If specificity is equal, the later rule wins.

---

## Avoid

Using too many IDs.

Avoid `!important`.

---

## Interview Questions

1. Calculate specificity.
2. Does an ID beat multiple classes?
3. When does source order matter?