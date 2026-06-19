# Receipt: Big Stick Public Surface Prep

## Date/Time

2026-06-18, America/Los_Angeles.

## Working Directory

Private Big Stick workspace. The private workspace path is intentionally not
published as project documentation.

## Run Mode

PUBLIC_SURFACE_CREATED_AND_PUSHED.

## Summary

Created a protected public-facing staging surface for Big Stick under
`_public_surface/big-stick/`.

Created and populated the public GitHub repository:

`https://github.com/thefayth/big-stick`

No WordPress page was published. No private app source, private data,
credentials, legal strategy, operational workflows, or private screenshots were
copied into the public surface.

## What I Inspected

- Current working directory.
- Git status and remote state.
- Top-level project tree.
- README and package metadata.
- Existing docs and public brand assets.
- Text references to Big Stick, Fightback, Unburied, Listen Up, AI Console,
  protected dashboard routes, public pages, and receipts.
- Sensitive-term scan across the private project tree, excluding heavy build
  folders where practical.

## What I Created Or Changed

- `README.md`
- `LICENSE.md`
- `NOTICE.md`
- `SECURITY.md`
- `TRADEMARKS.md`
- `CONTRIBUTING.md`
- `docs/PROJECT_BRIEF.md`
- `docs/PUBLIC_PRIVATE_BOUNDARY.md`
- `docs/COMMERCIAL_USE_POLICY.md`
- `docs/HOW_TO_ENGAGE.md`
- `docs/STATUS.md`
- `docs/FAQ.md`
- `docs/ROADMAP.md`
- `docs/IMAGE_BRIEF.md`
- `docs/WORDPRESS_PAGE_DRAFT.md`
- `docs/LAUNCH_CHECKLIST.md`
- `docs/PRIVACY_AND_SAFETY_REVIEW.md`
- `assets/README.md`
- image prompt files under `assets/image-prompts/`
- WordPress draft files under `wordpress/`
- this receipt.

## Safety Check Results

- Initial PREPARE_ONLY staged public surface contained 26 files.
- Secret-shaped value scan on `_public_surface/big-stick/` found no matches.
- Source/env/build/runtime file scan found no staged source code, `.env`,
  `storage`, `deploy`, `scripts`, `desktop`, `.next`, `.desktop-app`,
  `dist-desktop`, or `node_modules` files.
- Updated GitHub-ready surface contains 40 files.
- GitHub repository created: `thefayth/big-stick`.
- Initial commit pushed: `fc20b78` (`Create protected public project surface`).
- Repository topics set: `public-record`, `evidence-boundaries`, `local-first`,
  `archive-workflows`, `redaction`, `operator-tools`, `faith-cheltenham`.
- Issues and wiki disabled.

## What I Intentionally Did Not Touch

- No WordPress publishing or staging write.
- No deployment, DNS, webhook, Stripe, database, server, or production config.
- No source code export.
- No private storage export.
- No image generation from private screenshots.

## What Must Stay Private

Source code, app data, storage, raw records, transcripts, archive material,
legal/admin/medical/family details, private receipts, prompts, workflows,
credentials, deployment details, screenshots, customer/project records, and
strategy memos.

## Public Repo Recommendation

Created: `thefayth/big-stick`

URL: `https://github.com/thefayth/big-stick`

Only the contents of `_public_surface/big-stick/` were pushed. The private app
root was not pushed.

## WordPress Page Recommendation

Recommended after Faith review as a public project story page at:

`/projects/big-stick/`

Do not publish until Faith approves final copy and visuals.

## Image Recommendation

Use original abstract visuals from the prompt pack. Do not use private
screenshots or real records.

## Risk Notes

Sensitivity: high to extreme because the private app includes legal/admin,
evidence, archive, transcript, medical/benefits/family-adjacent, worker,
credential, and deployment contexts.

Public surface readiness: READY AFTER FAITH REVIEW.

## Open Questions For Faith

- Should the public page slug be `/projects/big-stick/` or `/big-stick/`?
- Should the public story name Fightback, Unburied, and Listen Up explicitly?
- Should visuals be generated now from the image prompts?

## Next Exact Review Steps

Review the public repository:

- `https://github.com/thefayth/big-stick`
- Confirm the README, diagrams, ownership terms, and WordPress draft copy.
- Decide whether to publish the WordPress page draft.

Future repo work should be review/update only unless Faith explicitly approves a
new publishing or production action.
