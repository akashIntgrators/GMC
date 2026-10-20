# Enquiries and ad launch setup

## Implemented
Persistent WhatsApp/callback enquiry links; short form; explicit WhatsApp handoff with no false submitted state; six offering tiles including price explanation; next-step process; business contact footer; privacy notice; top-of-page load even from old #projects URL; local map/media, WebP asset and lazy loading; optional consent-controlled tag configuration.

WhatsApp destination confirmed by owner: 917676246810. The owner asked to connect via WhatsApp for more information. No CRM or form submission endpoint is configured. The visitor must send the prepared message. Browser preparation tests sent no messages.

## Measurement
In site-config.js, add approved ga4Id, googleAdsId and metaPixelId. Tracking IDs are not API secrets. Empty defaults make no tag requests. Tags load only after opt-in; preference can be changed from footer. Do not add form PII as analytics parameters. Validate consent, network requests and events in actual Google/Meta test tools after configuring IDs.

Available events: enquiry_open, whatsapp_click, enquiry_prepared, whatsapp_enquiry_opened. These are interaction signals, NOT submitted leads or completed conversations. No Lead conversion is fired on a WhatsApp click. googleLeadLabel is reserved and intentionally unused until a confirmed lead-completion source exists.

URL campaign parameters utm_source, utm_medium, utm_campaign, utm_content, utm_term, gclid, fbclid stay in memory and may be included in the visitor's editable prepared WhatsApp message. Do not put personal data in campaign values. For a true attribution pipeline, store enquiry source in the CRM and implement authenticated receipt/qualification before sending completed-lead events. Server-side Meta Conversions API requires a backend; no access tokens should be put on GitHub Pages.

## Still needed before paid traffic
- Confirm current rate; displayed rate remains based on owner-supplied 2025 proposal.
- Supply actual project sites, approved project media, genuine customer reviews and permissions. No testimonials or portfolio completion claims invented.
- Business approval of corporate/contact details, inclusion/exclusion schedule, privacy notice and actual enquiry retention practices.
- Supply analytics account IDs and verify tags in real browsers including Instagram/Facebook in-app browsers. No performance score or device test claimed by source changes alone.
- Create separate campaign-specific landing copy only from approved offers. Current page is a construction landing page; do not send interior-only ads to a construction price as if it were an interiors quote.
- Validate lead handling: message received by team, response process, source captured, qualified lead definitions. Do not claim that local form preparation is lead delivery.
- Test real mobile speed, gallery load/playback, enquiry buttons and privacy settings before launch.

## Deployment
Upload updated HTML/CSS/JS, privacy.html, site-config.js and assets to existing GMC repository. Keep existing CNAME. This local package does not overwrite or modify the remote repository. Google/Meta setup and genuine portfolio data remain pending.

## Map licence
Retain visible attribution to OpenStreetMap contributors and the Commons author/source plus CC BY-SA 2.0 link. Attribution shortened in UI; source/date/approximate-coordinate limits documented in PROJECTS-SETUP.md. WebP rendition is a format conversion of the same map. No licence ownership claim is made by the business.
