# Quota Reset Watch — public evidence and corrections

[Quota Reset Watch](https://quotaresetwatch.com/en/) is a free, independent archive of public quota reset announcements for Codex and Claude. Each record links to the original announcement and distinguishes a rollout announcement from confirmed completion.

This repository holds a small, reviewed dataset and a public place to suggest corrections. It contains no application template or website source code.

## Browse the archive

- [Codex public reset history](https://quotaresetwatch.com/en/products/codex/)
- [Claude public reset history](https://quotaresetwatch.com/en/products/claude/)
- [Primary-source directory](https://quotaresetwatch.com/en/sources/)
- [中文网站](https://quotaresetwatch.com/zh/)
- [RSS feed](https://quotaresetwatch.com/feed.xml)

## Interpret an announcement

- [Automatic vs. banked Codex resets](https://quotaresetwatch.com/en/guides/codex-automatic-vs-banked-resets/)
- [Claude usage windows vs. public resets](https://quotaresetwatch.com/en/guides/claude-usage-reset-vs-public-reset/)
- [Quota resets, bonus credits and limit increases](https://quotaresetwatch.com/en/guides/ai-quota-reset-vs-credits-and-limit-increases/)

## Dataset and evidence rules

See [data/events.json](data/events.json) for the initial two historical records. This is a curated sample, not an exhaustive history or a live feed. An older rollout announcement retains its evidence status; it does not mean the rollout is still happening today.

A public reset must identify a provider action affecting a publicly described audience. Personal five-hour or weekly refreshes, a higher limit, saved reset credits, and incident recovery are distinct concepts. An announcement is marked completed only when a primary source explicitly supports completion. Date-only sources stay date-only; precise timestamps use UTC.

Third-party reports can be leads, but a record needs the provider's announcement or an identifiable product team member's original public post. Product names identify the tools being discussed; this project is not affiliated with OpenAI or Anthropic.

## Corrections

[Open an issue](https://github.com/Normr0i33aW1vis144ingo/quota-reset-watch/issues/new/choose) with the record URL, original public source, and the proposed correction. Please keep account credentials, personal quota screenshots and private messages out of public issues.

Live collection and automated notifications are planned separately and are not active in this release. The site currently requires no account or alert subscription.
