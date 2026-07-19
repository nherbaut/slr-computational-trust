---
schema: paper-monitor/paper/v1
paper_id: 5565
record_type: PAPER
bibliography:
  title: 'Hybrid Anomaly Detection in Cyber-Physical Systems: Integrating Unsupervised Learning With Explainable AI'
  authors: Debjyoti Bose, Mridul Singh Rajput
  abstract: Abstract The rapid proliferation of cyber-physical systems (CPS) across critical industrial domains has heightened
    the demand for robust, interpretable, and scalable anomaly detection mechanisms to ensure system safety, availability,
    and operational resilience. Traditional anomaly detection approaches—particularly those relying solely on statistical
    or black-box models—often lack transparency, making it challenging for engineers and operators to trust model outputs
    or derive actionable conclusions. To address this limitation, the present study proposes a hybrid framework that integrates
    multiple unsupervised learning techniques with explainable artificial intelligence (XAI) tools to detect, interpret, and
    rank anomalies in CPS environments. The detection architecture combines LSTM Autoencoders, Isolation Forests, and K-Means
    clustering to identify deviations in multivariate sensor streams, typical of time-series CPS datasets. A dynamic model
    selection mechanism evaluates each detector using a balanced score composed of precision, recall, F1-score, and AUC-ROC,
    enabling adaptive selection of the best-performing model for further analysis. To ensure interpretability, we apply KernelSHAP
    and LIME to quantify the influence of individual features on anomaly decisions, offering both global importance and localized
    reasoning for each anomaly instance. To further enhance operational value, we introduce a novel severity scoring mechanism
    that aggregates SHAP impact values using PMIOE (Probability-weighted Mutual Information over Joint Entropy) weights. These
    weights reflect the systemic importance of each sensor feature based on its average dependency with other features, providing
    a mathematically grounded and data-driven severity ranking. Anomalies are categorized into high, moderate, or low impact
    based on percentile thresholds of their severity scores, and final outputs include structured, actionable insights combining
    SHAP explanations, PMIOE weights, and recommended maintenance priorities. The framework is validated on the FD001 subset
    of the C-MAPSS benchmark dataset, showing strong recall, reliable thresholding, and consistent interpretability across
    high-impact anomalies. Overall, this work bridges the gap between accurate anomaly detection and transparent, operationally
    actionable insight generation. It demonstrates the feasibility of combining unsupervised machine learning with information
    theory and XAI to create trustworthy monitoring systems for CPS, making it suitable not just for research, but for real-world
    deployment in high-stakes industrial settings.
  publisher: ASME International Mechanical Engineering Congress and Exposition Proceedings Imece
  published_on: '2025-09-10'
  doi: 10.1115/imece-india2025-160718
links:
  source: https://doi.org/10.1115/imece-india2025-160718
  open_access: null
source:
  logical_feed_id: 26
  logical_feed_name: SLR UPDATE
  feed_id: 34
  feed_name: Miage Scholar Import 2026-05-13:17:44:27 RSS
  discovered_at: '2026-05-13T15:44:51.808140Z'
workflow:
  state:
    id: NEW
    label: New
    prisma_bucket: null
  tags: [
    ]
  eligibility:
    exclusion: null
    inclusion:
      criteria: [
        ]
files:
  pdf:
    available: false
    name: null
    original_name: null
---

