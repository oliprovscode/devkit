# devkit — Developer Utilities

A beautiful, zero-dependency browser toolkit for developers. No build step. No backend. Just open it and go.

## Tools

| Tool | What it does |
|------|-------------|
| **JWT Decoder** | Decode JWT tokens, inspect header/payload, check expiry |
| **Base64** | Encode and decode Base64 strings |
| **URL Encode** | URL encode/decode components |
| **Hash (SHA)** | Generate SHA-256, SHA-384, SHA-512 hashes via Web Crypto API |
| **JSON Formatter** | Format and minify JSON with validation |
| **Text Diff** | Line-by-line LCS diff between two text blocks |
| **UUID Generator** | Generate v4 (random) and v7 (time-ordered) UUIDs |
| **Regex Tester** | Live regex testing with match highlighting and group capture |
| **Color Converter** | Convert between HEX, RGB, HSL, and OKLCH |

## Usage

Just open `devkit.html` in any modern browser — no installation, no server, no dependencies.

```
git clone https://github.com/oliprovscode/devkit
open devkit.html
```

## Features

- **Dark & light mode** — follows system preference, with manual toggle
- **Keyboard accessible** — full focus management and ARIA labels
- **Responsive** — works on mobile and desktop
- **Zero dependencies** — vanilla JS, Web Crypto API
- **Instant feedback** — all tools react in real-time as you type

## Tech

- Vanilla JavaScript (no build step)
- Web Crypto API for SHA hashing
- CSS custom properties + OKLCH color system
- JetBrains Mono + Inter fonts

## License

MIT — see [LICENSE](LICENSE)
