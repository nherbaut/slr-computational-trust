---
schema: paper-monitor/paper/v1
paper_id: 5508
record_type: PAPER
bibliography:
  title: Trust-Aware Task Allocation With Quantum Optimization in Adversarial Multi-Agent Systems
  authors: Giselle Roman Barroso, Duy H. Ho, Luke Miller, Ahmed Alanazi, Yugyung Lee
  abstract: Autonomous multi-agent robotic systems are increasingly deployed in safety-critical domains where human access
    is limited and rapid coordination is essential. However, their autonomy also exposes them to cyber-physical attacks such
    as GPS spoofing, misinformation, and communication failures, which can erode inter-agent trust and destabilize mission
    outcomes. To address this challenge, we present a trust-aware task allocation framework that explicitly models dynamic
    trust degradation and recovery in adversarial environments. The allocation problem is formulated as a Quadratic Unconstrained
    Binary Optimization (QUBO) and solved using the NEAL simulated annealing sampler, enabling global reasoning over urgency,
    trust, and interdependent task constraints. The framework is evaluated under diverse adversarial conditions, including
    fake high-priority tasks, blocked pathways, urgency decay, and communication disruptions, with defenses such as trust-based
    curing and urgencyweighted penalties. Across $\mathbf{1 0 0}$-round simulations, QUBO-based solvers preserved up to 91%
    final trust under attack compared to only 29% for Greedy heuristics, and sustained 24.2% task completion despite widespread
    spoofing, where Greedy completed none. These results demonstrate that explicitly integrating trust with global optimization
    provides a robust foundation for resilient multi-agent coordination in adversarial, uncertain, and safetycritical environments.
  publisher: IEEE International Conference on Data Mining Workshops Icdmw
  published_on: '2025-11-12'
  doi: 10.1109/icdmw69685.2025.00348
links:
  source: https://doi.org/10.1109/icdmw69685.2025.00348
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

