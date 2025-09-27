# My Blog

A personal blog built with [Quartz](https://quartz.jzhao.xyz/), a fast, batteries-included static-site generator.

## Features

- 🔍 **Full-text search** - Find content quickly
- 🕸️ **Graph view** - Visualize connections between notes
- 🔗 **Wikilinks** - Link between pages using `[[page name]]`
- 📱 **Responsive design** - Works on all devices
- 🌙 **Dark mode** - Toggle between light and dark themes
- ⚡ **Fast loading** - Optimized for performance

## Getting Started

### Development

To start the development server:

```bash
npm run dev
```

The blog will be available at `http://localhost:8080`

### Building

To build for production:

```bash
npm run build
```

### Content

All content is stored in the `content/` directory as Markdown files. Use wikilinks (`[[page name]]`) to create connections between pages.

## Content Structure

- `content/index.md` - Homepage
- `content/about.md` - About page
- `content/getting-started-with-quartz.md` - Setup guide

## Customization

- `quartz.config.ts` - Main configuration
- `quartz.layout.ts` - Layout customization
- `content/` - Your blog content

## Learn More

- [Quartz Documentation](https://quartz.jzhao.xyz/)
- [Quartz GitHub Repository](https://github.com/jackyzha0/quartz)

---

*Built with Quartz v4.5.2*