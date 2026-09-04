---
schema: paper-monitor/paper/v1
paper_id: 5882
record_type: PAPER
bibliography:
  title: '[PDF] BlockFLow: An Accountable and Privacy-Preserving Solution for Federated Learning'
  authors: Vaikkunth Mugunthan, Ravi Rahman, Lalana Kagal
  abstract: Federated learning enables the development of a machine learning model among collaborating agents without requiring
    them to share their underlying data. However, malicious agents who train on random data, or worse, on datasets with the
    result classes inverted, can weaken the combined model. BlockFLow is an accountable federated learning system that is
    fully decentralized and privacy-preserving. Its primary goal is to reward agents proportional to the quality of their
    contribution while protecting the privacy of the underlying datasets and being resilient to malicious adversaries. Specifically,
    BlockFLow incorporates differential privacy, introduces a novel auditing mechanism for model contribution, and uses Ethereum
    smart contracts to incentivize good behavior. Unlike existing auditing and accountability methods for federated learning
    systems, our system does not require a centralized test dataset, sharing of datasets between the agents, or one or more
    trusted auditors; it is fully decentralized and resilient up to a 50% collusion attack in a malicious trust model. When
    run on the public Ethereum blockchain, BlockFLow uses the results from the audit to reward parties with cryptocurrency
    based on the quality of their contribution. We evaluated BlockFLow on two datasets that offer classification tasks solvable
    via logistic regression models. Our results show that the resultant auditing scores reflect the quality of the honest
    agents' datasets. Moreover, the scores from dishonest agents are statistically lower than those from the honest agents.
    These results, along with the reasonable blockchain costs, demonstrate the effectiveness of BlockFLow as an accountable
    federated learning system.
  publisher: arXiv.org.
  published_on: '2020-07-08'
  doi: null
links:
  source: https://openalex.org/W3042012704
  open_access: https://arxiv.org/pdf/2007.03856
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
  tags:
  - arxiv
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

