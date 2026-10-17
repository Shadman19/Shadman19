# Shadman Mahmood Khan Pathan

**PhD Candidate, Electrical & Computer Engineering — Old Dominion University (expected Fall 2026)**  
**Research and engineering:** trustworthy ML, AI security/evaluation, privacy-preserving learning, biomedical AI, and scalable LLM systems.

I develop **reproducible ML experiments and working software prototypes**, with particular attention to when model improvements, uncertainty estimates, or safety claims do **not** survive appropriate controls. My background combines doctoral research with operational analytics experience in airline flight operations.

## Selected work

| Project | What is implemented / established |
|---|---|
| [Repo Doctor: code-risk and remediation agent](https://github.com/Shadman19/repo-doctor) | Security scanning, redacted findings, SARIF/PDF reporting and human-reviewed remediation. [**v2 open PR**](https://github.com/Shadman19/repo-doctor/pull/1) adds an optional Bedrock Converse integration, model-output validation and a reproducible synthetic benchmark; *not merged or tested against live AWS*. |
| [DPO reliability audit](https://github.com/Shadman19/dpo-reliability-audit) | LoRA/DPO experiments with Qwen2.5-0.5B-Instruct, 5,000 UltraFeedback pairs and a beta sweep. Audited how reward-model scores can rise with response length while other quality measures worsen. |
| [Encrypted calibration with FHE](https://github.com/Shadman19/encrypted-calibration-fhe) | CKKS and polynomial-approximation experiments for privacy-preserving model calibration; connected to an IEEE ICNC 2026 peer-reviewed paper. |
| [Scalable LLM engine](https://github.com/Shadman19/scalable-llm-engine) | Demonstration of a model-serving gateway with routing, Redis caching/queues, Docker/Kubernetes, health checks and autoscaling. *Research/engineering prototype, not a claimed production deployment.* |
| [NIST updates](https://github.com/Shadman19/nist-updates) | Prototype workflow for monitoring NIST SP 800 guidance and preparing auditable engineering updates. |
| [MedRAG clinical QA](https://github.com/Shadman19/medrag-clinical-qa) | Evidence-grounded retrieval and generation prototype with source-cited responses. |
| [MPRA cross-assay audit](https://github.com/Shadman19/mpra-cross-assay-audit) | Cardiac regulatory-variant / foundation-model reliability analyses with assay-aware controls and failure reporting; no claimed clinical validation or proven uncertainty-filtering benefit. |

## Research focus

- **Security and evaluation:** adversarial machine learning, model/attacker separation, LLM judge calibration, confidence and reliability under distribution shift.
- **Privacy-preserving learning:** CKKS encrypted calibration, federated/heterogeneous learning and LoRA-based adaptation.
- **Biomedical and scientific ML:** ECG reliability and lead reconstruction, clinical NLP, medical imaging, cancer genomics and cardiac variant uncertainty.
- **ML systems:** PyTorch, Python, Linux/HPC/Slurm, FastAPI, Redis, Docker, Kubernetes and reproducible experiment pipelines.

**Peer-reviewed selected work:** privacy-preserving post-deployment calibration (IEEE ICNC 2026); false-negative induction in brain-tumor segmentation (IEEE ICCIT 2023); cardiovascular disease risk ML comparison (JILSA 2024).

**Manuscripts under review:** first-author ICLR 2027 submissions on encrypted-output probability reliability, disagreement-aware model-selection uncertainty and graph-transformer robustness. *Under review is not acceptance.*

## Collaboration and contact

I am interested in applied-scientist, research-engineering and ML systems roles where experimental rigor and deployed-system constraints meet.

[Research portfolio](https://shadman-portfolio.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/shadmanmahmood9/) · [Google Scholar](https://scholar.google.com/citations?user=zpxbdEEAAAAJ) · [Email](mailto:spath004@odu.edu)

<sub>Documentation distinguishes completed code and observed results from proposals, submissions, and unvalidated deployment claims.</sub>
