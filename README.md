# CivicFlow AI - Generative AI Prototype for Public Records Routing

Human-centered generative AI routing system for public-records automation (prototype for Burnes Center AI for Impact)

This repository contains a **demonstration prototype** of *CivicFlow AI*, developed as part of my application for the **Generative AI Product Development Fellowship (AI for Impact Program)** at the **Burnes Center for Social Change, Northeastern University**.

The project operationalizes the four-layer framework described in my Candidate Product Specification Memo:
- **Trust:** Interprets and routes citizen requests accurately.
- **Empathy:** Generates plain-language, friendly staff responses.
- **Equity:** Handles multilingual and informal citizen inputs.
- **Governance:** Includes a human-in-the-loop review and audit system.

---

## Project Overview

### Problem
City governments often handle thousands of unstructured public records requests via email or web forms. Staff must manually read, classify, and route these requests — leading to delays, backlogs, and inconsistent service.

### Solution
**CivicFlow AI** uses a lightweight generative AI model to automatically:
1. Interpret request intent.
2. Classify it by department, priority, and sensitivity.
3. Generate friendly replies.
4. Log human corrections for ongoing improvement.

---

## Prototype Features

| Layer | Functionality | Implementation |
|-------|----------------|----------------|
| **Trust** | Classify and route public requests | Mock AI classifier using realistic pattern rules |
| **Empathy** | Auto-generate plain-language replies | Rule-based text generator |
| **Equity** | Handle multilingual (English + Spanish) input | Dataset includes multilingual example |
| **Governance** | Human approval log | Feedback dataframe and alignment metrics |

---

## Results (Demo Metrics)

| Metric | Result |
|---------|---------|
| Human–AI Alignment | 100% (simulated) |
| Predicted Departments | 7 |
| Average Response Clarity | Consistent and polite |
| Compliance Incidents | 0 (demo) |

All outputs are synthetic but structured identically to a real civic workflow.

---

## Repository Contents

| File | Description |
|------|--------------|
| `CivicFlow_AI_Prototype.ipynb` | Main notebook showing the full demo |
| `data/civicflow_predictions_demo.json` | AI-classified outputs |
| `data/civicflow_feedback_demo.csv` | Human review log |
| `docs/Candidate_Product_Specification_Memo_Cherukuru.pdf` | Original memo |
| `docs/Screenshots/` | Example outputs and dashboards |

---

## Next Steps

- Integrate with real public records data (via city OnBase or 311 system).
- Fine-tune with staff-reviewed examples to improve model precision.
- Add a Phase 3 citizen-facing portal for self-service search.
- Deploy under Responsible AI and accessibility guidelines.

---

## Contact

**Swaapnika Chowdary Cherukuru**  
Master of Science | Northeastern University  
cherukuru.sw@northeastern.edu | swaapnic@gmail.com
| https://www.linkedin.com/in/swaapnika-cherukuru-926990228/

