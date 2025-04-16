# Guiding Principles for AI/ML-Based Software as a Medical Device (SaMD)

This summary consolidates key information from the FDA's guiding principles documents on Good Machine Learning Practices (GMLP), Transparency, and Predetermined Change Control Plans (PCCP) for AI/ML-enabled medical devices. These principles are designed to support the safe and effective development, implementation, and oversight of AI-based Software as a Medical Device (SaMD).

---

## 1. Good Machine Learning Practice (GMLP)

### Core Principles

1. **Multidisciplinary Expertise Is Leveraged Throughout the Product Lifecycle**  
   *Example:* A company includes data scientists, software engineers, clinicians, and regulatory experts in the early planning stages of an AI-enabled diagnostic tool.

2. **Good Software Engineering and Security Practices Are Implemented**  
   *Example:* Developers use version control and unit testing frameworks and follow secure coding standards when building the device's backend AI system.

3. **Clinical Study Participants and Data Sets Are Representative of the Intended Patient Population**  
   *Example:* The training data for a cardiovascular AI tool includes patients of varying ages, sexes, races, and comorbidities from multiple geographic locations.

4. **Training and Test Data Are Independent**  
   *Example:* The training set for a skin cancer detection model is drawn from hospitals A, B, and C, while the testing set exclusively uses data from hospital D.

5. **Selected Reference Datasets Are Based Upon Best Available Methods**  
   *Example:* A diabetic retinopathy AI model is trained using images labeled by a panel of ophthalmologists with inter-rater agreement metrics documented.

6. **Model Design Is Tailored to the Available Data and Intended Use of the Device**  
   *Example:* A home-based respiratory monitoring system is designed using models robust to background noise and variations in patient posture.

7. **Focus Is Placed on the Performance of the Human-AI Team**  
   *Example:* In a clinical reader study, physicians using an AI radiology assistant show faster and more accurate diagnoses compared to physicians working alone.

8. **Testing Demonstrates Device Performance During Clinically Relevant Conditions**  
   *Example:* An AI system that monitors ICU patients is validated with real-time data from simulated ICU environments before clinical deployment.

9. **Users Are Provided Clear, Essential Information**  
   *Example:* The product includes a visual model card summarizing how the AI works, expected accuracy, confidence intervals, and known limitations.

10. **Deployed Models Are Monitored for Performance and Re-training Risks Are Managed**  
   *Example:* A manufacturer sets up automatic data drift detection and performance alerts to flag when their AI model needs retraining or human review.

---

## 2. Transparency Principles

### Key Areas

- **Intended Use Communication**: Clarify what the AI is intended to do and its role in clinical workflow.
- **Data Sources and Limitations**: Describe datasets, demographics, and known biases.
- **Performance Expectations**: Provide performance metrics (e.g., sensitivity, specificity, AUROC).
- **Human Factors**: Labeling and interfaces should support comprehension and safe use.
- **Model Updates**: Explain how and when the model will be updated.

### Recommendations

- Use **Model Cards**: Summarize model details in a consistent, user-friendly format.
- Address **subgroup performance**: Highlight any variability across demographics.
- Include **limitations** and conditions where the model may not perform well.

### Summary Table of Transparency Guiding Principles

| Guiding Principle | Description |
|-------------------|-------------|
| **Who** (Relevant audiences) | Transparency is relevant to all parties involved in a patient’s health care, including those intended to: <br>• Use or receive health care with the device <br>• Make decisions about the device to support patient outcomes |
| **Why** (Motivation) | Transparency supports: <br>• Safe and effective use <br>• Patient-centered care <br>• Evaluation of risks and benefits <br>• Informed decision-making <br>• Device maintenance <br>• Health equity via bias identification <br>• Adoption through user confidence |
| **What** (Relevant information) | Share information on: <br>• Device characterization and intended use <br>• Workflow integration and decision impact <br>• Performance, benefits, and risks <br>• Development and risk management activities <br>• Model logic (if explainable) <br>• Limitations, known biases, confidence intervals, and data gaps <br>• Lifecycle safety and effectiveness practices |
| **Where** (Placement of information) | Maximize the use of software interfaces to: <br>• Make information responsive, personalized, and adaptive <br>• Deliver content through varied modalities (e.g., text, alerts, visuals) |
| **When** (Timing of communication) | Timely communication should consider: <br>• Lifecycle stages <br>• Updates or discovered issues <br>• Workflow-triggered events or high-risk actions |
| **How** (Methods to support transparency) | Apply **human-centered design**: <br>• Tailor content detail and organization for target users <br>• Validate communication through iterative testing and usability evaluation |

