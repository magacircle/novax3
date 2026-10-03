# NovaX V42 Approved Restore Point — 2026-10-02

This repository is based on:
- `NovaX_V42_Surgical_Update.zip` (functional V42 source)
- `NovaX_Hub_Prototype_V2.zip` (navy-blue visual reference)

## Landing-page visual source
The landing page now uses the locked portrait and landscape reference images as the exact visual plates. This intentionally avoids another generated/recomposed background and preserves the approved logo, typography, colors, ring, hikers, sun, and composition exactly as locked.

- `assets/NovaX_LOCKED_PORTRAIT_REFERENCE.png`
- `assets/NovaX_LOCKED_LANDSCAPE_REFERENCE.png`

The CTA remains a real HTML link to `quiz.html` via a transparent hit area over the approved CTA in each locked composition. Semantic hidden text remains in the link for accessibility.

## Quiz visual update
`quiz.html` retains its existing functionality and logic while its retired black/gold treatment has been migrated to the Hub V2 navy / cyan / blue / violet visual language.

## Asset cleanup
Removed from `assets/` because they were retired/obsolete and no active production page references them:
- `NovaX_LANDING_RING_X_COLORS.png`
- `NovaX_APPROVED_RING_X_COLORS.png`
- `landing-background-portrait.png`

Retained assets are still referenced by active pages or required by existing functionality (Hub, Auth, Quiz, legal pages, Builder Card/share logic).

## Restore identity
Repository: `NovaX_V42_APPROVED_RESTORE_2026-10-02`
Source restore point: `NovaX_V42_Surgical_Update.zip`
Visual reference: `NovaX_Hub_Prototype_V2.zip`
