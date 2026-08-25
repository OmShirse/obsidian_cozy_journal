# Cozy Journal

A warm, dark journaling theme for Obsidian. Pure black background, warm amber accents, serif reading font, and Notion-style gradient banners no plugins required.

## Features

- Pure black (`#000000`) background
- Warm amber/brown accent palette
- Serif font for cozy long-form journaling
- Redesigned sidebar, tabs, and status bar
- Rounded blockquotes, code blocks, and tags
- Respects Obsidian's "Readable line length" setting
- **Notion-style banners**  no plugin needed

## Installation

1. Download `Manifest.json` and `theme.css`
2. In your vault, create folder: `.obsidian/themes/Cozy Journal/`
3. Place both files inside
4. Obsidian → Settings → Appearance → Themes → select **Cozy Journal**

## Banners

Add a colored gradient banner to any note  no plugin required:

```yaml
---
cssclasses: banner-1
---
```

Available banners:

|Class|Color|
|---|---|
|`banner-1`|Warm amber|
|`banner-2`|Green|
|`banner-3`|Purple|
|`banner-4`|Red|

## Customization

Edit color variables at the top of `theme.css` (e.g. `--background-primary`, `--interactive-accent`) to adjust the palette.

## License

MIT