---

## 3. Predetermined Change Control Plans (PCCP)

### Purpose

Predetermined Change Control Plans (PCCPs) enable manufacturers of ML-enabled medical devices to pre-authorize specific types of future changes — such as updates to an AI model — without submitting a new marketing application each time, as long as those changes fall within the bounds of the approved plan.

---

### Guiding Principles for PCCPs

The FDA outlines five key principles that a well-structured PCCP should follow:

#### 1. **Focused and Bounded**

- The PCCP must clearly define the scope and extent of anticipated modifications. These changes must remain within the originally authorized intended use.
- The plan should:
  - Limit modifications to what is explicitly described and justified.
  - Include safeguards (e.g., rollbacks or abort procedures) if a change fails validation.
  - Specify how impacts on device performance will be measured.
  
  *Example:* A PCCP may allow changes to a model's input weighting scheme but not permit adding new clinical features unless a new submission is filed.

#### 2. **Risk-Based**

- The PCCP should be developed using principles of risk management.
- Risk assessments must consider:
  - Each change's potential impact.
  - The accumulation of risk over multiple updates.
  - The environment in which the device is used.

  *Example:* A home-use device’s PCCP would account for different risks than a hospital-only tool due to variability in user expertise.

#### 3. **Evidence-Based**

- All changes implemented under a PCCP must be supported by scientific and clinical evidence.
- Performance metrics and validation methods must:
  - Be proportionate to the risks introduced.
  - Demonstrate safety and effectiveness both before and after the change.

  *Example:* If a model is retrained using a new data source, the evidence must include validation on a test set representative of the target population.

#### 4. **Transparent**

- The PCCP should include detailed plans for how updates and their impacts will be communicated to:
  - End users (e.g., clinicians, patients).
  - Regulatory authorities.
- Transparency applies across:
  - Data used for updates.
  - Test results before/after changes.
  - Performance monitoring and deviation handling.

  *Example:* Update summaries and performance dashboards are made available to users via the device UI or cloud portal.

#### 5. **Total Product Lifecycle (TPLC) Perspective**

- PCCPs should be designed and maintained with a long-term view across the entire lifecycle:
  - Integrating quality management systems (QMS).
  - Using postmarket surveillance data to refine future updates.
  - Ensuring continuity in safety and performance.

  *Example:* A PCCP might include periodic performance audits and feedback collection to inform both pre- and post-market improvements.

---

### PCCP Components

A complete PCCP typically includes the following sections:

#### 1. **Description of Modifications**

Defines what types of changes will be made and the rationale behind them.

#### 2. **Modification Protocol**

Details:

- When and how changes are triggered
- Data acquisition and preparation
- Model update workflows
- Testing and validation protocols
- Rollback mechanisms

#### 3. **Impact Assessment**

Describes how the manufacturer will evaluate:

- Whether the change maintains the device's safety and effectiveness
- Potential unintended effects or failure modes

---

### Benefits of Using a PCCP

- Streamlines regulatory interactions
- Enables faster model improvements
- Supports proactive risk mitigation
- Increases clinical and user confidence in adaptive systems

---

### Best Practices

- Maintain strong documentation and traceability
- Use representative data for validation
- Clearly communicate changes to all stakeholders
- Avoid scope creep — stay within the “focused and bounded” guardrails

---

## 4. Lifecycle Considerations for AI/ML SaMD

### TPLC Approach (Total Product Lifecycle)

FDA emphasizes continuous oversight and improvement:

- **Development**: Risk assessment, data curation, model design
- **Validation**: Independent testing, subgroup analysis
- **Deployment**: Clear labeling, usability evaluation
- **Monitoring**: Post-market surveillance and update management

---

## 5. Submission Considerations

| Section | Submission Content |
|--------|--------------------|
| Device Description | AI use, inputs/outputs, user environment |
| User Interface & Labeling | How the AI is accessed and understood |
| Risk Assessment | File including risk management plan and mitigation |
| Data Management | Representativeness, independence, cleaning methods |
| Model Description | Architecture, training, tuning, calibration |
| Validation | Performance metrics, study design, usability |
| Monitoring | Drift detection, update plans |
| Cybersecurity | Threat models, safeguards, risk controls |
| Public Summary | Transparent summary (e.g., model card) |

---

Last updated: April 2025
