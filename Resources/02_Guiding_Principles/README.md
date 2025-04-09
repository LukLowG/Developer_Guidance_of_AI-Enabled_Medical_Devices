# Guiding Principles for AI/ML-Based Software as a Medical Device (SaMD)

This summary consolidates key information from the FDA's guiding principles documents on Good Machine Learning Practices (GMLP), Transparency, and Predetermined Change Control Plans (PCCP) for AI/ML-enabled medical devices. These principles are designed to support the safe and effective development, implementation, and oversight of AI-based Software as a Medical Device (SaMD).

---

## 1. Good Machine Learning Practice (GMLP)

### Core Principles

1. **Multidisciplinary Expertise**: Involve cross-functional teams from the beginning.
2. **Clinical Relevance**: Ensure that data is relevant and representative of the target population.
3. **Data Quality and Integrity**: Use high-quality, curated datasets with proper data management.
4. **Training and Testing Independence**: Separate data used for training from that used for testing.
5. **Performance Metrics**: Use clinically meaningful metrics and evaluate across relevant subgroups.
6. **Human-AI Teaming**: Evaluate the performance of both the AI and the human-AI team.
7. **Test for Relevance**: Validate under clinically representative conditions.
8. **Risk Management**: Incorporate software risk management practices throughout the lifecycle.
9. **Transparency**: Provide users with clear, essential information about the model and its outputs.
10. **Monitoring**: Establish monitoring procedures to address model performance over time.

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

---

## 3. Predetermined Change Control Plans (PCCP)

### Purpose

Enable proactive updates to AI models without requiring a new submission, while maintaining safety and effectiveness.

### 🧱 Structure of a PCCP

1. **Description of Modifications**: Detail what types of changes (e.g., retraining, threshold adjustment) are planned.
2. **Modification Protocol**:
   - Data management practices
   - Re-training/tracking processes
   - Performance evaluation procedures
3. **Impact Assessment**: Explain how safety and effectiveness will be ensured post-modification.

### Best Practices

- Include appropriate **statistical validation** and **bias control** methods.
- Provide **transparent documentation** on data handling and model evolution.
- Use **independent test data** to validate any changes before deployment.

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
