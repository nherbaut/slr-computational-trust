---
schema: paper-monitor/paper/v1
paper_id: 5868
record_type: PAPER
bibliography:
  title: '[PDF] Version-Wide Software Birthmark via Machine Learning'
  authors: Chih-Ko Chung, Pi‐Chung Wang
  abstract: Identifying the credibility of executable files is critical for the security of an operating system. Modern operating
    systems rely on code signing, which uses a default-valid trust model, for executable files to identify their publishers.
    A malware could pass software validation of operating systems and security software by using counterfeit code-signing
    certificates. Although the counterfeit certificates can be revoked by CAs, the previous research showed that the revocation
    delay takes as long as 5.6 months. In this paper, we attempt to identify the credibility of software with multiple-version
    executable files without relying on public key infrastructure (PKI), where a new-version executable file is usually developed
    incrementally based on the previous versions. The sharing features among different versions can be extracted for identifying
    the software. Accordingly, we present a software-birthmark scheme to serve our purpose. Our scheme generates a cross-version
    software birthmark for executable files of the same software. The proposed software birthmark is a binary-classification
    model of a machine learning algorithm based on imported and exported function names extracted from different-version executable
    files. To evaluate the performance of version-wide software birthmarks, our experiments include 138 versions of Windows
    kernel32.dll and 545 versions of firefox.exe. We also use multiple machine learning algorithms for performance comparisons.
    The results show that proposed software birthmark can effectively identify the derivations of these executable files.
    The proposed software birthmark can be used by operating systems or security software to evaluate the credibility of executable
    files with suspicious certificates.
  publisher: IEEE Access.
  published_on: '2021-01-01'
  doi: 10.1109/access.2021.3103186
links:
  source: https://doi.org/10.1109/access.2021.3103186
  open_access: https://ieeexplore.ieee.org/ielx7/6287639/6514899/09509024.pdf
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

