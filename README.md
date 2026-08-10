

# ESUIT Extensions Archive

An unofficial archive of discontinued ESUIT browser extensions for digital preservation, technical documentation, security research, and historical reference.

> [!IMPORTANT]
> This repository is not affiliated with ESUIT, William Chen, Meta, Facebook, Instagram, or Google.

## Background

ESUIT developed a collection of Chromium browser extensions for exporting and downloading content from Facebook and Instagram.

In 2026, the ESUIT service, website pages, payment subscriptions, and Chrome Web Store listings had become unavailable.

## Purpose of this repository

This is an archival repository. It is not an official continuation of ESUIT and does not provide a replacement subscription service.

## Archived extensions

| Extension                             | Platform  | Archived version |
| ------------------------------------- | --------- | ---------------: |
| ESUIT Comments Exporter for Facebook  | Facebook  |          `2.8.1` |
| ESUIT Export User Likes for Facebook  | Facebook  |          `1.3.0` |
| ESUIT Photos Downloader for Facebook  | Facebook  |         `4.10.2` |
| ESUIT Photos Downloader for Instagram | Instagram |         `3.13.2` |
| ESUIT Posts Exporter for Facebook     | Facebook  |         `2.19.3` |
| ESUIT Video Downloader for Facebook   | Facebook  |          `2.9.2` |

## Important source-code distinction

The files in this repository are unpacked production extension distributions.

They contain the HTML, CSS, JavaScript, manifests, translations, icons, and other resources distributed to users. Much of the JavaScript has been compiled, bundled, minified, or otherwise transformed from the original development source.

> [!NOTE]
> Each `manifest.json` specifies `host_permissions` and `externally_connectable` matches for `https://*.esuit.dev/*`. As the ESUIT service is discontinued, requests to this domain will fail, which may affect functionality dependent on server-side authentication or license verification.

This repository therefore does **not** necessarily contain the original:

* TypeScript source files
* Build configuration
* Package manifests
* Source maps
* Development comments
* Original module boundaries
* Test suites
* Unminified dependency source

The archived files may be useful for reconstruction and reverse engineering, but they should not be confused with the original maintainable source repository.

## Responsible use

Use these materials only for lawful and authorised purposes.

You are responsible for complying with:

* Copyright law.
* Privacy and data-protection law.
* Applicable computer-misuse law.
* Facebook and Instagram terms and policies.
* Browser-extension platform policies.
* Any obligations applying to the content or accounts being accessed.

Do not use these extensions to access private information without permission, evade access controls, bypass payment or licensing restrictions, or collect content you are not authorised to obtain.

## Contributing

Contributions of missing original versions are welcome when their provenance can be reasonably documented.

Where possible, contributions should include:

* The exact extension name and version.
* The original CRX file or an unmodified extracted copy.
* The date the copy was obtained.
* The original Chrome Web Store listing URL or extension ID.
* A SHA-256 checksum.
* A brief explanation of provenance.
* Confirmation that files have not been patched or modified.

Modified, cracked, repackaged, or entitlement-bypassing builds should not be presented as original archival copies.

Changes made for research should be kept clearly separate from preserved originals.

Please do not submit personal browser data, cookies, access tokens, downloaded user content, account identifiers, or other sensitive information.

## Disclaimer

The repository is provided **as is**, without warranty of any kind.

The archive maintainer does not guarantee that the software is complete, secure, functional, accurate, lawful for every use, or compatible with current browser and platform versions.

Use of these files is entirely at your own risk.
