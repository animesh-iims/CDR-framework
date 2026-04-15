# CDR Framework (ERW & Biochar)

A modular decision-support framework to assess the suitability of agricultural clusters in India for carbon dioxide removal (CDR) deployment via **Enhanced Rock Weathering (ERW)** and **biochar**.

---

## What this is

This framework helps identify and prioritise deployment zones by evaluating clusters across multiple dimensions such as:

* Soil and climatic conditions
* Feedstock availability
* Infrastructure and logistics
* Policy and market readiness
* Environmental and operational risks

It is designed to balance:

* **Accuracy** (grounded in available data and research)
* **Usability** (practical for deployment teams)
* **Adaptability** (modular and extensible across regions)

---

## How it works

* Each parameter is scored on a **1–5 scale**
* Certain criteria act as **knockouts (KO)** where deployment is not viable
* Scores are aggregated using a **weighted structure**
* ERW and biochar are evaluated **separately**, with pathway-specific considerations
* Missing data can be marked as **N/A**, with visibility into coverage

The framework is implemented as an interactive HTML tool.

👉 **Live tool:**
https://animesh-iims.github.io/climate-framework/

---

## Versioning

### v1

* Initial structure with core parameters and scoring logic
* Separate modules for ERW and biochar
* Basic weighted aggregation and KO logic

### v2 (current)

* Refined scoring logic and parameter definitions
* Improved UI/UX (tooltips, readability, structure)
* Added N/A handling and coverage visibility
* Expanded criteria:

  * Soil drainage (ERW knockout)
  * Biochar-specific risks (e.g., feedstock competition, double counting)
  * Market readiness (VCM/CCTS)
* Introduced open-source data integration (manual + assisted)

---

## What this is not

* Not a definitive site selection tool
* Not a substitute for field validation or MRV systems
* Not exhaustive—criteria can be extended based on context

This is a **structured starting point** to support decision-making, not replace it.

---

## Data & references (indicative)

The framework draws on publicly available data sources and research, including:

* Indian datasets: NBSS, ICAR, IMD, GSI
* Global datasets: WorldClim
* MRV frameworks and methodologies (e.g., Isometric, Puro.earth)
* Literature and case studies from active CDR deployments

---

## Why this exists

Early-stage CDR deployment often faces a trade-off between:

* overly simplistic heuristics, and
* overly complex, hard-to-use models

This framework attempts to sit in between:

* structured enough to be systematic
* simple enough to be usable

---

## Next steps

* Expand and validate criteria with field data
* Improve data integration and automation
* Incorporate feedback from practitioners
* Explore applicability beyond India

---

## Feedback

Open to feedback, critique, and collaboration—especially from people working on:

* ERW
* Biochar
* MRV
* Climate / agri deployment in India

---

## Author

Animesh B.
IIM Shillong

---
