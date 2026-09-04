---
schema: paper-monitor/paper/v1
paper_id: 5668
record_type: PAPER
bibliography:
  title: 'PERFEX-I: confidence scores for image classification using decision trees'
  authors: Thijs A. Eker, Ajaya Adhikari, Sabina B. van Rooij
  abstract: To be able to use machine learning models in practice, it is important to know when their predictions can be trusted.
    Confidence estimations can help end users to calibrate their trust, avoiding under- or over-reliance, and to decide when
    human interference is needed. In our work, we further develop the eXplainable AI (XAI) method PERformance EXplainer (PERFEX),
    which was originally proposed for tabular datasets. We adapt PERFEX such that it can be used to accurately estimate the
    image classifier confidence. This was done by applying the method on feature-reduced activation values of the last layer
    of image classification models. We coin this approach PERFEX-I. We show that PERFEX-I performs on par with existing methods
    for confidence estimation such as Temperature Scaling and Deep Ensembles. The Expected Calibration Error (ECE) on the
    ImageNet dataset is reduced from 6.83 to 1.71 for ResNet50 and from 8.84 to 1.44 for Swin-B compared to using the Softmax
    scores. Additionally, PERFEX-I groups images that may share common reasons for errors, and visual analysis of these groups
    can reveal patterns of the model’s behavior.
  publisher: Proceedings of SPIE the International Society for Optical Engineering
  published_on: '2024-11-13'
  doi: 10.1117/12.3049363
links:
  source: https://doi.org/10.1117/12.3049363
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

