# Aryan Patel's Claude Code Plugins

AI-powered creative tools for Claude Code.

## Available Plugins

| Plugin | Description | Version |
|--------|-------------|---------|
| [gemini-image-gen](https://github.com/AryanXPatel/gemini-image-gen) | Generate stunning images with Gemini 3 Pro using viral prompt optimization | 1.0.0 |

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

## Quick Install

### 1. Add This Marketplace

```
/plugin marketplace add AryanXPatel/aryanxpatel-plugins
```

### 2. Install a Plugin

```
/plugin install gemini-image-gen@aryanxpatel
```

### 3. Set Your API Key

```bash
export GEMINI_API_KEY=your_key_here
```

### 4. Generate Images

```
/image a cyberpunk city at night with neon lights
```

## Commands

| Action | Command |
|--------|---------|
| Add marketplace | `/plugin marketplace add AryanXPatel/aryanxpatel-plugins` |
| Install plugin | `/plugin install gemini-image-gen@aryanxpatel` |
| Update plugin | `/plugin update gemini-image-gen@aryanxpatel` |
| Remove plugin | `/plugin uninstall gemini-image-gen@aryanxpatel` |
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
