# AI's Carbon Footprint

**[Live site](https://ethical-tech-colab.github.io/ai-carbon-footprint/)** ·
**[Research report](AICF-Paper.md)** (plain-language, non-technical)

**The Environmental Impact of Artificial Intelligence** — an academic report from the [Ethical Tech CoLab](https://ethical-tech-colab.github.io/website/) (NYU SPS Center for Global Affairs × Microsoft).

📄 **Read it:** https://ethical-tech-colab.github.io/ai-carbon-footprint/

## About

AI's rapid expansion carries a significant but often overlooked environmental cost. This report examines AI's energy demands across training and inference, its data-center and hardware toll, and the mitigation strategies, regulatory frameworks, and policy considerations that could reduce its ecological footprint without hindering its development.

**Sections:** Introduction · AI's Energy Consumption · Data Centers & Hardware Impact · Mitigation Strategies & Sustainable AI · Regulatory Frameworks · Ethical & Policy Considerations · Conclusion & Future Directions · References (58 sources).

## Authors

Advised by **Professor Yorke Rhodes III**. Written by Alexandra Du, Elizabeth Matthews, Emily Harrington, Hannah Zhao, Jennifer Hofmann, Natasha Nagarajan, Renata Gladkikh, and Smita Samanta.

## Structure

A single self-contained `index.html` (inline CSS, no build step), served via GitHub Pages. To preview locally, open `index.html` in a browser.

---

Views expressed are those of the researchers and do not represent the official positions of NYU, Microsoft, or any partner institution.

---

## Peer Review

The full independent academic peer review of this report is in [PEER-REVIEW.md](PEER-REVIEW.md) (also available as [Word](peer-review/ai-carbon-footprint-Peer-Review.docx) under [`peer-review/`](peer-review/)).

**Recommendation:** Major revisions

**What the review found:**

- Headline inference-energy figures contain a ~1,000x arithmetic error and the two scenarios contradict each other (S2). — **Fixed.**
- A cluster of technical errors in S3: the PUE scale is stated backwards, the 626,000 lb CO2 figure is misattributed, and lithium/cobalt/nickel are miscalled rare-earth elements. — **Fixed.**
- Mitigation section (S4) relays vendor self-reporting uncritically while omitting the peer-reviewed primary sources. — **Fixed.**
- The thesis's load-bearing qualifier, that mitigation can cut AI's footprint "without hindering its development and role in advancing society," is asserted and never argued (thesis, S1, S7). — *Open.* This is the clause that distinguishes the report from a simple "AI is bad for the planet" polemic, and nothing in the body defends it. The two things it needs to engage are the rebound problem, that efficiency gains enable more use and the report's own "inference dominates at scale" argument implies exactly that, and the possibility that binding regulation slows deployment. The counter-thread that AI can be part of the solution is likewise carried by initiative names rather than by net-impact estimates. Fixing it means either arguing the clause or dropping it.

**Noted strength:** The cooling-technology taxonomy and regulatory map (S3, S5) are clear, correct, and rarely assembled this cleanly.

### Revisions applied

- **S2 inference arithmetic recomputed** from the 0.047 kWh unit figure and reported in consistent units: one trillion queries is ~47 TWh (not 47,000 MWh), and the 4.3-billion-user scenario is ~74 TWh (not 470,000 MWh). The two scenarios now scale consistently — 1.57x the queries for 1.57x the energy — and the "x training" multiples are derived rather than asserted. Both are labelled as illustrative projections and as upper bounds, since 0.047 kWh/query sits at the high end of published estimates (~0.002–0.005 kWh).
- **PUE definition corrected (S3):** PUE is bounded *below* by 1.0 and unbounded above, with 1.0 the ideal floor and real facilities at ~1.1–2.0. The previous "scale is 0–1.0" statement described a physically impossible range.
- **BERT carbon figure disambiguated (S3):** the 1,507 kWh BERT-base run corresponds to ~3,300 lb CO2 on a coal grid. The 626,000 lb figure is Strubell et al. (2019)'s number for a full neural architecture search with hyperparameter tuning, not BERT-base training; the report now says so and cites Strubell et al. directly.
- **Mineralogy corrected (S3):** lithium, cobalt, and nickel are described as critical minerals, distinguished from true rare-earth elements (lanthanides plus scandium and yttrium). The extraction-impact argument is unchanged.
- **Corporate claims in S4 are now weighed rather than relayed.** The section opens with the three distinctions a reader needs — pledge versus achievement, market-based versus location-based accounting, and offsetting versus not emitting — and each company's claim is marked accordingly. The AWS contradiction is resolved: the Climate Pledge's net-zero-by-2040 target and the separate annual renewable-matching claim were two different commitments run together, and a 2040 target cannot have been met in 2024. Google's 100% carbon-free target is identified as an hourly goal its own reporting does not yet meet, Microsoft's carbon-negative pledge is read against its own reporting of rising emissions, and Meta's "fully offset" is unpacked as offset rather than unemitted.
- **The primary literature is cited directly (S4, References).** Patterson et al. (2021) and Luccioni et al. (2022) join Strubell et al. (2019) in the bibliography and are discussed by name in S4 as the peer-reviewed counterweight to vendor self-reporting (now 58 sources).
