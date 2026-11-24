# Adora Marketing Website — Internal Revision 03

INTERNAL — PENDING BOTH PARTNERS' APPROVAL

## Changes
- Added a dedicated `contact.html` page using the existing Adora espresso, sand, and taupe visual system.
- Updated the main navigation Contact item and Consultation CTA across all site pages to open `contact.html`.
- Added a Portfolio dropdown to the main navigation on all site pages, with direct links to:
  - `dash.html` — DASH
  - `line.html` — Line Construction
  - `marianos.html` — Mariano's Painting
- Added responsive dropdown behavior for mobile and keyboard-accessible button state (`aria-expanded`).

## Deliberate limitation
The supplied website source did not contain an approved contact email, phone number, CRM destination, or form endpoint. The new Contact page therefore does not invent contact details or pretend a form submission is connected. It is a styled contact landing page; the approved inquiry mechanism still needs to be supplied and integrated before public release.

## QA
- Local HTML references: PASS (all local href/src targets resolve in this package)
- Navigation coverage: PASS (all nine HTML pages include Contact and Portfolio dropdown links)
- JavaScript syntax: verify with `node --check assets/js/main.js`
- Browser/device testing: NOT VERIFIED
- Form delivery/integration: NOT VERIFIED / NOT CONFIGURED
- Both partners' exact-version approval: PENDING
- Production deployment: NOT AUTHORIZED
