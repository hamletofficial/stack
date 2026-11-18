# Hamlet Support Centre

The Support Centre is the help and product-documentation home for **hamlet**, an integrated commercial and residential property workspace (IWMS) developed for property professionals and organisations. It explains the platform’s property, portfolio, deal and organisation workflows, its supporting member tools, and how to use each area safely. Hamlet’s direction is **less fragmentation, more connected deals**: bringing property information, transaction coordination and professional collaboration into a more coherent workspace.

## Product direction and current capabilities

Hamlet has developed beyond a standalone commercial property CRM into an IWMS-oriented workspace spanning commercial and residential property workflows, individual member workspaces and organisation-level collaboration. The precise controls available to a user depend on account status, verification, subscription entitlements and deployment configuration.

The current product surface includes:

- **Commercial property workspace:** live commercial listings, member-specific property portfolios, property resources and sustainability information.
- **Residential property workflows:** dedicated residential property records and portfolio/publishing controls, separate from commercial listings.
- **Deal management:** a Kanban-style transaction pipeline covering LOI Issued, Due Diligence, Under Contract and Closed, with critical-path dates and follow-up prompts where enabled.
- **Member tools:** public member profiles and directory, professional portfolios, community feed and related communication/notification features where available.
- **Broker intelligence:** Broker Rankings, dashboards and reporting designed to help members understand activity and recorded deal flow.
- **AI-assisted workflows:** Deal Copilot and Listings Assistant, dependent on enabled access, authentication, service availability and the applicable model gateway. AI-generated material must be reviewed before use.
- **Organisation workspaces:** a separate organisation identity and workspace model, including organisation profiles, membership requests and review, organisation-level administration and verification-related workflows. Organisation tenancy uses the canonical `{slug}.orgs.hamlet-ai.co.uk` pattern. The creator’s personal account remains distinct from the organisation identity.
- **Bookings:** the Support Centre and product navigation may link to Hamlet’s Timify booking page for scheduled assistance or demonstrations.

Hamlet’s sustainability focus includes property information such as Passivhaus and EnerPHit. Certification and performance claims should be supported by appropriate evidence; a submitted claim is not automatically independently verified by Hamlet.

These descriptions explain the product direction and documented workflows, not a guarantee that every function is enabled for every account or currently available in every deployment.

## Current product and release information

Hamlet's web workspace and its Windows desktop installer are versioned and released separately. Do not infer the desktop installer version from the Support Centre's own `package.json` version.

- **Previously confirmed stable desktop label:** `v1.04.02` (as last confirmed in the project notes; check the official downloads page for any newer release).
- **Web application:** continuously updated independently of the Windows desktop installer.
- **Windows installer:** use the filename and version currently published on the official downloads page; do not rely on a hard-coded filename in this README.
- **Release source:** [Hamlet releases and downloads](https://www.hamlet-ai.co.uk/download.html)
- **Official product website:** [hamlet-ai.co.uk](https://www.hamlet-ai.co.uk/)
- **Support website:** [support.hamlet-ai.co.uk](https://support.hamlet-ai.co.uk/)

Check the official downloads page for the latest release, current file size and published SHA-256 checksum before installing. Never rely on a filename or version copied into old support content as proof that an installer is current.

## Start here

- **[Support home](https://support.hamlet-ai.co.uk/)** — search help topics, FAQs and troubleshooting guidance.
- **[Product tour](https://support.hamlet-ai.co.uk/docs/product-tour.html)** — understand the connected property and deal workflow, and the role of the main workspace areas.
- **[Bookings](https://reserve.timify.com/60996e0106234611834f3f23)** — use the published Timify booking page where a scheduled session is appropriate.
- **[Downloads and installation](https://www.hamlet-ai.co.uk/download.html)** — obtain the official Windows installer and verify its checksum.

## What Hamlet covers

Guides should reflect the features actually available to the account and current deployment. Hamlet’s integrated workspace encompasses:

- Commercial property listings, member-specific portfolios, property resources and sustainability information.
- Residential property records and dedicated portfolio/publishing workflows.
- Deal pipeline management across LOI Issued, Due Diligence, Under Contract and Closed, including critical-path milestones and follow-up.
- Organisation workspaces with a distinct organisation identity, organisation profiles, membership requests, administration and verification-related processes.
- Member profiles, public directory, professional identity and the community feed.
- Broker Rankings, workspace dashboards and platform reporting.
- AI-assisted workflows, including Deal Copilot and Listings Assistant, subject to authentication, model gateway availability and account permissions.
- Bookings through the published Timify booking route, where applicable.
- Sustainability-related property information, including Passivhaus and EnerPHit claims that must be checked against appropriate source evidence.

The Support Centre must not promise that every feature is available to every account, that AI output is guaranteed to be correct, or that user-submitted property claims are independently verified by Hamlet.

## Privacy and account safety

Public search and portfolio guidance must distinguish public pages from authenticated member areas. Do not document or expose private member records, workspace information, search analytics or administrative functionality in public-facing examples. A page requiring Firebase authentication must not be represented as public merely because its URL is known.

When contacting support, provide the affected page, the steps that reproduce the issue, expected versus actual behaviour, and non-sensitive error text. **Never include passwords, verification codes, payment-card details, identity documents, API keys or other secrets.**

## Repository and project structure

- `index.html` — primary support-centre homepage.
- `support/index.html` — alternate support landing page.
- `docs/product-tour.html` — product-tour guide.
- `package.json` — support-site package metadata and start script.

The support pages are authored primarily in HTML, CSS and JavaScript. `index.html` includes searchable help topics, FAQs and dated product updates; `docs/product-tour.html` provides the guided tour. Keep descriptions of organisation tenancy, AI features, identity verification and subscription entitlements aligned with the live product and deployment. Follow the package scripts and deployment configuration for the environment you are actually using; do not assume that opening a source file locally verifies the production deployment.

## Deployment and maintenance

The repository's `main` branch contains source files. A successful commit alone does not prove that the public site has deployed correctly. After changes, inspect the relevant GitHub Actions or hosting status and test the published Support Centre and product-tour URLs.

When Hamlet's product changes, review the homepage, alternate support landing page, product tour, FAQs, troubleshooting steps, release references and navigation links together. Keep release numbers, file names and feature descriptions aligned with the authoritative product site. Update the dated **What’s new** section whenever a notable workflow or product enhancement ships; make clear whether an item is generally available, account-dependent, in staged rollout or still planned. Do not describe a planned feature as released, and do not infer desktop installer versions from web-app changes.

## Reporting documentation issues

Use [GitHub Issues](https://github.com/hamletofficial/stack/issues) to report documentation or site problems. Include the relevant page and concise reproduction steps. Remove personal or confidential data from screenshots and logs before sharing them.
