# Enhancements — Standalone Edition Changelog

Upstream: <https://github.com/awesome-selfhosted/awesome-selfhosted>
Maintainer of this edition: Syed Mujtaba Abbas (@mujtbabbas)

## v1.1.0 — Enhancement release (2026-10-20)

- Added "About This Standalone Edition" section to README.md with upstream
  link, base version provenance, credit, and a Table of contents entry.

- Added this changelog (ENHANCEMENTS.md).
- Added .github/dependabot.yml (weekly GitHub Actions updates).
- Added .markdownlint.json and .github/workflows/markdown-check.yml
  (markdown linting automation; upstream ships no workflows in this repo —
  its link/maintenance checks live in the separate
  awesome-selfhosted-data repository — so this is its first workflow).

- Added .editorconfig (standard editor settings: UTF-8, LF, 2-space indent).
- Licence recorded, NOT changed: LICENSE in tree is CC BY-SA 3.0
  (Creative Commons Attribution-ShareAlike 3.0 Unported) — the file the
  GitHub API reports as NOASSERTION. ShareAlike: this standalone edition
  must stay CC BY-SA 3.0.

## v1.0.0 — Baseline (2026-10-20)

- Clean standalone baseline of awesome-selfhosted/awesome-selfhosted at
  upstream commit 121b4eb6d44bf3b21ffa1cba056fe208146891c2 (upstream HEAD
  dated 2026-10-18; upstream default branch master, this edition uses
  main). Upstream's latest release tag (1.0.0) long predates the snapshot,
  so the commit SHA is the provenance.

- Fork history severed; all 6 upstream files preserved as-is: README.md
  (the full generated list, 331 KB), non-free.md, LICENSE, the issue/PR
  templates, and _static/awesome.png (1975 bytes, the only binary — a
  connector snapshot push cannot carry binaries). Upstream restructured:
  the underlying list data now lives in the awesome-selfhosted-data
  repository, which is outside this conversion's scope.
