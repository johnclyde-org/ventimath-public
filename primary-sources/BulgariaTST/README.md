# Bulgaria TST — Bulgarian IMO Team Selection Tests

## Contest Owner

**Union of Bulgarian Mathematicians (СМБ)** and the national olympiad
commission. The selection tests ("Контролни за определяне на отбора за
МОМ") are the final stage picking Bulgaria's six-student IMO team from
the top finishers of the national olympiad. One or two tests per year,
each in IMO format: two days, three problems, 4.5 hours.

## Contents

- `aops/c{ID}.json` — raw AoPS community category captures (the
  `fetch_category_data` API response for each per-year collection;
  problem statements are BBCode in `post_data.post_canonical`).
  `c3276.json` is the tree root; the per-year collections cover
  2003–2008 and 2020 (c3521–c3526, c1798657).
- `official/kmom-2020-probs.pdf` — the official Bulgarian paper for the
  2020 test ("Контролно за определение на отбора за 61 МОМ", София,
  май 2020): two days of three problems.
- `official/kmom-2020-sol.pdf` — the official solutions (7 pages).

The AoPS 2020 collection omits Problem 4 (Ivan's checker-placement
game); the official paper includes it.

## Source

- AoPS community tree: https://artofproblemsolving.com/community/c3276
  (per-year collection URLs are `.../community/c{ID}` with the IDs above).
- Official PDFs from the Klasirane.com selection-test archive
  ("Контролни за МОМ", years 1994 and 2003–2025 with problems and
  solutions): https://klasirane.com/competitions/KMOM/All — file URLs
  follow `https://klasirane.com/api/competitions/KMOM/All/{year}/9-12%20кл/probs`
  (and `/sol`). Klasirane credits the "Български математически
  състезания" book series and school Sicademy.

## Attribution

Problems are the property of the Bulgarian national olympiad
commission / СМБ. English statements in the AoPS captures are community
translations; the official Bulgarian papers are authoritative. The
missing 2020 Problem 4 also appears in English on Dragomir Grozev's
blog: https://dgrozev.wordpress.com/2020/07/17/ivan-plays-tic-tac-toe-bulgarian-tst-2020-p4/
