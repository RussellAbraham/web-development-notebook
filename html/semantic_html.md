# Semantic HTML

Semantic HTML refers to using HTML tags that convey the meaning or structure of content rather than just the presentation.
It improves the clarity of the code and enhances accessibility, SEO and maintainabilty.

## Example

__Non-Semantic HTML:__

```html
<div class="header">
  <h1>Welcome to My Blog</h1>
</div>
<div class="content">
  <p>This is a blog post about semantic HTML.</p>
</div>
<div class="footer">
  <p>&copy; 2024 My Blog</p>
</div>
```

__Semantic HTML:__

```html
<header>
  <h1>Welcome to My Blog</h1>
</header>
<main>
  <article>
    <p>This is a blog post about semantic HTML.</p>
  </article>
</main>
<footer>
  <p>&copy; 2024 My Blog</p>
</footer>
```

### Key Semantic HTML Elements:

- `<header>`: Defines the header of a page or section.
- `<nav>`: Defines a block of navigation links.
- `<main>`: Represents the main content of a document.
- `<section>`: Groups content into thematic sections.
- `<article>`: Self-contained content that can be reused.
- `<footer>`: Defines the footer of a page or section.