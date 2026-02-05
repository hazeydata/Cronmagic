# ⏰ CronMagic

**Human-readable cron expressions. Never forget the syntax again.**

Convert plain English to cron expressions and vice versa. The simplest cron builder on the internet.

🔗 **Live:** [cronmagic.hazeydata.ai](https://hazeydata.github.io/cronmagic/) (or configure custom domain)

## Features

- **English → Cron**: Type "every Monday at 9am" → get `0 9 * * 1`
- **Cron → English**: Paste `*/5 * * * *` → see "Every 5 minutes"
- **Next runs preview**: See when your cron will fire next
- **Quick picks**: Common patterns one click away
- **Zero dependencies**: Pure HTML/CSS/JS, works offline

## Examples

| English | Cron |
|---------|------|
| every minute | `* * * * *` |
| every 5 minutes | `*/5 * * * *` |
| daily at midnight | `0 0 * * *` |
| every Monday at 9am | `0 9 * * 1` |
| weekdays at 8am | `0 8 * * 1-5` |
| first of every month | `0 0 1 * *` |

## Development

```bash
# Clone
git clone https://github.com/hazeydata/cronmagic.git
cd cronmagic

# Serve locally (any static server works)
python -m http.server 8000
# or
npx serve .
```

Open http://localhost:8000

## Deploy

GitHub Pages, Netlify, Vercel, Cloudflare Pages — any static host works.

This repo is configured for GitHub Pages from the root directory.

## Support

If CronMagic saved you time, [buy me a coffee](https://buymeacoffee.com/hazeydata) ☕

## License

MIT © [Hazeydata](https://hazeydata.ai)

---

Built with ☕ for developers who forget cron syntax (all of us)
