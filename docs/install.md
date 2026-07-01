# Install Map

Daily OS is currently an alpha made of several local-first projects.

## Required

Install the main app first:

```bash
git clone https://github.com/alexli-77/daily-os-feishu.git
cd daily-os-feishu
npm install
npm run setup
npm run start
```

For background mode:

```bash
npm run service:install
```

## Optional

Install `life-review-os` when you want deep weekly / biweekly / quarterly review and Feishu Weekly write-back.

`calendar-planning-os` is planned and should remain optional.

## Boundary

This is not yet a signed macOS app or DMG.

The current alpha uses:

- local Node.js
- local config files
- local Codex or Claude CLI login
- Feishu credentials configured by the user
- optional local vault paths

Do not commit:

- `.env`
- `config.yaml`
- Feishu tokens
- Codex or Claude credentials
- personal vault files
