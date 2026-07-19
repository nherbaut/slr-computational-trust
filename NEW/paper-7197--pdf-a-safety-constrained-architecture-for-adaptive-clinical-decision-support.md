---
schema: paper-monitor/paper/v1
paper_id: 7197
record_type: PAPER
bibliography:
  title: '[PDF] A Safety-Constrained Architecture for Adaptive Clinical Decision Support'
  authors: Kavishwa Wendakoon, Nirnaya Tripathi
  abstract: Abstract AI-assisted clinical decision support systems (CDSS) increasingly incorporate adaptive and generative
    components to personalize recommendations and improve workflow efficiency. However, runtime adaptation in safety-critical
    clinical settings introduces significant governance challenges, including loss of predictability, unclear accountability,
    and limited auditability of system behavior over time. Existing CDSS architectures largely focus on model performance
    or explainability, while providing insufficient support for governing how and when adaptive changes are permitted in practice.
    This paper presents a safety-constrained self-adaptive software architecture for AI-assisted CDSS that enables bounded
    personalization while preserving clinician authority, patient safety, and regulatory accountability. Following a Design
    Science Research methodology, we design and iteratively refine an architecture based on a MAPE-K control loop augmented
    with an explicit Constraint Layer. The constraint layer enforces an adaptation boundary through bounded parameter updates,
    multi-clinician validation gates, evidence anchoring with contradiction checks, and auditable change records with versioning
    and rollback. We instantiate the architecture in a nurse-led triage-to-disposition workflow, modeling escalation paths
    and safety gates as an explicit state machine, and demonstrate interoperability via SMART on FHIR-style interfaces that
    exchange clinical context while keeping adaptation logic and governance mechanisms internal to the system. A formative
    stakeholder evaluation with clinicians indicates that the proposed approach improves perceived predictability, trust calibration,
    and confidence in oversight compared to unconstrained adaptive CDSS. The results suggest that governing adaptation, rather
    than restricting AI capability, is a key design strategy for deploying trustworthy, adaptive decision support in regulated
    digital health environments.
  publisher: Communications in Computer and Information Science.
  published_on: '2026-01-01'
  doi: 10.1007/978-3-032-28819-6_21
links:
  source: https://doi.org/10.1007/978-3-032-28819-6_21
  open_access: https://link.springer.com/content/pdf/10.1007/978-3-032-28819-6_21.pdf
source:
  logical_feed_id: 26
  logical_feed_name: SLR UPDATE
  feed_id: 34
  feed_name: Miage Scholar Import 2026-05-13:17:44:27 RSS
  discovered_at: '2026-07-05T04:34:19.188893Z'
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

