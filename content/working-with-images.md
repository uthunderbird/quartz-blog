---
title: "Working with Images in Quartz"
description: "Complete guide to adding and managing images in your Quartz blog"
tags: ["images", "media", "tutorial", "quartz"]
---

# Working with Images in Quartz

[[Working with Images in Quartz]] is essential for creating engaging blog content. Quartz supports multiple ways to include images in your articles.

## Image Methods

### 1. Local Images (Recommended)

Store images in the `content/images/` directory and reference them:

```markdown
![Alt text](images/image-name.jpg)
```

**Example:**
```markdown
![Web Development Diagram](images/web-dev-diagram.png)
```

### 2. Relative Path Images

For images in subdirectories:

```markdown
![Screenshot](images/screenshots/app-interface.png)
```

### 3. External Images

Link to images hosted elsewhere:

```markdown
![External Image](https://example.com/image.jpg)
```

### 4. Images with Captions

Add descriptive captions:

```markdown
![React Components](images/react-components.png)
*Figure 1: React component hierarchy*
```

## Best Practices

### Image Optimization

- **Use WebP format** when possible for better compression
- **Optimize file sizes** - aim for under 500KB per image
- **Use appropriate dimensions** - don't upload 4K images for thumbnails
- **Add alt text** for accessibility

### File Organization

```
content/
├── images/
│   ├── screenshots/
│   ├── diagrams/
│   ├── photos/
│   └── icons/
└── articles/
```

### Naming Conventions

- Use **kebab-case**: `web-development-diagram.png`
- Be **descriptive**: `react-component-hierarchy.png`
- Include **version numbers** if needed: `logo-v2.png`

## Image Types for Different Content

### Screenshots
```markdown
![Code Editor](images/screenshots/vscode-interface.png)
```

### Diagrams
```markdown
![Database Schema](images/diagrams/database-schema.png)
```

### Photos
```markdown
![Workspace Setup](images/photos/desk-setup.jpg)
```

### Icons and Logos
```markdown
![React Logo](images/icons/react-logo.svg)
```

## Advanced Image Features

### Resizing Images

Quartz can handle image resizing automatically:

```markdown
![Large Image](images/large-image.jpg)
*This image will be automatically optimized*
```

### Image Galleries

Create image galleries using multiple images:

```markdown
![Project Screenshot 1](images/project-1.png)
![Project Screenshot 2](images/project-2.png)
![Project Screenshot 3](images/project-3.png)
```

### Images in Lists

```markdown
## Technology Stack

- ![React](images/icons/react.svg) React for frontend
- ![Node.js](images/icons/nodejs.svg) Node.js for backend
- ![MongoDB](images/icons/mongodb.svg) MongoDB for database
```

## Integration with Articles

### In [[Web Development Journey]]

Add visual elements to enhance your learning path:

```markdown
![Learning Path](images/diagrams/web-dev-path.png)
*My journey through web development technologies*
```

### In [[React Development]]

Include code examples with screenshots:

```markdown
![React Component Example](images/screenshots/react-component.png)
*Example of a React functional component*
```

### In [[Database Design]]

Show database schemas and relationships:

```markdown
![Database Schema](images/diagrams/user-database-schema.png)
*User authentication database schema*
```

## Tools for Image Creation

### Screenshots
- **Snipping Tool** (Windows)
- **Screenshot** (macOS)
- **Greenshot** (Cross-platform)

### Diagrams
- **Draw.io** (Free online)
- **Lucidchart** (Professional)
- **Miro** (Collaborative)

### Image Editing
- **GIMP** (Free)
- **Photoshop** (Professional)
- **Canva** (Online)

## Related Topics

- [[Web Development Journey]] - Add visual elements to your learning path
- [[React Development]] - Include component diagrams
- [[Database Design]] - Show schema visualizations
- [[API Development]] - Document API endpoints with screenshots

## Resources

- [[MDN Web Docs]] - Web image optimization
- [[FreeCodeCamp]] - Image handling tutorials
- [[Stack Overflow]] - Image-related questions

---

*Images make your content more engaging and help readers understand complex concepts visually.*
