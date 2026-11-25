# Settlemark landing page

A responsive, single-file landing page built from the supplied Website Requirements Document.

## Run locally

Open `index.html` in a modern browser, or serve the repository root with any static web server.

## Included

- Institutional ledger-inspired visual system and responsive navigation
- Interactive lump-sum exact-match / short-pay preview and controller approval state
- Reactive trapped-cash calculator
- Four-module workflow, safeguards, deployment timeline, pricing and FAQ
- Accessible sample audit and CSV export guide dialogs
- Client-side audit form validation and email-draft handoff

## Before production launch

This repository currently contains a static front end only. The audit form opens a prefilled email draft; it does **not** transmit or store submissions. Connect a secure intake backend or CRM, encrypted file-upload service, and real booking calendar before accepting prospect data. Do not ask prospects to send financial CSVs through ordinary email.

Replace the founder name and LinkedIn placeholders in the footer. Verify all service, security, retention, pricing, guarantee and competitor-comparison claims before publishing. The sample report and matcher data are illustrative.

## Deployment

The site has no build step or runtime dependencies. It can be deployed to GitHub Pages or any static hosting provider by publishing the repository root.
