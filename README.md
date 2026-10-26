# Hamlet Support Centre

The Support Centre is the help and product-documentation home for **hamlet**, a connected workspace for commercial property professionals. It explains how to use the platform, complete common tasks, troubleshoot account and workspace issues, and understand the boundaries of public and private information.

## Current product and release information

Hamlet's web workspace and its Windows desktop installer are versioned and released separately. Do not infer the desktop installer version from the Support Centre's own `package.json` version.

- **Current stable product label:** `v1.04.02`
- **Windows installer:** use the filename and version currently published on the official downloads page; do not rely on a hard-coded filename in this README.
- **Release source:** [Hamlet releases and downloads](https://www.hamlet-ai.co.uk/download.html)
- **Official product website:** [hamlet-ai.co.uk](https://www.hamlet-ai.co.uk/)
- **Support website:** [support.hamlet-ai.co.uk](https://support.hamlet-ai.co.uk/)

Check the official downloads page for the latest release, current file size and published SHA-256 checksum before installing. Never rely on a filename or version copied into old support content as proof that an installer is current.

## Start here

- **[Support home](https://support.hamlet-ai.co.uk/)** — search help topics, FAQs and troubleshooting guidance.
- **[Product tour](https://support.hamlet-ai.co.uk/docs/product-tour.html)** — understand the connected commercial-leasing workflow and the role of the main workspace areas.
- **[Downloads and installation](https://www.hamlet-ai.co.uk/download.html)** — obtain the official Windows installer and verify its checksum.

## What Hamlet covers

Guides should reflect the features actually available to the account and current deployment. The platform's broader workflows include:

- Commercial property listings, member portfolios and property resources.
- Deal pipeline management, including LOI Issued, Due Diligence, Under Contract and Closed stages, with attention to critical dates and follow-up.
- Residential property resources and publishing controls.
- Member profiles, directory and professional identity.
- Broker Rankings and platform reporting.
- Broker Social Feed, member messaging and notifications where enabled.
- AI-assisted workflows, including Deal Copilot and Listings Assistant, subject to authentication, model gateway availability and the permissions required by each feature.
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

The support pages are authored primarily in HTML, CSS and JavaScript. Follow the package scripts and the deployment configuration for the environment you are actually using; do not assume that opening a source file locally verifies the production deployment.

## Deployment and maintenance

The repository's `main` branch contains source files. A successful commit alone does not prove that the public site has deployed correctly. After changes, inspect the relevant GitHub Actions or hosting status and test the published Support Centre and product-tour URLs.

When Hamlet's product changes, review the homepage, alternate support landing page, product tour, FAQs, troubleshooting steps, release references and navigation links together. Keep release numbers, file names and feature descriptions aligned with the authoritative product site.

## Reporting documentation issues

Use [GitHub Issues](https://github.com/hamletofficial/stack/issues) to report documentation or site problems. Include the relevant page and concise reproduction steps. Remove personal or confidential data from screenshots and logs before sharing them.
