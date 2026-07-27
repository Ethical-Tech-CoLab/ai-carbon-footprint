# Backlog

Known gaps, in the order they would mislead a reader.

---

## Credibility review — 2026-07-27

A hostile-but-fair peer-review sweep of the report copy (canonical in
[AICF-Paper.md](AICF-Paper.md), mirrored on the site in
`website/src/content/publications/ai-carbon-footprint.ts`). Fix in both places.
See also [PEER-REVIEW.md](PEER-REVIEW.md). This report had a ~1000× arithmetic
error once before, so every magnitude here is worth re-deriving.

### 1. The Meta / LLaMA figure is misattributed

§04 says "Training LLaMA 3-70B generated an estimated 2,290 metric tons of CO₂,"
but the cited Hugging Face model card reports **2,290 t as the combined 8B + 70B
total** (8B ≈ 390 t + 70B ≈ 1,900 t). The 70B alone is ~1,900 t. Fix: change to
1,900 t for the 70B, or relabel 2,290 as the combined 8B-plus-70B total.

### 2. The Wyoming coal share is overstated and feeds the hero stat

§02 says "Wyoming, where 95 percent of electricity comes from coal." EIA puts
Wyoming coal generation at roughly 71–79% in recent years and falling. This
figure underpins the "10×" hero comparison against Quebec. Fix: correct to the
current EIA share with the year cited, and recheck the 10× ratio.

### 3. The data-center count cites a source not in the reference list

§03 gives "an estimated 11,000 data centers globally (Minnix, 2025)," but the
works cited lists Brightlio, not Minnix, leaving the figure effectively
unsourced. Fix: add the Minnix reference or reattribute the 11,000 figure.

### 4. (Carried from earlier) The thesis qualifier is never argued

The claim that mitigation can cut the footprint "without hindering its
development and role in advancing society" is never defended in the body. Engage
the rebound problem (which the report's own "inference dominates at scale"
argument implies) and the possibility that binding regulation slows deployment,
or drop the clause.

---

## Peer-review findings (from PEER-REVIEW.md, 22 Jul 2026 — "major revisions")

Full referee report in [PEER-REVIEW.md](PEER-REVIEW.md). Verify each against the
current report copy and check off any already fixed. Note the site's mirror
`ai-carbon-footprint.ts` was corrected for a ~1000× inference-energy error on a
branch once before — confirm this repo's copy matches.

Major:
- [ ] **Inference-energy math has a ~1000× error and is internally inconsistent
      (§2 ¶4–5).** 0.047 kWh × 1e12 queries = 47,000,000 MWh (47 TWh), not the
      stated 47,000 MWh; the second scenario conflates "365 days" with "365×
      training." Recompute both from consistent units (TWh/GWh) and re-derive
      the ×training multiple rather than asserting it.
- [ ] **Cluster of technical errors (§2–§3).** PUE scale stated backwards (it is
      bounded below by 1.0, unbounded above); the 626,000 lb CO₂ figure is
      Strubell et al.'s NAS run, misattributed to BERT-base (and inconsistent
      with the 1,507 kWh figure); "rare earth elements like lithium, cobalt,
      nickel" — none is a rare earth (they are critical minerals). Correct all
      three.
- [ ] **Over-reliance on corporate self-reporting (§4).** Google/Microsoft/AWS/
      Meta pledges relayed at face value; AWS "2040 target met by 2024" is
      garbled; "fully offset" treated as "not emitting." Cite the primary
      studies (Strubell 2019, Patterson 2021, Luccioni 2022) directly; separate
      pledge from achievement and market-based from location-based accounting.
- [ ] **Thesis qualifier "without hindering development" never argued (thesis /
      §1 / §7).** Engage the Jevons/rebound tradeoff and cite a net-impact
      estimate, or soften the thesis. (Same as credibility item 4 above.)

Minor: unsourced "inference 60–80%" vs "pre-training 90–95%" framing unreconciled
(m1); §5 and §6 overlap (m2); GPT-3 naming inconsistent (m3); DeepMind 280B =
Gopher, name it (m4); 0.047 kWh/query is high and needs a primary cite + range
(m5); citation style inconsistent (m6); WUE unit not stated (m7).
