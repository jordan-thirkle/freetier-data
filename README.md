# FreeTier Data

Open-source data behind FreeTier — the By JTT directory of free SaaS tiers and generous plans for indie builders.

The current catalogue contains **37 tools across 9 categories**. This repository is the neutral data source; it intentionally does not contain affiliate/referral links.

> Free-tier limits and prices change often. Entries should be treated as catalogue data, not timeless guarantees. Verify changed claims against the provider's primary pricing/documentation before updating them, and keep the website's `lastVerified` metadata honest.

## Contribute

Know a tool with a useful free tier that's missing? Found an outdated limit? Submit a PR or open an issue.

### Steps

1. Fork this repo.
2. Edit `tools.json`.
3. Verify changed plan/price/limit claims against a primary provider source.
4. Open a PR and include the source used for verification in the PR description.

### Format

Each tool entry follows this structure:

```json
{"name":"Tool Name","desc":"Short description of the free offering.","free":"Free tier limit","url":"https://tool.com","color":"emerald"}
```

**Color values:** `emerald`, `violet`, `amber`, `blue`.

### Guidelines

- SaaS tools, dev tools, and platforms may be included when their free/near-free status is described accurately.
- Do not turn a time-limited trial into a "free tier" claim.
- Describe what is actually free, not marketing fluff.
- If a product is paid-only or pay-as-you-go, say so explicitly rather than forcing it into a free-tier label.
- Keep descriptions factual and concise.
- PRs adding affiliate or referral links will be rejected; this is the neutral directory.
- Do not advertise tools in the website README before they are actually present in `tools.json`.

## Data only

This repository contains raw neutral catalogue data. The FreeTier website overlays its own presentation, optional referral metadata and per-entry verification dates. This keeps the source community-readable while allowing the product layer to remain separate.

The intended restored product hostname is `https://freetier.byjtt.com`; do not use the removed `mvp-freetier.vercel.app` project as current-live evidence.

## License

MIT
