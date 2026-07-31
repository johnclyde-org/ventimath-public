# China TST — Chinese IMO Team Selection Tests

## Contest Owner

**Chinese Mathematical Olympiad Committee** (Chinese Mathematical
Society). The national training camp (国家集训队) runs two stages of
selection tests picking China's six-student IMO team; each sitting is
three problems in 4.5 hours, IMO format.

## Contents

- `papers/china-tst-{YEAR}-*.pdf` — the Chinese papers for recent
  cycles, as compiled and republished by the education aggregator
  自主选拔在线 (zizzs.com):
  - 2024: stage-1 selection tests with answers (one combined file).
  - 2025: tests 1–2 (each both days combined) and tests 3–4 (one file
    per day).
  - 2026: stage-1 tests 1–4 and stage-2 days 1–4 (days 2–3 include
    answers).
- `aops/c{ID}.json` — raw AoPS community category captures (the
  `fetch_category_data` API response for each per-year collection;
  problem statements are BBCode in `post_data.post_canonical`).
  `c3282.json` is the tree root; the 41 per-year collections run
  1986–2026.

The Chinese Mathematical Society releases no official archive of the
camp papers. The canonical published record is the annual 走向IMO
(East China Normal University Press, written by the national-team
coaches) and the 中等数学 magazine, both commercial print. The 2022
and 2023 papers circulate only as photos on aggregator articles, not
as PDFs. For everything the papers above do not cover, the AoPS
community tree is the only comprehensive open record, and these
captures preserve it.

## Source

- Chinese papers from 自主选拔在线: the per-test articles under
  https://www.zizzs.com/gk/shitiku/ (e.g. the 2025 hub at
  `/gk/shitiku/197067.html` and the 2026 hub at
  `/gk/jingsai/217666.html`), each carrying its compiled PDF.
- AoPS community tree: https://artofproblemsolving.com/community/c3282
  (per-year collection URLs are `.../community/c{ID}`).

## Attribution

Problems are the property of the Chinese Mathematical Olympiad
Committee. English statements in the AoPS captures are community
translations of the Chinese originals; the 走向IMO volumes are the
authoritative published texts.
