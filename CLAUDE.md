# Strix Benchmarks

Personal benchmarking site. First person ("I") throughout, never "we".

## Writing Rules

- No colons in prose (colons are fine when introducing a list)
- No semicolons
- No em dashes
- Hyphens are fine (compound words, model names)
- Never use the word "romance" on site. The writing benchmarks are "creative
  writing" or just "writing".
- This is because I author that genre separately. Site copy must describe
  benchmark output as capability testing, not model-assisted authorship.
- Keep copy direct and factual. This is a data site, not a blog post.
- Keep public writing-benchmark summaries at the evaluation level and
  spoiler-safe. State scores, completion or length, and broad craft findings.
  Do not retell plot beats, reveals, character backstories, setting facts, or
  scenario-specific continuity errors.
- Report artifact size, memory fit, and quant tradeoffs when they help readers
  choose or run a model. Do not discuss personal model inventory, NVMe or
  coldstore placement, local retention, or storage incident history unless
  storage itself is the measured subject.

## AI Slop Prevention

Read `tropes.md` before writing or editing any prose on this site. It catalogs
the sentence-level patterns that make text read as AI-generated. The biggest
offenders to watch for:

- Bold-first bullets (every list item or callout starting with a bolded phrase)
- Em dash addiction (use periods, commas, or restructure instead)
- Negative parallelism ("It's not X, it's Y")
- Grandiose stakes inflation ("the most comprehensive", "fundamentally reshape")
- Pedagogical voice ("Let's break this down", "Think of it as")
- Rhetorical questions answered immediately ("The result? Devastating.")
- "Serves as" and other copula dodges
- Tricolon/anaphora abuse (three-part parallel structures repeated back to back)

## Homepage Feature Notes

- Treat `src/pages/index.astro` as a reverse-chronological benchmark news feed.
  Every newly published model result or material follow-up goes at the top,
  immediately below the hardware stats. Never insert a newer result beneath an
  older feature.
- Keep the previous lead directly below the new entry and remove its
  `.badge.new` treatment. Only the current newest entry carries that badge.
- Move existing sections rather than duplicating them when the feed order
  changes.
- Keep detailed per-quant comparisons on `src/pages/quantization.astro`. The
  homepage may carry a compact follow-up and the Models page should link to the
  comparison. Do not replace a reference row or assign a Combined score until
  the alternative quant has results for every component of that score.

## Tooling Column

- The models page Quality table has a Tooling /65 column. It is scored
  separately and excluded from Combined /285. Untested models show a hyphen.
  Update the hyphen to a score as models run the suite.
