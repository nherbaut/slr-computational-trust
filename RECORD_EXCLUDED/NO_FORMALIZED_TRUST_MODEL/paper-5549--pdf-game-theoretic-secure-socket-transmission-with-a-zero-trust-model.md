---
schema: paper-monitor/paper/v1
paper_id: 5549
record_type: PAPER
bibliography:
  title: '[PDF] Game-Theoretic Secure Socket Transmission with a Zero Trust Model'
  authors: Evangelos D. Spyrou, Vassilios Kappatos, Chrysostomos Stylios
  abstract: A significant problem in cybersecurity is to accurately detect malicious network activities in real-time by analyzing
    patterns in socket-level packet transmissions. This challenge involves distinguishing between legitimate and adversarial
    behaviors while optimizing detection strategies to minimize false alarms and resource costs under intelligent, adaptive
    attacks. This paper presents a comprehensive framework for network security by modeling socket-level packet transmissions
    and extracting key features for temporal analysis. A long short-term memory (LSTM)-based anomaly detection system predicts
    normal traffic behavior and identifies significant deviations as potential cyber threats. Integrating this with a zero
    trust signaling game, the model updates beliefs about agent legitimacy based on observed signals and anomaly scores. The
    interaction between defender and attacker is formulated as a Stackelberg game, where the defender optimizes detection
    strategies anticipating attacker responses. This unified approach combines machine learning and game theory to enable
    robust, adaptive cybersecurity policies that effectively balance detection performance and resource costs in adversarial
    environments. Two baselines are considered for comparison. The static baseline applies fixed transmission and defense
    policies, ignoring anomalies and environmental feedback, and thus serves as a control case of non-reactive behavior. In
    contrast, the adaptive non-strategic baseline introduces simple threshold-based heuristics that adjust to anomaly scores,
    allowing limited adaptability without strategic reasoning. The proposed fully adaptive Stackelberg strategy outperforms
    both partial and discrete adaptive baselines, achieving higher robustness across trust thresholds, superior attacker–defender
    utility trade-offs, and more effective anomaly mitigation under varying strategic conditions.
  publisher: Applied Sciences Switzerland.
  published_on: '2025-09-29'
  doi: 10.3390/app151910535
links:
  source: https://doi.org/10.3390/app151910535
  open_access: https://www.mdpi.com/2076-3417/15/19/10535/pdf?version=1759139817
source:
  logical_feed_id: 26
  logical_feed_name: SLR UPDATE
  feed_id: 34
  feed_name: Miage Scholar Import 2026-05-13:17:44:27 RSS
  discovered_at: '2026-05-13T15:44:51.808140Z'
workflow:
  state:
    id: RECORD_EXCLUDED/NO_FORMALIZED_TRUST_MODEL
    label: No formalized trust model
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

