---
title: "Markdown Showcase — All the Things"
pubDate: 2026-06-18
author: 'Demo Writer'
authImage: 'https://images.unsplash.com/photo-1544005313-94ddf0286df2?auto=format&fit=crop&w=80&q=80'
image: 'https://images.unsplash.com/photo-1515378791036-0648a3ef77b2?auto=format&fit=crop&w=1200&q=80'
tags: ['test', 'markdown', 'showcase']
slug: test-articles/markdown-showcase
summary: "A single post that demonstrates headings, lists, code blocks, tables, footnotes, images, and other common Markdown features."
type: "Article"
---

# Markdown Showcase

Welcome — this article demonstrates many common Markdown elements you can use in posts.

## Emphasis and inline elements

You can use *italic*, **bold**, and ***both***. ~~Strikethrough~~ also works.

Inline code: `const x = 1;` and a code span with `--flag`.

Link: [Astro website](https://astro.build) — opens in a new tab when rendered by the browser.

Image (remote Unsplash):

![Demo image](https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?auto=format&fit=crop&w=1200&q=80)

---

## Headings

### H3 — Example

#### H4 — Example

##### H5 — Example

###### H6 — Example

---

## Lists

Unordered list:

- Item one
- Item two
  - Nested item A
  - Nested item B
- Item three

Ordered list:

1. First
2. Second
   1. Second.A
   2. Second.B
3. Third

Task list (GitHub-style):

- [x] Write demo
- [ ] Review content
- [ ] Publish

---

## Code blocks

Bash example:

```bash
# install dependencies
npm ci
```

JavaScript example:

```js
export function greet(name) {
  return `Hello, ${name}!`;
}
console.log(greet('Markdown'));
```

SQL example:

```sql
SELECT id, title FROM posts WHERE published = true ORDER BY pubDate DESC;
```

---

## Table

| Feature       | Supported | Notes |
| ------------- | ---------:| ----- |
| Headings      | Yes       | #, ##, ### |
| Code fences   | Yes       | Triple backticks with language |
| Tables        | Yes       | Basic pipe tables |

---

## Blockquote

> This is a blockquote. Use blockquotes for important notes or citations.
>
> — Demo Writer

---

## Footnotes

Here is a statement that needs a citation.[^1]

[^1]: This is the footnote content. Footnotes render at the bottom of the article.

---

## HTML (inline)

You can include inline HTML if needed: <span style="color: #2b6cb0;">styled text</span>.

---

## Definition-style sample

Term
: Definition for the term. (Not standard in all renderers, but many support it.)

---

## Emoji and special characters

Use emoji for tone: 😄 🚀 ✨

---

## Math (KaTeX) — inline and block

Inline math: $E = mc^2$.

Block math:

$$
\int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi}
$$

(Note: KaTeX rendering depends on site config.)

---

## Conclusion

This file includes most of the common Markdown features you will use when authoring posts. Edit the frontmatter to change title, tags, or the `slug` (for nested URLs keep slashes in the slug).

If you want I can:

- Add this post to the index automatically, or
- Convert images to local `src/assets` imports and optimize them.
