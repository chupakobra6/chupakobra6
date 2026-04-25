# Igor / chupakobra6

Backend engineer focused on Go services, Telegram products, automation, and developer tooling.

Previously at Flant. My commercial backend work is primarily Go; my public GitHub shows the surrounding product instincts: workers, stateful bots, CLI tools, PDF/media workflows, deployment hygiene, and end-to-end testing.

I am useful when a system has to keep working after the demo: background jobs, database state, operational commands, observable failure modes, and user flows that are simple enough to survive real use.

Open to backend, platform, automation, Telegram, and developer tooling work.

## What I bring

- Go backend services with PostgreSQL, Docker, migrations, workers, and explicit runtime contracts.
- Telegram bot products with stateful UX, background pipelines, and real-user E2E coverage.
- Python tooling for document, media, browser, and workflow automation.
- Practical ops habits: setup scripts, backup/restore paths, diagnostics, local reproducibility, and small deployable changes.
- Product-minded engineering: I care about the path a user actually takes, not only the internal architecture.

## Selected work

| Project | Why it matters |
| --- | --- |
| [shelfy](https://github.com/chupakobra6/shelfy) | Go Telegram product for expiration tracking with a pinned dashboard, background parsing pipelines, PostgreSQL, Docker, and deterministic dev controls. |
| [telegram-bot-e2e-test-tool](https://github.com/chupakobra6/telegram-bot-e2e-test-tool) | Go MTProto test runner that drives a bot as a real Telegram user, records chat state, clicks buttons, and produces scenario artifacts. |
| [trackmate](https://github.com/chupakobra6/trackmate) | Telegram accountability bot with a separate worker, PostgreSQL state, Alembic migrations, backups, restore commands, and Docker operations. |
| [pf2e-pdf-tools](https://github.com/chupakobra6/pf2e-pdf-tools) | PDF form toolkit and local web editor that keeps widget state and AcroForm fields synchronized across viewers. |
| [video_downloader](https://github.com/chupakobra6/video_downloader) | Authenticated conference video downloader using Chrome cookies, `yt-dlp`, Playwright network capture, and batch workflows. |
| [vagvin](https://github.com/chupakobra6/vagvin) | Django product-shaped app for VIN checks, payments, user accounts, moderation, and Prometheus/Grafana monitoring. |

## How I build

- Start from the contract: what the user, operator, or downstream tool can rely on.
- Keep interfaces explicit and changes small enough to review.
- Treat deployment, backup, restore, and diagnostics as part of the product.
- Prefer boring, repeatable local workflows over clever one-off automation.
- Test behavior that protects real users, protocols, and tooling contracts.

## More public work

- [video2note](https://github.com/chupakobra6/video2note): `whisper.cpp`-based CLI for turning audio and video into transcripts and notes.
- [telegram_mirror](https://github.com/chupakobra6/telegram_mirror): Telegram mirroring bot with database-backed configuration and rendered message images.
- [redrawing_master](https://github.com/chupakobra6/redrawing_master): PyQt5 overlay tool for cursor projection and tracing workflows.

## Contact

- Telegram: [@Pheik15](https://t.me/Pheik15)
