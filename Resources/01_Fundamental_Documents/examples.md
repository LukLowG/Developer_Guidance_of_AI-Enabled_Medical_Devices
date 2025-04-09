# 📘 Examples of AI/ML-Based SaMD with PCCPs

This document illustrates how the FDA’s PCCP (Predetermined Change Control Plan) approach can be applied to AI-enabled medical device software functions (AI-DSFs). The examples below are taken from real-world scenarios discussed in the FDA’s 2024 guidance and are meant to provide practical insight into how modifications may be handled across the product lifecycle.

---

## Example 1: Patient Monitoring Software

- **Function**: Analyzes patient vital signs in real-time to detect early signs of clinical deterioration.
- **PCCP Scope**:
  - Performance improvements based on new training data.
  - Updates to thresholds for alerts based on population-specific tuning.
- **Risk Control Measures**:
  - Continuous real-world monitoring.
  - Defined validation metrics in the Modification Protocol.

---

## Example 2: Skin Lesion Classification Software

- **Function**: Uses dermatological images to assist clinicians in classifying lesions as benign or malignant.
- **PCCP Scope**:
  - Retuning the model based on diverse skin tone datasets.
  - Adjusting sensitivity/specificity trade-offs.
- **Key Considerations**:
  - Emphasis on bias mitigation.
  - Transparent documentation of model limitations.

---

## Example 3: Ventilator Settings Optimization Software

- **Function**: Provides ventilator parameter suggestions based on patient respiratory metrics.
- **PCCP Scope**:
  - Performance updates based on ICU data across hospital networks.
  - Inclusion of new input parameters (e.g., lung compliance metrics).
- **Safety Measures**:
  - Guardrails on parameter changes.
  - Human-in-the-loop validation.

---

## Example 4: Image Acquisition Assistance Software

- **Function**: Assists in optimizing image acquisition parameters in radiological workflows.
- **PCCP Scope**:
  - Learning optimal parameters for new scanner types.
  - Adapting to different imaging protocols.
- **Challenges**:
  - Interoperability across devices.
  - Need for site-specific testing.

---

## Example 5: Radiograph Analysis for Feeding Tube Placement

- **Function**: Detects tube position in chest X-rays.
- **PCCP Scope**:
  - Expanded capability to detect more tube types.
  - Improved performance under different patient postures.
- **Performance Metrics**:
  - Localization accuracy.
  - False positive/negative rate thresholds.

---

## Example 6: Optical Imaging System with Imaging Drug

- **Function**: Combines a drug and an AI-enhanced imaging system to detect disease markers.
- **PCCP Scope**:
  - Enhancing software to interpret signals from newly approved imaging agents.
  - Calibrating model to adjust for variations in signal intensity.
- **Regulatory Complexity**:
  - Involves coordination across device-drug combination policies.
  - Early FDA engagement recommended.

---

## Note

Each example includes:

- **Description of planned modifications** (via the Description of Modifications section),
- **Defined validation procedures** (in the Modification Protocol),
- **Risk-benefit analysis** (in the Impact Assessment).

For detailed protocol components and validation methods, refer to **Appendix A** of the FDA's PCCP guidance.
