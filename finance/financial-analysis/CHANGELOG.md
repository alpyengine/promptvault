# Changelog

## [5.3.0] - 2026-07-10

### Added

- Broadened Script Brief activation: discrete price levels are sufficient on their
  own (no formula, oscillator or algorithmic system required). Closes the false
  "NOT APPLICABLE" that skipped valid level-based indicators.
- Coherence control between Sequence 5 and Sequence 6: if a detected strategy is
  Pine-viable, Sequence 6 must generate the brief.

---

## [5.2.0] - 2026-07-10

### Added

- Level Reconciliation rule: every drawable price level cited in the report must
  appear in the Script Brief or be listed under "Open items" with an explicit
  exclusion reason — never dropped silently.
- Reconciliation control added to the final audit.

---

## [5.1.0] - 2026-07-10

### Added

- Mandatory sequence completeness: no sequence is omitted silently; non-applicable
  sequences are rendered explicitly as "NOT APPLICABLE" with a reason.
- Opinion attribution extended to narrative prose (dashboard, macro context), not
  only the asset matrix.
- Unambiguous indicator vs strategy classification in the Script Brief.

### Changed

- No-repaint brief section kept at requirements level (no premature Pine API
  injection such as barmerge).
- Multi-symbol briefs flagged as candidates for a generic parametrizable indicator
  instead of per-ticker hardcoded logic.

---

## [5.0.0] - 2026-07-10

### Changed

- BREAKING: Sequence 6 no longer emits production Pine code. It now produces a
  **Script Brief** — a self-contained hand-off specification consumed by the
  "Pine Script Farm" project, where a dedicated skill writes and validates the
  real v6 code against the official reference.

### Added

- Two independent on-demand deliverables: the financial PDF and the Script Brief
  (the brief is never embedded in the PDF).
- FACT / OPINION / INFERENCE tagging on every operable rule.
- Optional non-authoritative Pine draft, included only for side-by-side comparison
  and freely discardable by the Farm.

---

## [4.0.0] - 2026-07-05

### Added

- Strict source validation and isolation rules.
- Mandatory source verification stage.
- Two-phase PDF generation workflow.
- Explicit user confirmation before PDF compilation.
- Standardized PDF naming conventions.
- Source integrity validation during the final audit.

### Changed

- Strengthened Pine Script generation requirements.
- Improved reproducibility of generated reports.
- Enhanced report compilation workflow.

---

## [3.0.0]

### Added

- Executive dashboard
- Investment scoring
- Institutional workflow
- Factor analysis
- Strategy detection
- Research audit

---

## [2.0.0]

### Added

- Evidence-based reasoning
- Validation workflow
- Watchlists
- Asset matrix
- Conviction level

---

## [1.0.0]

### Added

- Initial prompt
- Finviz classification
- Pine Script generation
