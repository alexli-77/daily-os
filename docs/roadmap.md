# Roadmap

This roadmap tracks the Daily OS ecosystem across repositories.

## Alpha

Goal: prove that one person can run Daily OS locally and use it every day.

Done:

- Feishu-first daily plan and review
- Dashboard setup and config
- Local decision policy editing
- Daily todo inbox
- Mac companion prototype
- Weekly review bridge to `life-review-os`
- Feishu Weekly write-back confirmation flow
- `daily-os-feishu v0.1.0-alpha.2` prerelease

## External Mac Validation

Goal: install and run on another Mac without relying on hidden local state.

Checklist:

- Fresh clone install
- `npm install`
- `npm run setup`
- Dashboard config
- Codex or Claude CLI login
- Feishu credentials
- `npm run service:install`
- Feishu commands work
- Daily plan reflects user policy and daily todo inbox
- Weekly deep review can call `life-review-os`

## Calendar Planning

Goal: turn weekly and daily plans into calendar drafts without taking control away from the user.

First version:

- `calendar-planning-os draft-week`
- `calendar-planning-os draft-day`
- Calendar policy file
- Existing calendar read
- Conflict detection
- Draft output only

Later:

- Confirmed write-back
- Undo / revert
- Daily rescheduling
- Review loop for planned vs actual time

## Beta

Goal: make Daily OS understandable and installable by a non-developer early user.

Likely work:

- Better first-run onboarding
- Clear install package boundary
- Message style preview cards
- More reliable multi-provider LLM output contracts
- Better failure recovery and logs
- Optional calendar planning engine
