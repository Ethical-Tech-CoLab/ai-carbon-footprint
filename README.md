# AI's Carbon Footprint

**The Environmental Impact of Artificial Intelligence** — an academic report from the [Ethical Tech CoLab](https://ethical-tech-colab.github.io/website/) (NYU SPS Center for Global Affairs × Microsoft).

📄 **Read it:** https://ethical-tech-colab.github.io/ai-carbon-footprint/

## About

AI's rapid expansion carries a significant but often overlooked environmental cost. This report examines AI's energy demands across training and inference, its data-center and hardware toll, and the mitigation strategies, regulatory frameworks, and policy considerations that could reduce its ecological footprint without hindering its development.

**Sections:** Introduction · AI's Energy Consumption · Data Centers & Hardware Impact · Mitigation Strategies & Sustainable AI · Regulatory Frameworks · Ethical & Policy Considerations · Conclusion & Future Directions · References (56 sources).

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
- Mitigation section (S4) relays vendor self-reporting uncritically while omitting the peer-reviewed primary sources. — *Open.*

**Noted strength:** The cooling-technology taxonomy and regulatory map (S3, S5) are clear, correct, and rarely assembled this cleanly.

### Revisions applied

- **S2 inference arithmetic recomputed** from the 0.047 kWh unit figure and reported in consistent units: one trillion queries is ~47 TWh (not 47,000 MWh), and the 4.3-billion-user scenario is ~74 TWh (not 470,000 MWh). The two scenarios now scale consistently — 1.57x the queries for 1.57x the energy — and the "x training" multiples are derived rather than asserted. Both are labelled as illustrative projections and as upper bounds, since 0.047 kWh/query sits at the high end of published estimates (~0.002–0.005 kWh).
- **PUE definition corrected (S3):** PUE is bounded *below* by 1.0 and unbounded above, with 1.0 the ideal floor and real facilities at ~1.1–2.0. The previous "scale is 0–1.0" statement described a physically impossible range.
- **BERT carbon figure disambiguated (S3):** the 1,507 kWh BERT-base run corresponds to ~3,300 lb CO2 on a coal grid. The 626,000 lb figure is Strubell et al. (2019)'s number for a full neural architecture search with hyperparameter tuning, not BERT-base training; the report now says so and cites Strubell et al. directly (now 56 sources).
- **Mineralogy corrected (S3):** lithium, cobalt, and nickel are described as critical minerals, distinguished from true rare-earth elements (lanthanides plus scandium and yttrium). The extraction-impact argument is unchanged.
