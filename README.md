![Cozy Journal screenshot](Obsidian_theme.png)

# Cozy Journal

A warm, dark journaling theme for Obsidian. Pure black background, warm amber accents, serif reading font, and Notion-style gradient banners — no plugins required.

> **Version:** 1.1.0 · **Author:** [OmShirse](https://github.com/OmShirse) · **License:** MIT

---

## ✨ Features

- **Pure black** (`#000000`) background — easy on the eyes
- **Warm amber/brown** accent palette (`#b5732f` → `#e0a458`)
- **Serif font** (Georgia / Iowan Old Style) for cozy long-form journaling
- **JetBrains Mono / Fira Code** for code blocks
- **Tiered heading colors** — H1–H6 each have a distinct warm amber shade
- **Redesigned sidebar** — rounded file/folder tiles with hover highlights
- **Redesigned tabs** — rounded corners, amber active state
- **Styled status bar** — minimal, muted
- **Rounded blockquotes** — italic, amber left border
- **Rounded code blocks** — dark background with border
- **Amber pill tags** — bold and compact
- **Custom scrollbars** — slim, rounded, amber on hover
- **Justified text** — in both Reading View and Live Preview
- **Custom list bullets** — `◈` diamond icon in accent color
- **Hover image zoom** — images scale up smoothly on hover with rounded borders
- **Hidden frontmatter box** — properties panel hidden by default for a cleaner look
- **Notion-style banners** — colored gradient header per note, no plugin needed
- **Respects "Readable line length"** — max 720px centered; full-width when disabled

---

## 🖼 Canvas Styling *(CSS-only, no plugin needed)*

Cozy Journal ships with rich Canvas styling inspired by the Advanced Canvas plugin — all pure CSS, zero dependencies.

| Feature | Details |
|---|---|
| **Warm dot-grid background** | Dark `#0d0b09` canvas with subtle warm dot pattern |
| **Node cards** | Rounded corners, dark bg, warm shadow + hover lift |
| **Selection glow** | Amber ring highlight on focused/selected nodes |
| **6 node color classes** | Red, Amber, Gold, Green, Teal, Purple — each with bg tint, border & label color |
| **Node font styling** | Georgia serif content font, muted label text |
| **Node shapes** | `.mod-pill` (fully rounded) · `.mod-diamond` (45° rotated) |
| **Edge / arrow styling** | Warm brown strokes, amber on hover, 6 color variants |
| **Dashed edges** | `.mod-dashed` stroke-dasharray pattern |
| **Arrow markers** | Arrowhead fill matches edge color |
| **Group nodes** | Dashed amber border, uppercase small label, color tints |
| **Canvas scrollbars** | Scoped warm scrollbar inside `.canvas-wrapper` |
| **Mini-map** | Dark translucent panel, amber border, soft shadow |
| **Toolbar / controls** | Sidebar-matched dark bg, amber on hover |
| **Text nodes** | Transparent bg (sticky-note style), border appears on hover |
| **Link / URL nodes** | Very dark bg with link-colored text |

### Node colors in action

Right-click any canvas node → **Color** → pick 1–6:

| # | Color | Accent |
|---|---|---|
| 1 | 🔴 Red / Rose | `#8b2e2e` |
| 2 | 🟠 Amber *(theme accent)* | `#b5732f` |
| 3 | 🟡 Gold | `#a09020` |
| 4 | 🟢 Moss Green | `#3a7a4a` |
| 5 | 🔵 Teal | `#2a7080` |
| 6 | 🟣 Purple | `#6040a0` |

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
| `--interactive-accent` | `#b5732f` | Accent color (tabs, tags, borders) |
| `--text-accent` | `#e0a458` | Link & bullet color |
| `--font-text` | Georgia, serif | Body font |
| `--font-monospace` | JetBrains Mono | Code font |
| `--file-line-width` | `720px` | Max readable line width |

---

## 📄 License

MIT
