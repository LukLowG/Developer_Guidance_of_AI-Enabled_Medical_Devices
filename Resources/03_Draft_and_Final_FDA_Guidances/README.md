# FDA Final Guidance on PCCPs for AI-Enabled Device Software Functions

## Section Summary: Scope

This document summarizes the **Scope** section of the FDA's final guidance on **Predetermined Change Control Plans (PCCPs)** for AI-enabled device software functions (AI-DSFs), issued December 2024.

---

## What Devices Are Covered?

This guidance applies to **AI-Enabled Device Software Functions (AI-DSFs)** that manufacturers intend to **modify over time**. This includes:

- Devices using **machine learning (ML)** or other artificial intelligence (AI) techniques
- **Automatically updating** systems (e.g., continuous learning)
- **Manually updated** systems (e.g., human-in-the-loop decision-making)
- Devices submitted through:
  - **Premarket Approval (PMA)**
  - **510(k) Notification**
  - **De Novo Classification**

---

## What the Guidance Includes

A **PCCP** is intended to authorize changes that would typically require a new submission, including:

- **Significant modifications** that could:
  - Affect the **safety** or **effectiveness** of the device
  - Change its **intended use**

These changes must be:

- Clearly defined in the **Description of Modifications**
- Verified and validated per the **Modification Protocol**
- Assessed through a formal **Impact Assessment**

---

## What the Guidance Excludes

This guidance does **not cover**:

- Minor modifications that **do not require a new marketing submission**
- Changes managed under the **Quality System Regulation (QSR)**, which must:
  - Be documented in the **Device Master Record**
  - Be included in **post-approval reports** (if applicable to PMAs)

---

## Combination Products

For **device-led combination products** (e.g., AI device combined with a drug or biologic):

- The guidance **applies only** to the **device software** component (AI-DSF)
- It does **not apply** to the **drug or biologic** constituents
- **Early FDA engagement** is recommended, especially if changes affect the combination product as a whole

---

## Implementation Highlights

- An **authorized PCCP** allows for pre-approved changes to be made **without**:
  - Re-submitting for a PMA supplement
  - Filing a new 510(k) submission
- This approach **streamlines iterative development** of AI-enabled devices while maintaining regulatory oversight

---

## FDA Recommendation

Manufacturers are **encouraged to engage early** with FDA using the **Q-Submission Program** to ensure:

- The scope of the PCCP is appropriate
- The evidence supports continued safety and effectiveness

## Section Summary: Definitions

This section defines key terms used throughout the guidance. Understanding these definitions is essential for interpreting FDA recommendations regarding PCCPs for AI-enabled medical device software.

---

## A. Software Functions

**Artificial Intelligence (AI)**  
A machine-based system that, for a given set of human-defined objectives, can make predictions, recommendations, or decisions influencing real or virtual environments.

**Machine Learning (ML)**  
A subset of AI consisting of techniques that improve performance on a task through exposure to data.

**Device Software Function (DSF)**  
A software function that meets the definition of a medical device under section 201(h) of the FD&C Act. It can be:

- Software as a Medical Device (SaMD)
- Software in a Medical Device (SiMD)

**Artificial Intelligence-Enabled Device Software Function (AI-DSF)**  
A DSF that implements an AI model. AI-DSFs are the primary focus of this guidance.

---

## B. Data Sets

**Training Data**  
Data used to build the AI model (e.g., setting weights or connections).

- Should represent the intended use population and environment.

**Tuning Data**  
Used to evaluate a small number of trained models during development (e.g., for hyperparameter optimization).

- FDA avoids using the term "validation" for this purpose to prevent confusion with clinical validation.

**Test Data**  
Used to characterize and validate model performance post-training.

- Should be independent from training and tuning data.
- Should represent the target population and use environment.
- Should be sourced from multiple sites when possible.

---

## C. Predetermined Change Control Plan (PCCP)

**Predetermined Change Control Plan (PCCP)**  
Documentation describing:

- What modifications are planned
- How they will be implemented and assessed  
Includes:

1. Description of Modifications  
2. Modification Protocol  
3. Impact Assessment

**Authorized PCCP**  
A PCCP that has been reviewed and accepted as part of an FDA marketing authorization. It becomes a technological characteristic of the authorized device.

**Modification Protocol**  
A detailed procedure for implementing, verifying, and validating modifications described in the PCCP. Includes predefined acceptance criteria.

**Impact Assessment**  
An analysis of the risks and benefits associated with the planned modifications, along with proposed mitigation strategies.
