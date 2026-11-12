# Shadman Mahmood Khan Pathan

**PhD Candidate in Electrical & Computer Engineering, Old Dominion University. Defense completed November 5, 2026; degree conferral expected December 2026.**  
**Research and engineering:** LLM evaluation, calibration under distribution shift, adversarial robustness, and privacy-preserving computation.

I build **reproducible Python/PyTorch experiments** to test when model improvements and safety claims survive appropriate controls. My research-scale LoRA/DPO audit examines response-length effects in apparent reward gains; my ToxicChat work studies safety-judge reliability under jailbreak shift, with a reproducible CPU baseline and per-example evidence. Related work covers model-selection uncertainty, adversarial robustness and CKKS-based encrypted scoring. My first-author ICNC 2026 paper is published; three first-author ICLR 2027 manuscripts remain under review. My background combines doctoral research with airline flight operations experience.

## Selected work

| Project | What is implemented / established |
|---|---|
| [Repo Doctor: repository-audit prototype](https://github.com/Shadman19/repo-doctor) | The main branch is a fixed audit/report pipeline for possible-secret pattern scans, dependency auditing, license/SBOM tooling and SARIF/PDF reports. The [**v2 open PR**](https://github.com/Shadman19/repo-doctor/pull/1) contains proposed human-reviewed remediation and optional Bedrock Converse integration, with model-output validation and a synthetic benchmark; *not merged or tested against live AWS*. |
| [DPO reliability and safety-judge audit](https://github.com/Shadman19/dpo-reliability-audit) | Research-scale LoRA/DPO experiments with Qwen2.5-0.5B-Instruct, response-length controls and a ToxicChat safety-judge study. The public CPU baseline includes frozen calibration/threshold choices, per-example scores, subgroup uncertainty and overlap sensitivity analysis. |
| [Encrypted scoring and calibration experiments](https://github.com/Shadman19/encrypted-calibration-fhe) | CKKS and polynomial-approximation research associated with an IEEE ICNC 2026 paper. The reviewed MIMIC notebook demonstrates encrypted dot-product scoring followed by decryption and plaintext NumPy adaptation; implementation boundaries are documented per notebook. |
| [Scalable LLM engine](https://github.com/Shadman19/scalable-llm-engine) | Demonstration of a model-serving gateway with routing, Redis caching/queues, Docker/Kubernetes, health checks and autoscaling. *Research/engineering prototype, not a claimed production deployment.* |
| [NIST updates](https://github.com/Shadman19/nist-updates) | Prototype workflow for monitoring NIST SP 800 guidance and preparing auditable engineering updates. |
| [MedRAG clinical QA](https://github.com/Shadman19/medrag-clinical-qa) | Evidence-grounded retrieval and generation prototype with source-cited responses. |
| [MPRA cross-assay audit](https://github.com/Shadman19/mpra-cross-assay-audit) | Cardiac regulatory-variant / foundation-model reliability analyses with assay-aware controls and failure reporting; no claimed clinical validation or proven uncertainty-filtering benefit. |

## Research focus

- **Security and evaluation:** adversarial machine learning, model/attacker separation, LLM judge calibration, confidence and reliability under distribution shift.
- **Privacy-preserving learning:** CKKS-based encrypted scoring, calibration experiments, federated/heterogeneous learning and LoRA-based adaptation.
- **Biomedical and scientific ML:** ECG reliability and lead reconstruction, clinical NLP, medical imaging, cancer genomics and cardiac variant uncertainty.
- **ML systems:** PyTorch, Python, Linux/HPC/Slurm, FastAPI, Redis, Docker, Kubernetes and reproducible experiment pipelines.

**Peer-reviewed selected work:** privacy-preserving post-deployment calibration (IEEE ICNC 2026); false-negative induction in brain-tumor segmentation (IEEE ICCIT 2023); cardiovascular disease risk ML comparison (JILSA 2024).

**Manuscripts under review:** first-author ICLR 2027 submissions on encrypted-output probability reliability, disagreement-aware model-selection uncertainty and graph-transformer robustness. *Under review is not acceptance.*

## Collaboration and contact

I am interested in research-engineering and applied-scientist work on model evaluation, calibration and reliability, with explicit attention to implementation and deployment constraints.

[Research portfolio](https://shadman-portfolio.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/shadmanmahmood9/) · [Google Scholar](https://scholar.google.com/citations?user=zpxbdEEAAAAJ) · [Email](mailto:spath004@odu.edu)

<sub>Documentation distinguishes completed code and observed results from proposals, submissions, and unvalidated deployment claims.</sub>
