---
schema: paper-monitor/paper/v1
paper_id: 5585
record_type: PAPER
bibliography:
  title: 'Explainable Machine-Learning Forecasts of Building-Energy Demand from Weather Signals: A Comparative Study of Classical,
    Ensemble and Hybrid DL Models'
  authors: Antar Chandra Das, Md. Anik Chowdhury, Mohammad Rifat Ahmmad Rashid, Md Hossen, Raiyan Gani, Rahin Arefin Ahmed,
    Karib Shams
  abstract: 'Accurate yet transparent forecasting of building-energy demand is a prerequisite for demand-response programmes
    and Net-Zero-Energy targets. This study proposes an explainable machine-learning pipeline that learns weather-load relationships
    from four years of hourly data collected in two commercial buildings and compares classical, ensemble, and hybrid deep-learning
    models. We begin with a statistical exploration-Pearson correlation, $t$ tests, and ANOVA-to quantify how sky radiation,
    temperature indices, and precipitation alter demand. Seven predictors are then benchmarked: Linear Regression, Decision
    Tree, K-Nearest Neighbours, Random Forest, XGBoost, LightGBM, and a CNN-LSTM hybrid. Random Forest achieves the best accuracy
    ( $R^{2}=0.8737$, RMSE = 0.077kWh), followed by XGBoost and LightGBM, while the CNN-LSTM slightly underperforms on this
    medium-sized tabular data. To bridge the “black-box” gap, SHAP global explanations show that short-wave radiation (ALLSKY),
    cooling-degree days, and maximum temperature dominate the predictions, whereas LIME provides hour-level rationales for
    individual forecasts. Together, these insights enable facility managers to trust model outputs, identify energy-intensive
    weather regimes, and prioritise control actions. The comparative results, open workflow, and public code repository furnish
    a reproducible baseline for future cross-climate studies and illustrate how explainable AI can accelerate the operational
    uptake of data-driven energy forecasting in buildings.'
  publisher: 2025 IEEE International Conference on Quantum Photonics Artificial Intelligence and Networking Qpain 2025
  published_on: '2025-07-31'
  doi: 10.1109/qpain66474.2025.11172015
links:
  source: https://doi.org/10.1109/qpain66474.2025.11172015
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

