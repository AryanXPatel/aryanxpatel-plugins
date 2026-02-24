# Aryan Patel's Claude Code Plugins

AI-powered creative tools for Claude Code.

## Available Plugins

| Plugin | Description | Version |
|--------|-------------|---------|
| [gemini-image-gen](https://github.com/AryanXPatel/gemini-image-gen) | Generate stunning images with Gemini 3 Pro using viral prompt optimization | 1.0.0 |
| [page-clone-brief](https://github.com/AryanXPatel/page-clone-brief) | Extract design tokens, layout, components, and data schemas from any website | 1.0.0 |

---

### gemini-image-gen

Generate images directly from Claude Code using Google's Gemini 3 Pro Image model. Features:

- **Smart prompt optimization** - 6 rules derived from 1,186 viral AI prompts
- **Genre detection** - Auto-applies techniques for food, portrait, product, cinematic, 3D, design
- **Dual API support** - Works with direct Gemini API or proxy
- **Lightweight architecture** - Uses ~500 tokens instead of 50K

**Sample outputs:**

<p align="center">
  <img src="assets/demo-images/sample-1.jpg" width="250" alt="Cyberpunk city">
  <img src="assets/demo-images/sample-2.jpg" width="250" alt="Fantasy landscape">
  <img src="assets/demo-images/sample-3.jpg" width="250" alt="Product shot">
</p>

---

### page-clone-brief

Extract everything Claude needs to rebuild any webpage from scratch. Produces a comprehensive JSON document ("Page Clone Brief") with 21 data layers extracted in parallel via Playwright.

- **21 parallel extractors** - Colors, typography, spacing, layout, components, navigation, tables, responsive behavior
- **Authenticated pages** - Save browser sessions and extract from login-protected pages
- **Two extraction methods** - Standalone CLI or interactive via Playwright MCP
- **Full page cloning** - Design tokens + page structure + content + data schemas

**Extracted data layers:**

| Category | What's Captured |
|----------|----------------|
| Design Tokens | Colors, typography, spacing, borders, shadows, breakpoints |
| Page Structure | Layout type, regions, sticky/fixed positioning |
| Components | Buttons, inputs, badges + full catalog (tables, cards, forms, modals, tabs, charts) |
| Navigation | Sidebar items with icons/badges/children, header, breadcrumbs, tabs |
| Data Schemas | Table columns with inferred types, sample rows, features |
| Responsive | Layout state at desktop (1920px), tablet (768px), mobile (390px) |

---

## Quick Install

### 1. Add This Marketplace

```
/plugin marketplace add AryanXPatel/aryanxpatel-plugins
```

### 2. Install a Plugin

```
/plugin install gemini-image-gen@aryanxpatel
/plugin install page-clone-brief@aryanxpatel
```

### 3. Use

**Image generation:**
```
/image a cyberpunk city at night with neon lights
```

**Website cloning:**
```
/clone-site https://example.com/dashboard
```

## Commands

| Action | Command |
|--------|---------|
| Add marketplace | `/plugin marketplace add AryanXPatel/aryanxpatel-plugins` |
| Install plugin | `/plugin install <name>@aryanxpatel` |
| Update plugin | `/plugin update <name>@aryanxpatel` |
| Remove plugin | `/plugin uninstall <name>@aryanxpatel` |
| List installed | `/plugin list` |

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on:
- Reporting bugs
- Requesting features
- Suggesting new plugins

## License

MIT - See [LICENSE](LICENSE)

## Author

**Aryan Patel** - [@AryanXPatel](https://github.com/AryanXPatel)
