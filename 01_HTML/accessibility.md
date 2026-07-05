# HTML Accessibility

## What is Accessibility?

Accessibility means making websites usable by everyone, including people with disabilities.

---

## Who Benefits?

- Blind users
- Low vision users
- Color blind users
- Motor impaired users
- Hearing impaired users

---

## Important Rules

### Use Semantic HTML

Good

```html
<nav></nav>
```

Bad

```html
<div class="nav"></div>
```

---

### Images

Meaningful image

```html
<img src="dog.jpg" alt="Golden Retriever playing in the park">
```

Decorative image

```html
<img src="background.png" alt="">
```

---

### Labels

Good

```html
<label for="email">

Email

</label>

<input id="email">
```

---

### Keyboard Navigation

Users should be able to navigate using

- Tab
- Shift + Tab
- Enter
- Space

---

## Focus

Never remove focus outlines without providing a replacement.

---

## Benefits

- Better usability
- Better SEO
- Better user experience
- Legal compliance

---

## Common Mistakes

❌ Missing labels

❌ Missing alt text

❌ Using div instead of button

❌ Removing focus outlines

---

## Interview Questions

1. What is accessibility?
2. What is alt text?
3. Why are labels important?
4. Why use semantic HTML?

---

## Cheat Sheet

- Semantic HTML
- Labels
- Alt text
- Keyboard navigation
- Visible focus