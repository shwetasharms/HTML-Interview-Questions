## HTML-Interview-Questions (Quick Revision)

### What is the difference between block and inline elements in HTML?
<details><summary><strong>What is the differnce between <section> , <article> and <aside></strong></summary>
  1. <article>: The Independent Unit
An <article> is intended to be self-contained. If you were to take the content out of the website and put it on a completely different page, it should still make sense on its own.

Best for: Blog posts, news stories, forum posts, or product cards.

Key mindset: "Could this be syndicated via an RSS feed?" If yes, it’s an article.

2. <section>: The Thematic Group
A <section> is a way to group related content together, usually with a heading. It is a piece of a larger whole, rather than something that stands alone.

Best for: Chapters of a document, "About Us" areas, or tabbed content.

Key mindset: It’s a logical "chapter" of your page.

3. <aside>: The Extra Context
An <aside> contains content that is tangentially related to the content around it. If you removed it, the main point of the page wouldn't change, but the user would lose some helpful "side" info.

Best for: Sidebars, pull-quotes, advertising, or "related links."

Key mindset: "This is related, but it’s not the main course."
</details>

## What is the purpose of the alt attribute in an <img> tag? Why is it important for web accessibility?
### 
## What is the difference between <div> and <section> elements in HTML?

### 1. What is DOCTYPE in HTML? Why is it important?

### 2. Difference between `<div>` and `<span>`?

### 3. What are semantic HTML tags? Why do we use them?

### 4. Explain HTML accessibility (A11Y).

### 5. What is the difference between `id` and `class`?

### 6. What is a `<meta>` tag? Types and uses?

### 7. Difference between `<script>`, `<script defer>`, and `<script async>`?

### 8. What is the difference between `<link>` and `<script>`?

### 9. What is the `alt` attribute in `<img>` tag and why is it important?

### 10. What is Local Storage vs Session Storage vs Cookies?

### 11. What is Critical Rendering Path?

### 12. What are Web Components?

### 13. Explain Shadow DOM

### 14. HTML parsing vs DOM construction?

### 15. What are custom data attributes? (`data-*`)

### 16. What is Progressive Enhancement vs Graceful Degradation?

### 17. Explain Lazy Loading images

### 18. CSP (Content Security Policy) meta tag?

### 19. What is the purpose of `rel="noopener noreferrer"` in links?

### 20. Difference between `<strong>` vs `<b>` and `<em>` vs `<i>`?

### 21. How do you optimize HTML for performance?

Answers include:

* defer/async scripts
* preload/preconnect
* image optimization
* minimize DOM nodes

### 22. What is HTML Minification?

### 23. Difference between SEO tags like `canonical`, `robots`, `og:title` etc.

## ✅ **Table/Form-based questions**

### 24. Explain form validation attributes in HTML5

`required`, `pattern`, `min`, `max`, `novalidate`, etc.

### 25. Difference between `<button type="submit">` vs `<button type="button">`

### 26. Input types in HTML5 (date, email, number, range etc.)

## ✅ **Scenario-Based Questions**

### 27. How to improve accessibility for a custom component?

Mention ARIA roles (`role="button"`, `aria-expanded`)

### 28. How to structure a Landing Page using semantic HTML?

Explain sections, header/nav, footer.

### 29. Why `label` is important in forms? How to associate it with input?

### 30. How do you handle large HTML tables for better UX?

Sticky header, pagination, `aria` roles.

---

## ✅ **Tricky Questions**

| Question                                    | Key Point                                  |
| ------------------------------------------- | ------------------------------------------ |
| Can a `<div>` be inside `<p>`?              | No, invalid nesting                        |
| Difference between `<iframe>` and `<embed>` | Iframe: webpage; embed: media content      |
| What happens if you don't close tags?       | Browser auto-fixes but risky               |
| Difference between DOM and Virtual DOM?     | DOM belongs to HTML, VDOM to JS frameworks |


