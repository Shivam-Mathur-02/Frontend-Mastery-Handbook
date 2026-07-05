# CSS Cascade

## What is the Cascade?

The cascade is the process the browser uses to decide which CSS rule wins when multiple rules target the same element.

Priority:

1. `!important`
2. Specificity
3. Source Order

---

## Example

```css
p{
    color:red;
}

p{
    color:blue;
}
```

Output:

```
Blue
```

Because the second rule comes later.

---

## Best Practices

- Keep specificity low.
- Avoid `!important`.
- Write CSS in a logical order.

---

## Interview Questions

- What is the CSS Cascade?
- What decides which rule wins?