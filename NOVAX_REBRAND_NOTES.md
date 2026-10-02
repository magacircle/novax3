# NovaX™ V41 Rebrand Notes

This repository is a rebranded copy of the MagaCircle V41 Google/Apple Auth Integrated prototype.

## Rebrand applied

- Brand references changed from MagaCircle™ to NovaX™ throughout active product, legal, auth, README, and changelog text.
- Canonical logo asset added as `assets/NovaX_logo_transparent.png` using the Founder-supplied transparent NovaX™ logo.
- HTML logo references updated to the NovaX™ logo asset.
- Auth configuration namespace changed from `MAGA_AUTH_CONFIG` to `NOVAX_AUTH_CONFIG`.
- NovaX state namespace is `novax_builder_v4`.
- Invite attribution namespace is `novax_invite_ref` / `novax_invite_attribution`.
- Auth user storage namespace is `novax_auth_user`.
- Builder-card download filename changed to `NovaX-[Archetype]-Builder-Profile.png`.

## Founder Credit terminology

The reward terminology has been standardized to:

**NovaX™ Founder Credit**

The previous `Founding Membership Credit` wording has been replaced in the prototype reward rules and Founder milestone UI.

## Legacy migration compatibility

Old MagaCircle browser keys remain referenced only as migration/fallback sources where needed:

- `magacircle_builder_v4`
- `magacircle_builder_v3`
- `mc_auth_user`
- `mc_invite_ref`

These are not the active NovaX™ namespaces.

## Asset note

The source V41 archive contains references to landing-page assets that were not present in that archive. This rebrand does not invent replacement artwork for those missing assets. The canonical NovaX™ logo is included and wired into the site. The landing-page mockup/background assets should be supplied/locked separately before production deployment.

## Source baseline

Source archive:
`MagaCircle_V41_Google_Apple_Auth_Integrated.zip`

This rebrand does not intentionally redesign the existing product flow or alter its scoring/reward mechanics beyond the requested terminology/brand namespace changes.
