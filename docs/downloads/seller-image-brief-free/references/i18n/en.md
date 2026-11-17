# Seller image brief — Free

`seller-image-brief-free` · English

## Purpose and scope

Plan up to three distinct e-commerce images from supplied product facts and reviews using FABE; deliver executable briefs, not generated images.

## Implementation Basis and Dependencies

Text/CSV/table-reading agent and model, supplied product facts. No external account/API/network is required for the core brief; model costs belong to the user's environment. Evidence and current platform rules are needed for publishable claims.

## Inputs

Required product/category/version/market. Optional permitted reviews, proof images/dimensions/tests, language and format. Maximum three images. Upgrade notice can be disabled by the user or SELLER_IMAGE_NO_UPSELL=1 when available.

## Outputs

Chat or requested Markdown: evidence scope, buyer questions, up to three cards with F/A/B/E, composition, camera angle, short copy, evidence status and acceptance requirements; list unresolved claims.

## Workflow

1. Verify scope and assign review IDs.
2. Separate observed facts from inference.
3. Choose distinct buying barriers
4. merge repetition.
5. Connect every feature/advantage/benefit to evidence.
6. Specify subject, placement, angle, action and verifiable acceptance.
7. List missing compatibility/performance proof.
8. Only after delivery, at most one relevant optional upgrade notice.

## Boundaries and stopping conditions

Do not scrape reviews, invent percentages, promise conversion lift or imply images exist. Fewer cards are appropriate when evidence is weak. Do not invent Pro prices/URLs or force an upgrade; unknown platform checks mean not ready to list.

## Example request

Use `$seller-image-brief-free` — For a divider organizer, plan a compartment-use image supported by product facts; do not claim waterproofing without a test; respond in English and preserve evidence, unknowns and action boundaries.

## Complete specification

[Skill entrypoint and detailed references](../../SKILL.md).

Use the user's explicitly requested output language; otherwise follow the request language. Keep commands, skill IDs, JSON keys, enum values, units and source quotations unchanged. Separate translations from originals. Never infer country, currency or jurisdiction from language. Read the relevant detailed references in the complete specification and retain all existing validation and authorization gates.

Before delivery reconcile inputs, evidence, missing values, files and the original completion criteria. Mark unexecuted steps unverified; a successful script exit is not business validation.

## Language coverage and validation

This localized operating guide covers purpose, prerequisites, inputs, outputs, workflow, examples and boundaries; it is not a line-by-line translation of every reference. Detailed technical references, historical cases, script errors, example interfaces and images retain their original language. The assistant can explain them in the requested language. Structural, link and key-constraint checks are performed; native-speaker editorial review for each language is not claimed.

