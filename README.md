# Daily OS

**Website: https://alexli-77.github.io/daily-os/** · [English](https://alexli-77.github.io/daily-os/en/)

Daily OS is a local-first daily planning and review agent for macOS. Every
morning it builds a time-blocked plan from your Feishu calendar and tasks,
GitHub, Linear and notes; every evening it reviews what actually happened.

This repository is the source of that website, served by GitHub Pages from the
repository root. It contains no product code.

## Source code

| Repository | What | License |
| --- | --- | --- |
| [daily-os-backend](https://github.com/alexli-77/daily-os-backend) | The service: scheduler, data sources, Feishu interaction, local console | AGPL-3.0 |
| [daily-os-macos](https://github.com/alexli-77/daily-os-macos) | Native macOS client and shared design system | MIT |

## Editing the site

Plain HTML and CSS, no build step.

- `index.html`: Chinese page (default)
- `en/index.html`: English page; keep it in step with the Chinese one
- `assets/`: stylesheet, screenshots (from `daily-os-macos/docs`), Open Graph image
- `sitemap.xml`, `llms.txt`: update `lastmod` and facts when the pages change

Preview locally:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000/.
