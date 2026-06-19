# Privacy Review

## Files Inspected

- Top-level project tree.
- `README.md`
- `package.json`
- `docs/`
- `public/brand/`
- selected `src/components/` references from text search.
- deployment and environment-template references from sensitivity scan.

## Sensitive Categories Found

Potential sensitive categories appeared in the private project tree:

- environment files and environment templates;
- deployment and server-operation docs;
- tokens, secrets, and password placeholders;
- worker token references;
- legal/admin/court workflow references;
- medical, benefits, family, phone, address, and DOB field references;
- private receipts and protected route documentation;
- local app storage and build artifacts.

No values were copied into this public surface.

## Files Excluded

- `.env.local`
- `.env.example`
- `deploy/`
- `storage/`
- `src/`
- `desktop/`
- `scripts/`
- private receipts and screenshots
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
- No claim that a public product, download, pilot, price, or license is open.
- No claim about private facts, records, legal strategy, or outcomes.

## Image Safety

The included SVGs are abstract original placeholders. They contain no real
records, names, IDs, routes, addresses, screenshots, credentials, or case
details.

## Workflow Safety

Workflow diagrams are intentionally high-level. They show public/private review
movement without internal architecture, deployment details, or implementation
paths.

## Rating

READY AFTER FAITH REVIEW

