# FreeTier Data

Open-source data behind [FreeTier](https://mvp-freetier.vercel.app) — a directory of free SaaS tiers and generous plans for indie builders.

## Contribute

Know a tool with a great free tier that's missing? Found an outdated limit? Submit a PR or open an issue.

### Steps

1. Fork this repo
2. Edit `tools.json`
3. Open a PR

### Format

Each tool entry follows this structure:

```json
{"name":"Tool Name","desc":"Short description of the free offering.","free":"Free tier limit","url":"https://tool.com","color":"emerald"}
```

**Color values:** `emerald`, `violet`, `amber`, `blue`

### Guidelines

- Only SaaS tools, dev tools, and platforms with a real free tier
- The free tier must be useful for building a real product (not just a trial)
- Describe what's actually free, not marketing fluff
- Keep descriptions factual and concise
- PRs adding affiliate or referral links will be rejected (this is a neutral directory)

## Data only

This repo contains only raw data. The FreeTier website overlays its own affiliate links and presentation. This keeps the data source neutral and community-owned while allowing the site to monetize independently.

## License

MIT
