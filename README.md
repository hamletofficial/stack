# Hamlet Support - Deployment Notes

The Hamlet Support Centre is the help and documentation website for **hamlet**, a workspace for a broker community working with commercial property listings and deal pipelines. It brings together practical product guidance, troubleshooting steps and frequently asked questions.

## Current hamlet release

- **Stable release:** `v1.04`
- **Release date:** 16 October 2026
- **Windows package version:** `1.4.0`
- **Installer:** `hamlet-Setup-1.4.0.exe` (approximately 93.5 MB)
- **Checksum file:** `SHA256SUMS.txt`, supplied alongside the installer to support integrity verification
- **Release status:** Stable release, not a pre-release

The public release label `v1.04` and Windows package version `1.4.0` refer to the same release. The Support Centre's own package version in `package.json` is tracked separately and is not the desktop application's version.

For current product information and download guidance, visit the [official hamlet website](https://www.hamlet-ai.co.uk/). The [GitHub Releases page for this repository](https://github.com/hamletofficial/stack/releases) lists releases published specifically in this repository.

## Repository

- **Repository:** [hamletofficial/stack](https://github.com/hamletofficial/stack)
- **Homepage source:** `index.html`
- **Additional support page:** `support/index.html`
- **Package metadata:** `package.json`
- **Official hamlet website:** https://www.hamlet-ai.co.uk/

## What the support centre covers

- Getting started and account access.
- Sign-in, email verification and identity-verification troubleshooting.
- Deal pipeline stages: **LOI Issued**, **Due Diligence**, **Under Contract** and **Closed**.
- Critical-date and reminder guidance.
- Commercial property listings and responsible descriptions of Passivhaus and EnerPHit credentials.
- Deal-flow reporting, common problems and FAQs.
- Safe guidance on what to include in a support request.

## Preview locally

Open `index.html` in a modern browser to preview the homepage. The site uses plain HTML, CSS and JavaScript and currently requires no package installation or build step. The matching support page is available at `support/index.html`.

## Project structure

```text
.
├── index.html
├── package.json
├── README.md
└── support/
    └── index.html
```

## Deployment

The homepage and support page are committed to the repository's `main` branch. Their presence in GitHub does **not** by itself confirm that the public website is deployed. Public availability depends on the repository's hosting configuration and a successful deployment; verify the published URL before sharing it as live.

## Contributing and reporting issues

Please use the repository's [GitHub Issues](https://github.com/hamletofficial/stack/issues) to report documentation or website issues. Include the affected page, steps to reproduce the problem, expected and actual behaviour, and any non-sensitive error text. Do not include passwords, payment details or identity documents.
