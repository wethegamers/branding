# Branding Repository - AI Coding Agent Instructions

**Version**: 1.0.0  
**Last Updated**: 2025-11-30  
**Repository**: wethegamers/branding

> **Master Instructions**: See `/home/seb/wtg/.github/copilot-instructions.md` for platform-wide standards.

---

## Purpose & Scope

This repository contains **branding assets** for WeTheGamers:
- Logos and icons
- Color palettes
- Typography guidelines
- Style guides

## Repository Structure

```
branding/
├── logo/
│   ├── primary/          # Primary logo variants
│   ├── icon/             # Icon-only versions
│   └── wordmark/         # Wordmark versions
├── styles/
│   ├── colors.md         # Color palette
│   └── typography.md     # Font guidelines
└── README.md
```

## Asset Guidelines

### Logo Formats
- SVG (preferred for web)
- PNG (with transparency)
- Provide multiple sizes: 32px, 64px, 128px, 256px, 512px

### Color Definitions
Export colors in multiple formats:
- Hex: `#RRGGBB`
- RGB: `rgb(R, G, B)`
- HSL: `hsl(H, S%, L%)`
- CSS variables: `--wtg-primary`

### File Naming
```
{type}-{variant}-{size}.{ext}
logo-primary-512.png
icon-light-64.svg
```

## Usage

### Web Projects
```html
<img src="/branding/logo/primary/logo-primary-256.svg" alt="WeTheGamers">
```

### CSS Variables
```css
:root {
  --wtg-primary: #...;
  --wtg-secondary: #...;
  --wtg-accent: #...;
}
```

---

For platform-wide standards, see the master instructions at `/home/seb/wtg/.github/copilot-instructions.md`.
