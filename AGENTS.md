# GPTAd documentation instructions

## Project

This Mintlify site contains agency guides for GPTAd prospects and clients. Content is MDX with title and description frontmatter. Navigation and branding live in `docs.json`.

## Audience and boundaries

- Focus on ChatGPT Ads agency services and the client relationship.
- Onboarding begins only after the client accepts the service agreement.
- Keep discovery, agreement acceptance, onboarding, and launch approval distinct.
- Do not document internal software, account signup, or self-service product workflows.
- Keep advertising spend separate from agency fees.
- Do not invent commercial commitments, platform eligibility, partnerships, or results.
- Link changing platform claims to current official OpenAI sources.
- Treat the agreement as the authority for scope, fees, timing, and contractual terms.

## Writing

Use active voice, sentence case, concise sentences, and direct language. Explain each page's purpose and the next step. Use descriptive links and tables for comparisons. Avoid duplicating detailed checklists across pages. Preserve the public contact address `contact@gptad.io` unless a verified replacement is provided.

## Validation

Run `mint validate` and `mint broken-links` after edits. Review the diff, navigation coverage, and agreement-first journey. Keep maintainer-only files excluded in `.mintignore`. Do not publish or push unless requested.
