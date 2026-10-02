# NovaX™ Hub Prototype V2

## Purpose

V2 corrects the primary issue in Prototype V1: V1 preserved almost all V41 visual assets and only introduced the new Hub. V2 applies the **Signature #5 visual direction across the prototype journey** while preserving the existing functional Quiz, scoring, invite, reward, and localStorage behavior.

## Source of truth

- Functional baseline: `NovaX_V41_Auth_Integrated` from V41.
- Visual reference: Founder-supplied **5 Visual Identity Options** board, specifically **#5 SIGNATURE**.
- Signature #5 is a current working visual direction for prototype evaluation, not a permanent final brand lock.

## V2 changes

### Production-style Signature wordmark assets
Added:
- `assets/NovaX_Signature_Logo_Dark.png`
- `assets/NovaX_Signature_Logo_Light.png`

These are cleaned transparent PNG working assets derived directly from the Founder-supplied Signature #5 reference, rather than AI-redrawn logo variants.

The prototype now uses these assets for the visible NovaX branding on Landing, Identity/Auth, Quiz/Builder Profile, Builder Card, and Hub.

### Shared Signature visual system
Added:
- `assets/novax-signature.css`

The visual system uses the Signature direction:
- dark cinematic navy foundation
- restrained electric blue / violet accents
- premium glass-like panels
- confident typography
- thin technical borders
- restrained gradients
- clear hierarchy
- mobile-first responsive behavior

### Landing
The existing approved functional copy is preserved, including:
- `Building the Parallel Economy`
- `What would you do with $50K?`
- `Take the quiz to see if you qualify for NovaX™`
- `LET’S BEGIN`
- `The first circle is forming.`

The old V41 landing artwork is no longer the visible foreground/background composition of the prototype. The new page uses the Signature visual language while preserving the functional CTA and legal navigation.

### Identity/Auth
The existing auth behavior is preserved, but the visual presentation now uses the Signature system and production-style logo.

### Builder Quiz / Builder Profile
The existing quiz questions and deterministic scoring behavior are preserved.

The presentation now uses the Signature system, including:
- new logo
- new panel treatment
- new controls
- new progress treatment
- new Builder Profile styling
- new Builder Card logo asset

No quiz questions or scoring rules were intentionally changed.

### NovaX™ Hub
Hub remains the main new experience introduced in V1, but now uses the production-style Signature logo rather than the reference-board crop.

Theme behavior remains:
- `System` is hidden from Builder-facing controls.
- Initial theme follows OS/browser `prefers-color-scheme`.
- Visible choices are only `Light` and `Dark`.
- Manual selection persists in `novax_theme` and overrides system preference.

## Intentionally retained

The repository still contains inherited V41 assets that are required by the baseline prototype, social metadata, legal pages, Builder Card fallback behavior, or future compatibility. Their presence does not mean they are the active visual identity of the V2 pages.

The following obsolete Signature reference crops were removed:
- `signature5-dark-reference.png`
- `signature5-light-reference.png`

## Still prototype-only

Not production infrastructure:
- Google/Apple production authentication
- PostgreSQL persistence
- real GrowSurf settlement
- Mautic synchronization
- Relaticle synchronization
- Stripe/payment processing
- production First Circle/community
- production Circle matching
- Builder Connection production workflow
- Vanguard application workflow
- funding infrastructure
- AI Workforce runtime

## Validation

V2 was checked for:
- required HTML pages remaining present
- all referenced local assets resolving
- no remaining references to the removed Signature reference crops
- new Signature assets present
- existing V41 functional JavaScript retained

Browser screenshot automation was attempted in the sandbox, but the environment blocks local/file browser navigation; therefore visual browser rendering must still be manually checked in a normal browser after download.
