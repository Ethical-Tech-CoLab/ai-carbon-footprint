# Decision-model recommendation: evidence-condition checking

Date: 2026-10-11. Public-source research proposal; no measured energy result.
Reviewed [README](https://github.com/Ethical-Tech-CoLab/ai-carbon-footprint/blob/188c2304eddf8d8ea87a10545628dcc84ead3146/README.md).
This document-led assessment preserves the report's recorded corrections and
open peer-review limitations.

## Useful bounded task

Assist researchers in determining whether a source actually supplies the
conditions needed for a stated energy claim: hardware, workload, precision,
batching, utilization, serving software, measurement boundary and uncertainty.
Use present / absent / ambiguous for each field, retaining exact source spans.
Check numeric arithmetic, units and conversions with code, never a model.

A second task is supports / contradicts / not established for a claim and its
source. Do not ask the model to invent missing energy measurements.

## What must not change

Cheap tokens, shorter outputs and lower latency do not establish lower energy
or carbon. Carbon also depends on the electricity context and accounting
boundary. Preserve vendor-versus-independent evidence distinctions, rebound
effects and the report's unresolved thesis qualifications.

## Evaluation

Compare a checklist and deterministic field extraction with a local classifier,
Jev's [citation-checking pattern](https://docs.typesafe.ai/cookbooks/citation_check.md),
Microsoft-Decision-1 and Sage using public papers.
Split by study/source family, not repeated claims from the same paper.

Measure false assertions that a condition was measured, missing-field recall,
calibration, reviewer agreement and cost per reviewed source. Include estimates
misdescribed as measurements, training/inference confusion and incompatible
system boundaries. Preserve unknown values instead of success-shaped defaults.

## Pilot

Keep the original report unchanged; add only reversible research annotations
after human adjudication. Adopt only with demonstrated review benefit. Do not
claim environmental savings from this proposal. Local processing needs a
licensed local model; the three proprietary checkpoints are not locally
downloadable equivalents.
