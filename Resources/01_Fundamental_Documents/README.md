# Proposed Regulatory Framework for Modifications to Artificial

Intelligence/Machine Learning (AI/ML)-Based Software as a Medical Device
(SaMD) - Discussion Paper and Request for Feedback

## Introduction – Expanded Summary with SaMD Context

- What is SaMD?
  - Software as a Medical Device (SaMD) is defined as software intended to be used for medical purposes without being part of a hardware medical device.
  - This includes software that, for example:
    - Diagnoses conditions using imaging data.
    - Predicts risk of disease progression.
    - Supports clinical decisions.

  - The International Medical Device Regulators Forum (IMDRF) provides the commonly accepted framework for SaMD, which the FDA follows.

- Why SaMD Needs a New Approach with AI/ML

  - Traditional SaMD is typically “locked” — it doesn’t change after approval.
  - But AI/ML-based SaMD can continuously learn, improve, or drift in performance after deployment.
  - The FDA recognizes that this adaptive nature challenges current review pathways.

- First Discussion Paper proposes:

  - A Total Product Lifecycle (TPLC) approach to regulate AI/ML-based SaMD:
    - From initial development to real-world use and ongoing updates.

  - The aim is to ensure:

    - Safety and effectiveness are maintained over time.
    - Manufacturers can pre-plan certain modifications, reducing regulatory burden.
    - Patients and providers maintain trust and understanding in how the AI behaves.

## Types of AI/ML-Based SaMD Modifications

| **Modification Type** | **What Changes** | **Examples** | **Impact on Intended Use** | **Regulatory Implications** |
|------------------------|------------------|--------------|-----------------------------|-----------------------------|
| **1. Performance** | Clinical or analytical performance improves via retraining or architecture tweaks | - Re-training with new data to boost sensitivity<br>- Updating algorithm logic | No change | May not require premarket submission if risks are controlled; must be validated |
| **2. Inputs** | Type or source of data used by the model | - Support for new sensor type<br>- Adding a new data stream (e.g., oximetry) | No change | May need review depending on risk; validation is essential |
| **3. Intended Use** | Clinical purpose, population, or indication expands or shifts | - From “aid in diagnosis” → “diagnostic output”<br>- Adults → pediatric use<br>- Lung cancer → liver cancer | Yes — significant | Likely requires **new FDA submission** unless covered under an **approved PCCP** |

---

### 📎 Footnote: Link to PCCP (Predetermined Change Control Plan)

In later chapters, the FDA introduces the **PCCP** as a way for manufacturers to **pre-authorize certain future changes** to AI/ML-based SaMD. Each modification type listed above can be proactively addressed through:

- **SaMD Pre-Specifications (SPS)** – outlines *what* changes are anticipated (e.g., performance tuning, new inputs).
- **Algorithm Change Protocol (ACP)** – explains *how* these changes will be developed, validated, and safely implemented.

If a modification falls within a pre-approved **PCCP**, it **may not require a new FDA submission**, streamlining updates while maintaining oversight and safety.
