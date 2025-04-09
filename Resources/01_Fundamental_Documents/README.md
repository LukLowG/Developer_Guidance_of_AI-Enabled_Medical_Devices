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


## Total Product Lifecylce (TPLC) Regulatory Approach

This chapter introduces the FDA’s vision for a **regulatory framework that supports safe, effective, and continuously learning AI/ML-based SaMD throughout their entire lifecycle** — from development through deployment and postmarket evolution.

---

### Scope of the TPLC Approach

- **This regulatory framework applies only to AI/ML-based SaMD that require premarket submissions**, such as those under:
  - **510(k)**
  - **De Novo**
  - **Premarket Approval (PMA)**

- It does **not apply to Class I or Class II devices that are exempt from premarket review**.

---

### Why TPLC is Needed

- Traditional regulatory pathways are designed for **"locked" software** — software that doesn’t change once marketed.
- AI/ML-based SaMD, however, can **continuously learn and evolve** after deployment, potentially altering behavior and performance.
- The **TPLC model allows for continuous improvement** while ensuring that safety and effectiveness are maintained.

---

### Core Components of the TPLC Approach

#### 1. Quality Systems + Good Machine Learning Practices (GMLP)

- Developers are expected to adopt robust development and validation practices, including:
  - Data quality assurance
  - Transparent training/testing pipelines
  - Risk management strategies
  - Clear documentation

- These align with the **culture of quality and organizational excellence** promoted in the FDA’s **Digital Health Software Pre-Cert Program**.

---

#### 2. Premarket Review + Predetermined Change Control Plan (PCCP)

- Manufacturers can include a **PCCP** as part of the initial premarket submission.

- PCCP consists of two parts:
  - **SaMD Pre-Specifications (SPS)** – defines *what* changes are anticipated (e.g., retraining, new inputs)
  - **Algorithm Change Protocol (ACP)** – outlines *how* those changes will be made, validated, and monitored

---

#### 3. Ongoing Risk Management + Real-World Performance Monitoring

- After market authorization, manufacturers are expected to:
  - Monitor performance in real-world settings
  - Implement risk-based updates
  - Document and control changes consistent with the approved PCCP

---

#### 4. Transparency to Users and the FDA

- Continuous updates must be accompanied by:
  - Clear communication to users (e.g., updates, performance changes)
  - Updated labeling and instructions for use
  - Potential public reporting mechanisms

---

### FDA’s Vision

- Support a **flexible, innovation-friendly pathway** for adaptive AI/ML software
- Enable **safe, effective, and continually improving SaMD**
- Establish a **trustworthy, transparent, and risk-aware oversight system**
