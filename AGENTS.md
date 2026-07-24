# Repository Guidelines

## Project Structure & Module Organization

This is a Markdown-first editorial repository for Ultrathink, a weekly applied-AI newsletter for business decision-makers.

- `README.md` defines the publication’s positioning and repository goals.
- `examples/` contains the canonical plain-text reference issues.
- Use the naming pattern `exampleN_raw.md` for additional source issues.
- Place future drafts or analysis in clearly named directories rather than mixing them with canonical examples.

There is currently no application source code, asset pipeline, or automated test suite.

## Editorial Workflow

Use the examples to analyze Ultrathink’s voice, three-act structure, recurring sections, and editorial balance. When drafting a new issue, preserve the established sequence:

1. A concise take of the week.
2. A substantial, applied `ai native` column.
3. A curated `worth your time` roundup.

Raw examples must remain faithful to their source. Remove link destinations and styling, but retain visible link text. Replace image-only banners with the words they display, such as `future proof` or `job board`.

## Development and Validation Commands

No build or runtime commands are required. Use these checks before submitting changes:

```sh
rg --files
wc -w examples/*.md
rg -n 'https?://|!\[|\]\(' examples
rg -n ';' --glob '*draft*.md'
rg -n '—' --glob '*draft*.md'
git diff --check
```

These commands inventory files, compare issue lengths, detect URLs or Markdown links in raw examples, flag semicolons, audit em dash placement, and catch whitespace errors.

## Style & Naming Conventions

Use UTF-8 Markdown with blank lines between paragraphs. Keep prose concise, natural, and executive-readable. Avoid unnecessary formatting in `_raw.md` files, including headings, emphasis, bullets, and embedded URLs. Preserve original capitalization and punctuation unless normalization is necessary.

Newsletter prose must sound written and edited by a human. Never use semicolons. Avoid em dashes in narrative copy, but use one to separate each `worth your time` hook from its summary. Use periods, commas, or colons elsewhere. Avoid canned contrasts, clipped dramatic fragments, repeated sentence templates, artificial symmetry, and abstract conclusions that merely restate the setup. Read drafts aloud and rewrite anything that sounds generated.

## Commit & Pull Request Guidelines

Recent commits use short, direct summaries. Prefer an imperative subject such as `Add fourth newsletter example` or `Clarify editorial goals`.

Pull requests should explain the editorial purpose, list affected files, and identify source URLs for imported issues. Call out any intentional changes to source wording. Include screenshots only when visual presentation or new assets are involved.

## Security & Source Integrity

Never commit credentials or populate `.env` with secrets. Verify externally sourced copy against the original page, and do not invent missing text, claims, or attribution.
