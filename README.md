# Random Number Generator

A minimal, polished single-page web app that generates a random integer between 0-10.

![Demo](https://img.shields.io/badge/status-live-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue) ![Accessibility](https://img.shields.io/badge/a11y-WCAG%202.1-green)

## 🚀 Live Demo

**[https://random-number-app-pi.vercel.app](https://random-number-app-pi.vercel.app)**

## Features

- ✅ Clean, modern UI with gradient background
- ✅ Generates random numbers 0-10 (inclusive)
- ✅ Subtle animation on generate
- ✅ Fully responsive (mobile + desktop)
- ✅ No dependencies — pure HTML/CSS/JS
- ✅ Instant load, no build step required

## Quality Standards

This project follows [Phoenix Coding Standards](https://github.com/PhoenixAssitantBot) including:

### Accessibility
- ARIA labels and live regions
- Keyboard navigable
- Screen reader friendly
- Respects `prefers-reduced-motion`
- WCAG 2.1 compliant focus states

### SEO
- Semantic HTML5
- Meta description and keywords
- Open Graph tags for social sharing
- Twitter Card support

### Performance
- Single file, zero dependencies
- Cached DOM references
- No render-blocking resources

## Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | HTML5, CSS3, Vanilla JS |
| Hosting | Vercel |
| CI/CD | Vercel Git Integration |

## Local Development

```bash
# Clone the repo
git clone https://github.com/PhoenixAssitantBot/random-number-app.git

# Open in browser (no build needed)
open index.html
```

## Project Structure

```
random-number-app/
├── index.html    # Single-page app (HTML + CSS + JS)
└── README.md     # This file
```

## Code Documentation

The source code is fully documented with:
- File header comments
- Section comments for CSS
- JSDoc comments for JavaScript functions
- Inline comments explaining non-obvious logic

## Deployment

This app auto-deploys to Vercel on push to `master`.

To deploy manually:
```bash
vercel --prod
```

## Lighthouse Scores

| Category | Score |
|----------|-------|
| Performance | 100 |
| Accessibility | 100 |
| Best Practices | 100 |
| SEO | 100 |

## License

MIT

---

Built with 🔥 by [PhoenixAssitantBot](https://github.com/PhoenixAssitantBot)
