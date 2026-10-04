# Awesome-Clinical-AI-Documentation

# Awesome-Clinical-AI-Documentation



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Ambient Clinical Scribing, Medical Speech Recognition & Automated Note Generation*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Clinical AI Documentation**. These tools help clinicians automate medical documentation—capturing patient encounters, generating structured notes, and reducing administrative burden so providers can focus on patient care.



**Examples** include Microsoft DAX Copilot, Abridge, Suki AI, Ambience Healthcare, DeepScribe, Nabla, Augmedix, Sunoh.ai, Robin Healthcare, and Freed AI (the category leaders).



**Open-source emphasis**: Clinical AI documentation has an **emerging and research-focused open-source ecosystem**. The most significant project is **AI-Enhanced OpenEMR** from Indiana University, which demonstrates ambient clinical documentation integrated with the open-source OpenEMR EHR via SMART on FHIR at approximately **$0.02 per encounter**—a **98-99% cost reduction** versus commercial alternatives . **OpenScribe** provides a local-first AI scribe with AES-GCM encrypted storage and modular LLM providers . **MedASR** from Google Health is a Conformer-based medical speech recognition model achieving **4.6% WER** on radiology dictation . **DocuScribe AI** delivers an agent-based system with SOAP notes, ICD-10 coding, and FHIR R4 export . This section documents these focused solutions honestly.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## 📖 Table of Contents



- [☁️ SaaS/Hosted Platforms](#-saas-hosted-platforms)

- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)

