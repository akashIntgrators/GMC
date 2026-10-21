# Goldman’s Marshall’s — mobile proposal prototype

## Intent
A mobile landing page for visitors arriving from Meta/Google ads. Price and the basis of calculation appear first; company history is deferred. No automatic popups, forms or large opening banner hide the quote. Expandable categories reduce reading load while allowing nested specifications. A persistent mobile bar offers an inclusion jump and a real phone link; it does not submit data or send messages automatically.

## Source
Owner-supplied Dec general proposal.pdf (23 pages, 2025). Gold/black branding, logo and villa illustration extracted from page 1. Price: ₹2,765/sq. ft. + GST, page 5. Inclusions and allowances: pages 6–19. Timeline/conditions/exclusions: page 20. Contact: page 23. Imagery is labelled as illustration, not as a completed customer project.

## Publication decisions outstanding
- Current rate and GST treatment; no tax percentage invented.
- Proposal overview versus exclusions: terrace garden, healthcare area, vanity, courtyard and optional amenities. The prototype flags ambiguity instead of presenting these as unconditional inclusions.
- Approval assistance versus excluded government/connection charges.
- Claimed fixed price must be reconciled with allowances, extra work and ground conditions. No unconditional no-overrun guarantee reproduced.
- The terms state 12 months plus 3 months grace; both are disclosed.
- Confirm contact phone/email, corporate name and artwork rights before publishing.
- No fabricated testimonials, metrics, completed-project claims or performance guarantees.

## Interaction
Five horizontal offering tiles opening a native modal dialog, with nested detail accordions. On mobile the tiles swipe horizontally and the dialog is presented as a bottom sheet. Keyboard accessible summaries and visible focus. One category appears at a time in the modal; close button, Escape and backdrop dismissal are supported. Native dialog focus handling returns focus to the triggering tile. Area illustration uses total built-up slab area and excludes GST/extras. Invalid/empty/non-integer inputs show an error instead of an estimate. Example 2,000 sq. ft. × ₹2,765 = ₹55,30,000.

## Hosting
Standalone buildless site: index.html, style.css, app.js and assets/. Upload to a separate GitHub Pages site when content is approved. No domain selected, no CNAME supplied, no deployment made. Keep this prototype separate from WhatsApp with Bigin. Do not upload the original client proposal without reviewing its contents and permissions.

## Content iteration
First approve mobile price block, expandable hierarchy, allowance/exclusion language and contact bar. Then fill remaining detailed specifications, process content and verified project photography. Review on a real phone before ad traffic is enabled.

## Latest interaction revision
Compact icon-and-label tiles replace the larger cards. Selecting a category reveals an inline panel below the horizontal row; no popup, overlay or bottom sheet. Clicking the selected tile or collapse control hides it. Selecting another category switches the panel content. Descriptions and legends removed from the selector to reduce visual copy. Nested specifications are retained inside the panel. JavaScript syntax verified; latest layout needs visual review.

## Lean opening revision — 21 October 2026
Removed large villa hero and repeated promotional text. Combined the price, area/GST qualification and offering selector into one opening section. All specifications remain behind click-to-reveal tiles. Contact design remains provisional.
