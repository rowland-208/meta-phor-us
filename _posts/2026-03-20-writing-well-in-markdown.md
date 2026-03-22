---
layout: post
title: "Writing Well in Markdown"
date: 2026-03-20 08:00:00 -0000
categories: writing markdown
---

Markdown is the lingua franca of technical writing. It's used in README files, documentation, pull requests, issue trackers, and — of course — blogs like this one. Learning a handful of conventions goes a long way.

## The Basics

### Headings

Use `#` for headings. One `#` gives you an `<h1>`, two gives `<h2>`, and so on up to six levels.

### Emphasis

Wrap text in `*` or `_` for *italics*, and `**` or `__` for **bold**. You can combine them for ***bold italics***.

### Lists

Unordered lists use `-`, `*`, or `+`:

- Item one
- Item two
  - Nested item

Ordered lists use numbers:

1. First step
2. Second step
3. Third step

### Links and Images

```markdown
[Link text](https://example.com)
![Alt text](path/to/image.png)
```

### Code

Inline code uses backticks: `print("hello")`.

Fenced code blocks use triple backticks with an optional language identifier for syntax highlighting:

```python
def greet(name):
    return f"Hello, {name}!"
```

## Tips for Readable Posts

- **Keep paragraphs short.** Long walls of text are hard to skim.
- **Use headings liberally.** They help readers navigate and understand structure at a glance.
- **Show, don't tell.** Code examples, diagrams, and screenshots speak louder than descriptions.
- **Link generously.** Readers appreciate pointers to further reading.

Markdown is intentionally simple. That simplicity is a feature — it keeps you focused on what you're saying, not how it looks.
