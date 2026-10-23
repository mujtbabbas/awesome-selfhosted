# Changelog

All notable changes to this standalone edition of awesome-selfhosted are documented in this file.

## v1.1.0 — Standalone enhancements (2026-10-20)

- Converted the repository from a fork into a standalone edition with its own history, keeping full upstream credit.
- Added an "About This Standalone Edition" section to `README.md` with the upstream link, base-version provenance, credit, and a Table of Contents entry.
- Added `ENHANCEMENTS.md` documenting everything changed in this edition.
- Added `.github/dependabot.yml` for weekly GitHub Actions dependency updates.
- Added markdown linting automation (`.markdownlint.json` and the Markdown check workflow — this repository's first workflow, since upstream ships none here; its link/maintenance checks live in the separate awesome-selfhosted-data repository); the check was later scoped via `.markdownlint-cli2.yaml` so it covers this edition's own documentation instead of failing on upstream content.
- Added `.editorconfig` with standard editor settings (UTF-8, LF, 2-space indent).
- Licence recorded, not changed: `LICENSE` in tree is CC BY-SA 3.0 (Attribution-ShareAlike), so this standalone edition stays CC BY-SA 3.0.

## v1.0.0 — Upstream baseline (2026-10-20)

- Clean standalone baseline of [awesome-selfhosted/awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) at upstream commit `121b4eb6d44bf3b21ffa1cba056fe208146891c2` (upstream HEAD dated 2026-10-18; upstream default branch is master, this edition uses main). Upstream's latest release tag (1.0.0) long predates the snapshot, so the commit SHA is the provenance.
- Fork history severed; all 6 upstream files preserved as-is, including the full generated list in `README.md` and `non-free.md`. The underlying list data now lives in the awesome-selfhosted-data repository, outside this edition's scope.
