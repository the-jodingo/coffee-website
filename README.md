[![CI](https://github.com/the-jodingo/coffee-website/actions/workflows/ci.yml/badge.svg)](https://github.com/the-jodingo/coffee-website/actions/workflows/ci.yml)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
# Aroma — Premium Coffee Landing Page

A single-page marketing site for a fictional coffee brand. Plain HTML, CSS, and vanilla JavaScript.

## Table of contents

- [Requirements](#requirements)
- [Usage](#usage)
- [Deployment](#deployment)
- [Accessibility](#accessibility)
- [License](#license)

## Requirements

A modern web browser. No build step, no dependencies, no server required.

## Usage

```bash
git clone https://github.com/the-jodingo/coffee-website.git
cd coffee-website
python3 -m http.server 8000
```

Open <http://localhost:8000>. You can also open `index.html` directly.

## Deployment

Any static host works — Netlify, GitHub Pages, Cloudflare Pages, S3, or nginx.
The page is a single file with no build step, so you can drag the folder in.

## Accessibility

- semantic landmarks and a logical heading order
- all text meets WCAG AA contrast
- keyboard-navigable, with visible focus states
- responsive layout, usable from 320 px wide
- CI runs an axe-core scan and HTML validation on every push

## License

[MIT](LICENSE) © Joash Odingo
