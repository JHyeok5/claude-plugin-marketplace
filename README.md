# JHyeok5 Plugin Marketplace

[![Plugins](https://img.shields.io/badge/plugins-3-blue?style=flat-square)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)]()

Claude Code plugin marketplace with production-grade tools for web development.

## Add This Marketplace

```bash
claude plugin marketplace add JHyeok5/claude-plugin-marketplace
```

## Available Plugins

| Plugin | Description | Install |
|--------|-------------|---------|
| **[ai-seo](https://github.com/JHyeok5/claude-plugin-ai-seo)** | AEO/GEO optimization for AI search engines | `/plugin install ai-seo@JHyeok5` |
| **[i18n-audit](https://github.com/JHyeok5/claude-plugin-i18n-audit)** | Multi-locale consistency checker (11 frameworks) | `/plugin install i18n-audit@JHyeok5` |
| **[netlify-functions](https://github.com/JHyeok5/claude-plugin-netlify-functions)** | Serverless API patterns with auto-detection | `/plugin install netlify-functions@JHyeok5` |

## Plugin Highlights

### All plugins feature:

- **Project Adaptation** — creates config on first run, learns your project patterns
- **Progress Tracking** — history with delta comparison across runs
- **Auto-Check Hooks** — PostToolUse hooks monitor file edits in real-time
- **Zero Dependencies** — pure bash/Node.js, no npm packages required
- **Framework Detection** — adapts behavior to your tech stack

## Quick Start

```bash
# 1. Add marketplace
claude plugin marketplace add JHyeok5/claude-plugin-marketplace

# 2. Install any plugin
/plugin install i18n-audit@JHyeok5

# 3. Restart Claude Code

# 4. Use naturally
"Check if all translations are complete"
```
