# Seller image brief — Free

[简体中文](README.zh-CN.md) | [English](README.en.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Español](README.es.md) | [Português](README.pt.md)

Use the user's explicitly requested output language; otherwise follow the request language. Keep commands, skill IDs, JSON keys, enum values, units and source quotations unchanged. Separate translations from originals. Never infer country, currency or jurisdiction from language. Read the relevant detailed references in the complete specification and retain all existing validation and authorization gates.

## Installation and use

Download or clone the repository and copy the indicated skill directory, including its existing references, scripts, assets and other dependencies, into your host's skill directory. Keep its name and SKILL.md. Changing the documentation language does not require another installation. Commands are installation options, not evidence of installation or activation.

```sh
git clone https://github.com/PDBen-Auto/seller-image-brief-free.git
```

## Seller image brief — Free

`seller-image-brief-free`

Plan up to three distinct e-commerce images from supplied product facts and reviews using FABE; deliver executable briefs, not generated images.

Skill directory: `skills/seller-image-brief-free`

**Implementation Basis and Dependencies**

Text/CSV/table-reading agent and model, supplied product facts. No external account/API/network is required for the core brief; model costs belong to the user's environment. Evidence and current platform rules are needed for publishable claims.

**Inputs**

Required product/category/version/market. Optional permitted reviews, proof images/dimensions/tests, language and format. Maximum three images. Upgrade notice can be disabled by the user or SELLER_IMAGE_NO_UPSELL=1 when available.

**Outputs**

Chat or requested Markdown: evidence scope, buyer questions, up to three cards with F/A/B/E, composition, camera angle, short copy, evidence status and acceptance requirements; list unresolved claims.

[Workflow · Boundaries and stopping conditions · Example request](skills/seller-image-brief-free/references/i18n/en.md)

> Use `$seller-image-brief-free` — For a divider organizer, plan a compartment-use image supported by product facts; do not claim waterproofing without a test; respond in English and preserve evidence, unknowns and action boundaries.

## Language coverage and validation

This localized operating guide covers purpose, prerequisites, inputs, outputs, workflow, examples and boundaries; it is not a line-by-line translation of every reference. Detailed technical references, historical cases, script errors, example interfaces and images retain their original language. The assistant can explain them in the requested language. Structural, link and key-constraint checks are performed; native-speaker editorial review for each language is not claimed.

Before delivery reconcile inputs, evidence, missing values, files and the original completion criteria. Mark unexecuted steps unverified; a successful script exit is not business validation.
