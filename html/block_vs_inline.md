# Block vs Inline elements in HTML

## Block-level Elements
- *Block-level elements* occupy the full width available, regardless of their content.
- They start on a new line and cause a line break before and after themselves.
- Examples include: `<div>`, `<p>`, `<h1>`, `<ul>`, and `<section>`.

## Example :
```html
<div>
  This is a block-level element.
</div>
<p> This is another block-level element</p>
```

## Inline Element
- *Inline elements* take up only as much width as necessary based on their content.
- They do not start on a new line and remain within the flow of the content.
- Common inline elements include : `<span>`, `<a>`, `<em>` and `<strong>`, `<img>`

## Example :
```html
<p>This is a <span>inline element</span> inside a paragraph.</p>
```

## Key Differences
- **Block Elements:**
  - Take up the full width available.
  - Start on a new line.
  - Typically used for larger pieces of content structure.
- **Inline Elements:**
  - Take up only as much space as needed
  - Do not cause a line break.
  - Used for styleling or linking small parts of content with block-level elements.