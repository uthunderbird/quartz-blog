---
title: "Getting Started with Quartz"
description: "A guide to setting up and using Quartz for your blog"
tags: ["quartz", "setup", "guide"]
---

# Getting Started with Quartz

Quartz is a powerful static-site generator that transforms Markdown content into beautiful, functional websites. Here's how to get started.

## Key Features

- **Full-text search** - Find content quickly
- **Graph view** - Visualize connections between notes
- **Wikilinks** - Link between pages using `[[page name]]`
- **Backlinks** - See what pages link to the current page
- **Hot reload** - See changes instantly during development

## Writing Content

### Basic Markdown

Quartz supports standard Markdown syntax:

```markdown
# Heading 1
## Heading 2
### Heading 3

**Bold text** and *italic text*

- Bullet points
- More items

1. Numbered lists
2. Second item
```

### Wikilinks

Use double brackets to create internal links:

```markdown
[[Welcome to My Blog]]
[[Getting Started with Quartz]]
```

### Tags

Add tags to organize your content:

```markdown
---
tags: ["quartz", "setup", "guide"]
---
```

## Development

To start the development server:

```bash
npm run dev
```

To build for production:

```bash
npm run build
```

## Next Steps

- Explore the [[Welcome to My Blog|main page]]
- Check out the [Quartz documentation](https://quartz.jzhao.xyz/)
- Start writing your own content!

---

*This guide covers the basics of using Quartz for your blog.*
