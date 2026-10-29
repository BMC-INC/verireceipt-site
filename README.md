# VeriReceipt · Public Website

The public information, support, and policy website for VeriReceipt, a receipt capture and organization app.

[Visit the website](https://bmc-inc.github.io/verireceipt-site/) · [Support](https://bmc-inc.github.io/verireceipt-site/support/) · [Privacy](https://bmc-inc.github.io/verireceipt-site/privacy/)

## What this repository contains

This is a complete static website. It contains the product overview, support information, privacy policy, and terms of use. The VeriReceipt application, receipt processing, and subscription implementation are maintained separately; this repository does not include an installable receipt app.

| Page | Purpose |
| --- | --- |
| [`index.html`](index.html) | Product overview and navigation |
| [`support/`](support/index.html) | Support contact and common questions |
| [`privacy/`](privacy/index.html) | Published privacy policy |
| [`terms/`](terms/index.html) | Published terms of use |

## Preview locally

No package installation or build step is needed. From the repository directory, run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open [localhost:8000](http://localhost:8000). Follow the support, privacy, and terms links to check the complete navigation. Stop the server with `Ctrl+C`.

## Maintenance

The site uses plain HTML and embedded CSS and is published through GitHub Pages. Keep links relative so navigation works both locally and under the `/verireceipt-site/` project path. Changes to product claims and policies should be checked against the application before publication.

For product questions, use the [support page](https://bmc-inc.github.io/verireceipt-site/support/). For website defects, [open an issue](https://github.com/BMC-INC/verireceipt-site/issues). Do not include receipts or personal financial information in public issues.

## Reuse

This is a publicly viewable product website. No repository-wide open-source license is currently included; publication of the source does not grant a general reuse license.