- [🤝 How to Contribute](#-how-to-contribute)

- [⚠️ Disclaimer](#-disclaimer)



## ☁️ SaaS/Hosted Platforms



> **📊 Market Context**: The global AI-powered clinical documentation market is estimated at **~$5.16B in 2026**, growing toward **~$13.99B by 2030** at a **28.3% CAGR** . North America accounts for **50.16% of global value** due to large-scale EHR installations and clinical IT spending priorities . The sector is **moderately fragmented** — Abridge leads with **$5.3B valuation** and **$117M ARR**, while Suki, Nabla, DeepScribe, and Ambience each command significant enterprise segments . No single vendor holds a winner-take-all position; health systems typically pilot multiple vendors before standardizing.



| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |

|----------|-------------|------------------------|------------------|--------------|

| **[Abridge](https://www.abridge.com/)** | AI-powered conversation analysis generating structured clinical notes. Partners with NVIDIA and Eli Lilly. | **$199/physician/month** (Enterprise volume discounts available) . | **None** — no free tier or free trial publicly available. Enterprise demo required. | **$5.3B valuation, $117M ARR, ~$830M raised**  |

| **[Ambience Healthcare](https://www.ambiencehealthcare.com/)** | AI operating system for clinical documentation with coding integrity. Reduces documentation time by average **78%**. | **Not published** — enterprise quote required. Reported ROI of at least **5X** for health systems . | **None** — enterprise demo required. | **$1.25B valuation, ~$345M raised**  |

| **[Suki AI](https://suki.ai/)** | Voice-controlled AI assistant generating SOAP notes, H&P notes, and coding suggestions. | **Not published** — pricing requires sales contact. Depends on EHR, practice size, and support tier . | **Free tier available** for individual clinicians with limited volume (BAA requires paid plan) . | **$317.8M valuation, $26.5M revenue, $168M raised**  |

| **[Nabla](https://www.nabla.com/)** | AI clinical notes deployed in **over 130 health organizations**. Early access to Yann LeCun's world model technology via AMI. | **Not published** — paid plan requires demo. Free tier has volume limits. | **Free tier available** with volume limits; **BAA not confirmed** on free tier . | **$27.8M revenue, $131M raised**  |

| **[DeepScribe](https://www.deepscribe.ai/)** | AI scribe trained on the largest clinical dataset in healthcare. Ambiently captures visits and writes billable documentation. | **Not published** — enterprise quote required. | **None** — enterprise demo required. | **$14.6M revenue, $133 employees**  |

| **[Microsoft DAX Copilot](https://www.microsoft.com/en-us/health-solutions/clinical-workflow)** | AI documentation integrated with Microsoft Cloud for Healthcare and Epic. Ambient voice capture and note generation. | **$369/provider/month** flat rate + one-time implementation fee of **~$700/user** . | **None** — enterprise licensing through Microsoft Cloud for Healthcare. | **~$281B revenue (Microsoft FY2025)**  |

| **[Freed AI](https://www.getfreed.ai/)** | AI medical scribe for individual clinicians and small practices. Offers self-serve signup. | **Starter: $39/month** (40 notes); **Core: $79/month** (unlimited); **Premier: $119/month** (EHR push, coding) . | **7-day free trial** on Premier with full functionality, no billing info required . | **~$19M ARR (est.), private**  |

| **[Sunoh.ai](https://www.sunoh.ai/)** | EHR-agnostic AI medical scribe available on mobile devices. Generates draft clinical summaries and SOAP notes. | **Starting at $149/month** (usage-based) . | **Free trial available** — details require sales contact. | **Private (Sunoh.ai)**  |

| **[Augmedix](https://www.augmedix.com/)** | AI-enabled medical documentation with human-in-the-loop MDS support. Products include Augmedix Live, Notes, Prep, and Go. | **Not published** — enterprise quote required. | **None** — enterprise demo required. | **~$53.2M revenue (2024 est.), acquired by Commure (2024)**  |

| **[Robin Healthcare](https://www.robinhealthcare.com/)** | AI-enabled medical scribe and back-office automation. Robin Assistant observes visits and uploads notes with codes to EHR. | **Not published** — enterprise quote required. | **None** — enterprise demo required. | **$82M raised, loan stage**  |



## 🔓 Open-Source GitHub Projects



Sorted by star count (descending). Star badge links to each repo's stargazers page.



| Repo | Description | Stars |

|---|---|---|

| **[MedASR (Google Health)](https://github.com/Google-Health/medasr)** — Conformer-based medical speech recognition model trained on **~5000 hours** of physician dictation. Achieves **4.6% WER** on radiology dictation, outperforming Whisper v3 Large (25.3%) and Gemini 2.5 Pro (10.0%). Apache-2.0 (repo code); Health AI Developer Foundations License (model). | [![Stars](https://img.shields.io/github/stars/Google-Health/medasr?style=social&color=white)](https://github.com/Google-Health/medasr/stargazers) | ~124 |

| **[OpenScribe](https://github.com/sammargolis/OpenScribe)** — Local-first AI scribe with **AES-GCM encrypted browser storage**, modular LLM providers (Anthropic, local Ollama), and Whisper transcription. No analytics or telemetry. Includes **MedGemma local text-only scribe** pipeline. | [![Stars](https://img.shields.io/github/stars/sammargolis/OpenScribe?style=social&color=white)](https://github.com/sammargolis/OpenScribe/stargazers) | ~50 |

| **[DocuScribe AI](https://github.com/abh2050/docu_scribe_ai)** — Agent-based clinical documentation system. Transcribes conversations, extracts medical concepts, generates SOAP notes, suggests ICD-10 codes, and exports **FHIR R4** compatible data. Multi-provider LLM support (OpenAI, Google, Anthropic). UMLS API integration. | [![Stars](https://img.shields.io/github/stars/abh2050/docu_scribe_ai?style=social&color=white)](https://github.com/abh2050/docu_scribe_ai/stargazers) | ~30 |

| **[clinical-note-generator](https://github.com/kennedyraju55/clinical-note-generator)** — HIPAA-friendly clinical note generator using **local Gemma 3 LLM via Ollama**. No patient data leaves the machine. FastAPI + Streamlit. Extracts vitals, medications, and assessments automatically. MIT License. | [![Stars](https://img.shields.io/github/stars/kennedyraju55/clinical-note-generator?style=social&color=white)](https://github.com/kennedyraju55/clinical-note-generator/stargazers) | ~15 |

| **[FLWhisper](https://github.com/leestott/FLWhisper)** — Privacy-first medical transcription using **Microsoft AI Foundry Local + Whisper medium**. 100% local processing, HIPAA-compliant, no cloud required. OpenAI-compatible REST API endpoint. ASP.NET Core 10. Includes 8 pre-recorded medical interview samples. | [![Stars](https://img.shields.io/github/stars/leestott/FLWhisper?style=social&color=white)](https://github.com/leestott/FLWhisper/stargazers) | ~10 |

| **[AI-Enhanced OpenEMR](https://github.com/iupui-soic/openemr-ai)** — **Reference implementation** of ambient clinical documentation integrated with **OpenEMR** via SMART on FHIR and serverless GPU pipeline. Achieves **~$0.02 per encounter** — **98-99% cost reduction** versus commercial alternatives. HIPAA-compliant on-premises deployment. No audio or PHI shared with vendor. Supported by SEIRI Seed Grant (Indiana University Indianapolis, 2025-2027). | [![Stars](https://img.shields.io/github/stars/iupui-soic/openemr-ai?style=social&color=white)](https://github.com/iupui-soic/openemr-ai/stargazers) | ~5 |



**Additional open-source options worth exploring:**



| Repo | Description |

|---|---|

| **[Synthetic Clinical Dialogue Dataset](https://zenodo.org/records/19986637)** — **~1,700 validated synthetic doctor-patient dialogue and SOAP summary pairs** generated with GPT-4o-mini + RAG over medical guidelines. Formats for Phi-3.5-mini, Llama-3.2-3B, and Llama-3.2-1B. For research in clinical NLP and knowledge distillation. | [![Zenodo](https://img.shields.io/badge/Zenodo-Dataset-blue)](https://zenodo.org/records/19986637) |

| **[medasr-model-card](https://developers.google.com/health-ai-developer-foundations/medasr/model-card)** — Full model card for Google's MedASR with training data details, performance evaluations, and safety assessments. | [![Google](https://img.shields.io/badge/Google-Health%20AI-blue)](https://developers.google.com/health-ai-developer-foundations/medasr/model-card) |



## 🤝 How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## ⚠️ Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Clinical AI documentation platforms handle **protected health information (PHI)** and are subject to **HIPAA**, **GDPR**, and FDA guidance on clinical decision support software. Ensure proper BAAs, audit logs, and compliance before deployment.

- **Open-source reality**: The open-source ecosystem for clinical AI documentation is **emerging and research-focused**. **AI-Enhanced OpenEMR** is the standout—a validated reference implementation achieving **$0.02 per encounter** (98-99% cost reduction) with full on-premises HIPAA compliance . **OpenScribe** provides a local-first AI scribe with encrypted storage . **MedASR** delivers production-grade medical speech recognition with **4.6% WER** on radiology dictation . However, **commercial platforms** (Abridge, Suki, Ambience, Microsoft DAX Copilot) provide **enterprise-grade integrations, proven deployments at major health systems, and dedicated support** that open-source alternatives require significant institutional investment to match. The open-source path is **genuinely viable** for **research institutions, FQHCs, and organizations with strong engineering capacity** seeking full data sovereignty and cost reduction.



---



**Made for clinicians, clinical informaticists, healthcare AI researchers, and health system IT teams.**

Let's make clinical documentation more open, efficient, and clinician-friendly.
