# Kanban (Mr Helper)

## Backlog
- [ ] Email monitoring for mrhelperbot@icloud.com (Himalaya + app-specific password) — decide A(draft) vs B(auto-send)
- [ ] Daily AI Agent Use-Case Scout (Modbot) — review outputs + decide YES/NO daily
- [ ] Evaluate skill-creator v5 (shared in Slack #silicon-saloon by U0ABPQQEQLX) — enhanced skill creation with security scans + library checks
- [ ] Fix memory search (embeddings provider broken after OpenAI API key removal — needs alternative)
- [ ] OpenClaw update to 2026.2.9
- [ ] Clean up stale LaunchAgent plist (ai.openclaw.gateway — doctor flagged)

## In progress
- [ ] OpenClaw comprehensive audit (Opus sub-agent - deep 4-6h analysis)
- [ ] Spending deep dive analysis (Opus sub-agent - processing spending + loan data)

## System / Reliability
- [ ] Cross-context messaging (Slack↔Telegram) — enable `tools.message.crossContext.allowAcrossProviders` + add permission/confirmation guardrails; validate via `openclaw doctor`

## Waiting on Mark
- [x] ~~Run `openclaw gateway restart`~~ (done 2026-02-10)

## Done
- [x] OpenClaw self-audit initial (14-section analysis) - now enhanced with Opus deep dive (2026-02-10)
- [x] Cron monitor hardening completed (exec allowlist verified, failure alerts tested) (2026-02-10)
- [x] Logging redaction patterns enhanced (added GitHub, AWS, JWT, Google tokens) (2026-02-10)
- [x] Security audit completed + credentials directory permissions fixed (chmod 700) (2026-02-10)
- [x] Podcast recommendations completed (30+ shows across business, tech, finance, property) (2026-02-10)
- [x] PropTrack scraping system implemented (automated property value tracking with Puppeteer) (2026-02-10)
- [x] LTR capital reallocation analysis completed - hybrid strategy recommended (2026-02-10)
- [x] Dashboard auto-sync fully operational (kanban.md → GitHub Pages every 10 min, zero manual work) (2026-02-10)
- [x] LTR investment brief completed with Dec 2025 quarterly data (2026-02-10)
- [x] Europe trip — flight shortlist + cost bands (closed per Mark)
- [x] Financial snapshot + analysis (screenshots + PDFs) delivered (2026-02-06)
- [x] Slack wiring prep in OpenClaw (config added; awaiting xoxb/xapp tokens)
- [x] Moltbot use cases scan (initial)
- [x] Telegram setup + WhatsApp disabled
- [x] GitHub Pages kanban dashboard — live at https://mgs788-ops.github.io/clawd-dashboard/

## Drafts created (awaiting input)
- [~] PropTrack scraper system: scripts/property-tracker.mjs + scripts/proptrack-scraper-setup.md
- [~] Podcast recommendations (30+ shows): reports/2026-02-10_podcast-recommendations-for-mark.md
- [~] LTR capital reallocation options: reports/2026-02-10_LTR-capital-reallocation-options.md
- [~] LTR investment brief draft: reports/2026-02-07_LTR-investment-brief_draft.md
- [~] Spending deep dive plan: reports/2026-02-07_Spending-behaviour-deep-dive_plan.md

## Dropped (per Mark)
- [x] Notes workflow (Apple Notes Kanban/templates)
