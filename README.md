![Cozy Journal screenshot](Obsidian_theme.png)

# Cozy Journal

A minimal, dark journaling theme for Obsidian. Pure black everywhere, white text, lavender bold/italic accents, serif reading font — no plugins required.

> **Version:** 1.2.2 · **Author:** [OmShirse](https://github.com/OmShirse) · **License:** MIT

---

## ✨ Features

- **Pure black** (`#000000`) background — editor, sidebar, and all UI chrome
- **White body text** — clean, high contrast on pure black
- **Lavender bold/italic** — `#c8b8f0` bold, `#b0a0d8` italic
- **No underline links** — white links, underline appears only on hover
- **Serif font** (Georgia / Iowan Old Style) for cozy long-form journaling
- **JetBrains Mono / Fira Code** for code blocks
- **Default heading sizes** — Obsidian native sizes, white color
- **Redesigned sidebar** — rounded tiles, pure black with neutral hover
- **Redesigned tabs** — rounded corners, neutral active state
- **Styled status bar** — minimal, muted
- **Rounded blockquotes** — italic, subtle border
- **Rounded code blocks** — near-black background, neutral text
- **Muted pill tags** — compact, neutral tones
- **Custom scrollbars** — slim, rounded
- **Justified text** — in both Reading View and Live Preview
- **Minimalist list bullets** — `›` chevron in muted faint color
- **Hover image zoom** — images scale up smoothly with rounded borders
- **Hidden frontmatter box** — properties panel hidden by default
- **Respects "Readable line length"** — max 720px centered; full-width when disabled
- **Canvas node defaults** — 360×260px default canvas node size

---

## 🚀 Installation

1. Download `manifest.json` and `theme.css`
2. In your vault, create the folder: `.obsidian/themes/Cozy Journal/`
3. Place both files inside
4. In Obsidian: **Settings → Appearance → Themes → select Cozy Journal**

---

## 🎨 Banners

Add a colored gradient banner to any note — no plugin required:

```yaml
---
cssclasses: banner-1
---
```

| Class | Color |
|---|---|
| `banner-1` | Warm amber |
| `banner-2` | Green |
| `banner-3` | Purple |
| `banner-4` | Red |

---

## 🛠 Customization

Edit CSS variables at the top of `theme.css` to tweak the look:

| Variable | Default | Purpose |
|---|---|---|
| `--background-primary` | `#000000` | Main background |
| `--interactive-accent` | `#4a4a5a` | Accent color (tabs, active states, borders) |
| `--text-normal` | `#ffffff` | Body text color |
| `--bold-color` | `#c8b8f0` | Bold text (lavender) |
| `--link-color` | `#ffffff` | Link color |
| `--font-text` | Georgia, serif | Body font |
| `--font-monospace` | JetBrains Mono | Code font |
| `--file-line-width` | `720px` | Max readable line width |

---

## 📋 Changelog

### v1.2.2
- Removed all warm/yellow tones from sidebar, UI chrome, borders, and hover states
- Pure black neutral palette throughout — no more yellowish sidebar
- Neutral grey borders (`#2a2a2a`) replace warm brown borders
- Code blocks: near-black background, neutral grey text
- Heading font sizes reset to Obsidian defaults (no custom overrides)
- Removed `!important` from canvas selected node styles

### v1.2.1
- Replaced heavy amber/orange palette with neutral-warm stone tones
- Links set to white, no underline by default (underline on hover)
- Bold and italic shifted to muted lavender
- List bullet changed from `◈` to `›` with muted faint color

### v1.2.0
- Initial full dark warm overhaul

---

## 📄 License

MIT
