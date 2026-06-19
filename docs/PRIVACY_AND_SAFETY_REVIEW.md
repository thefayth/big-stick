# Privacy And Safety Review

## Files Inspected

- Top-level project tree.
- `README.md`
- `package.json`
- `docs/`
- `public/brand/`
- selected `src/components/` references from text search.
- deployment and environment-template references from sensitivity scan.

## Files Created

All created files are under `_public_surface/big-stick/`.

## Sensitive Categories Found

Potential sensitive categories appeared in the private project tree:

- environment files and environment templates;
- deployment and server-operation docs;
- tokens/secrets/password placeholders;
- public support email placeholders;
- worker tokens;
- legal/admin/court workflow references;
- medical, benefits, family, phone, address, and DOB field references;
- private receipts and protected route documentation;
- local app storage and build artifacts.

Values were not displayed or copied into the public surface.

## Sensitive Files Excluded

- `.env.local`
- `.env.example`
- `deploy/`
- `storage/`
- `src/`
- `desktop/`
- `scripts/`
- `docs/local-full-app-receipt-2026-06-17.md`
- `docs/brand/auntie-ai/**/receipts/`
- `.next/`
- `.desktop-app/`
- `dist-desktop/`
- `node_modules/`

## Public-Safe Claims Used

- Big Stick is a local command center.
- Fightback, Unburied, Listen Up, AI Console, Exports, and Settings are tool
  areas inside Big Stick.
- Fightback is public-facing approved/redacted material.
- Unburied and Listen Up are private/protected areas.
- The project is local-first and review-first.

## Claims Avoided

- No claim that Big Stick is publicly available.
- No claim that Big Stick gives legal advice.
- No claim that a public repo or WordPress page exists.
- No claim that pilots, licensing, downloads, pricing, or services are open.
- No claim about private facts, records, legal strategy, or outcomes.

## Images Safe / Not Safe

Safe: abstract command-board visuals, public/private boundary diagrams, redacted
record metaphors, icon concepts.

Not safe: real screenshots, raw records, names, case details, addresses, phone
numbers, medical/legal/benefits documents, private receipts, or unpublished
strategy material.

## WordPress Safe / Not Safe

Safe after Faith review: project-story draft in `wordpress/`.

Not safe: product access language, pricing, downloads, raw evidence, private
screenshots, or operational details.

## GitHub Safe / Not Safe

Safe after Faith review: this staged public surface only.

Not safe: the private project root or any source/data/build/runtime folders.

## Public Surface Readiness

READY AFTER FAITH REVIEW

