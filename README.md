<div align="center">

# Base64 Encoder / Decoder

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?style=flat-square)](https://soumendrak.github.io/base64/)
[![MIT License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26?style=flat-square&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![Zero Dependencies](https://img.shields.io/badge/dependencies-0-success?style=flat-square)](https://www.w3.org/TR/html52/)

<!-- Inline SVG logo -->
<svg width="140" height="140" viewBox="0 0 140 140" xmlns="http://www.w3.org/2000/svg">
<rect width="140" height="140" rx="24" fill="#0a0a14"/>
  <text x="70" y="48" text-anchor="middle" font-family="monospace" font-size="11" fill="#5a5a6e">Hello</text>
  <path d="M 70 52 L 50 68 L 90 68 Z" fill="#ff6b35" opacity="0.3"/>
  <text x="70" y="82" text-anchor="middle" font-family="monospace" font-size="9" fill="#ff6b35">SGVsbG8=</text>
  <rect x="16" y="100" width="108" height="1" fill="#2a2a2a"/>
  <text x="70" y="118" text-anchor="middle" font-family="monospace" font-size="9" fill="#5a5a6e">SGVsbG8=</text>
  <path d="M 70 122 L 50 106 L 90 106 Z" fill="#4caf7d" opacity="0.3"/>
  <text x="70" y="136" text-anchor="middle" font-family="monospace" font-size="11" fill="#f0ece4">Hello</text>
</svg>

**Encode and decode text — and small files — to and from Base64 instantly.**

**Live:** [https://soumendrak.github.io/base64/](https://soumendrak.github.io/base64/)

</div>

---

## Features

- Encode and Decode tabs for text ↔ Base64
- File encoding via drag-and-drop or click-to-upload (FileReader)
- Shows file name and size for uploaded files
- Copy to clipboard button for results
- Dark theme with orange accent (#ff6b35)
- Zero dependencies — single HTML file

## How It Works

Text encoding uses `btoa()` and `atob()` with UTF-8-safe encoding via `encodeURIComponent`. File encoding reads the uploaded file as an ArrayBuffer, converts to a binary string, then calls `btoa()` on the result. The UI uses CSS tabs (radio-button hack) to switch between encode/decode modes.

## Usage

1. Open `https://soumendrak.github.io/base64/` in any browser.
2. No build step, no installation, no server required.
3. Deploy anywhere — GitHub Pages, Netlify, or any static host.

```bash
git clone https://github.com/soumendrak/base64.git
# Open index.html directly
```

## License

Licensed under the [MIT License](LICENSE).

---

<p align="center"><sub>Built with ❤️ and zero dependencies</sub></p>
