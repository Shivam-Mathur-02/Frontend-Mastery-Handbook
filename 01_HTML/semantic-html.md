# Semantic HTML

## What is Semantic HTML?

Semantic HTML uses meaningful HTML elements that describe the purpose of their content rather than just how it looks.

Instead of using generic `<div>` elements everywhere, semantic elements make the structure of the page meaningful.

---

## Why was Semantic HTML introduced?

Earlier, developers built pages like this:

```html
<div class="header"></div>
<div class="menu"></div>
<div class="content"></div>
<div class="footer"></div>
```

The browser had no idea which part was navigation, main content, or footer.

Semantic HTML solves this problem.

---

## Common Semantic Elements

| Element | Purpose |
|----------|---------|
| `<header>` | Top section of page |
| `<nav>` | Navigation links |
| `<main>` | Main content |
| `<section>` | Related content |
| `<article>` | Independent content |
| `<aside>` | Sidebar or extra content |
| `<footer>` | Bottom section |

---

## Example

```html
<header>
    <nav>
        <a href="#">Home</a>
        <a href="#">Projects</a>
    </nav>
</header>

<main>

<section>

<h2>About Me</h2>

<p>Frontend Developer</p>

</section>

<section>

<h2>Projects</h2>

<article>

<h3>Portfolio Website</h3>

<p>Built using HTML and CSS.</p>

</article>

</section>

</main>

<footer>

<p>© 2026 Shivam Mathur</p>

</footer>
```

---

## Benefits

- Better accessibility
- Better SEO
- Easier maintenance
- Better readability
- Helps search engines understand the page

---

## Best Practices

- Use only one `<main>` element.
- Prefer semantic elements over generic `<div>` elements.
- Maintain proper heading hierarchy.
- Use `<article>` for standalone content.

---

## Common Mistakes

❌ Using only `<div>` tags.

❌ Skipping heading levels.

❌ Multiple `<main>` elements.

---

## Interview Questions

1. What is Semantic HTML?
2. Why is Semantic HTML important?
3. Difference between `<section>` and `<article>`?
4. Why use `<main>`?

---

## Cheat Sheet

```
<header>

<nav>

<main>

<section>

<article>

<aside>

<footer>
```