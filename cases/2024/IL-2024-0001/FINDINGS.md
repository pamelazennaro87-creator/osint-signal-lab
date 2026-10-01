# Findings — IL-2024-0001

## FINDING-001 — Spoken Arabic gap pre-dates Oct 2023 in PRIMARY narrative
**Status:** PRIMARY  
**Evidence:** Slides 3–10 sequence ChatGPT → LLaMA (English only) → Falcon → JAIS/AceGPT → **No Spoken Arabic**.  
**Implication:** Capability archaeology can show the *technical problem* was framed before the war acceleration described in 2025 reporting, without asserting that 7 Oct *caused* the project idea.

## FINDING-002 — Methodology public; task catalogue not public
**Status:** PRIMARY  
**Evidence:** Slides 11–20 cover data selection, evaluation, ablations, instruction-tuning principle. Slide 19: “broad range of tasks relevant to your domain” with **no** named tasks, datasets, or I/O examples.  
**Implication:** Strong answer to “how did they train?”; weak/absent answer to “what exact tasks?”

## FINDING-003 — 2025 investigation is a Source Delta, not a slide transcript
**Status:** SECONDARY  
**Evidence:** Guardian/+972/Local Call (2025-03-06) add unit, corpus claims, intended Q&A use, precursor models, deployment uncertainty.  
**Implication:** Secondary reporting should not be back-projected into the PDF as if the slides contained operational task specs.

## FINDING-004 — Deployment and predictive production use unresolved
**Status:** UNRESOLVED  
**Evidence:** Investigation states training continued in H2 2024 and does not establish large-LLM deployment; slides contain no deployment claim. Aspirational prediction rhetoric reported from talk context is not a published evaluation result.  
**Implication:** Do not treat the foundation model as a proven production predictive system from open sources alone.
