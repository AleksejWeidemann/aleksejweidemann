# Aleksej Weidemann

**GenAI on Azure · RAG · EU AI Act · IT Project Management**

Düsseldorf, Germany · M.Sc. Big Data & Business Analytics (FOM, 1.9) · German, Russian, English

---

## About me

I build GenAI applications and take them live: document retrieval, prompts with clear rules, automated tests, container deployment on Azure and cost control.

I come from IT project management. At DSV Global Transport & Logistics I work in IT portfolio and project management. Before that I was PMO for a global SAP program and managed an archiving project and a data migration project. In total I have seven years of corporate IT experience at Ericsson, DXC Technology, DB Schenker and DSV.

This background shapes how I run AI projects. I start with the business problem, agree on a clear scope and make risks visible early. Then I build a working solution that people can test.

Current focus: retrieval-augmented generation (RAG), evaluation of LLM output and the EU AI Act.

## How I work

I build with a coding agent (Claude Code). I decide scope and architecture, set the rules the agent has to follow and review the changes. I test the results live and document decisions and limits in the README.

## Featured projects

### AI-Act Conformity Copilot
`Python` · `Azure OpenAI` · `Azure AI Search` · `RAG` · `Streamlit` · `Docker` · `Azure Container Apps`

Answers questions on the EU AI Act only from the legal text and cites the article for every statement. Hybrid search (full text and vector), automatic citation check and a fixed refusal instead of guessing. 58 automated tests. Runs on Azure in EU regions.
Next steps: risk classification and Annex IV gap analysis.

[Repository](https://github.com/AleksejWeidemann/ai-act-copilot) · [Live demo](https://ca-aiact-copilot.jollyglacier-8eb368d3.swedencentral.azurecontainerapps.io/) (access code on request)

### Posteingang-KI: document triage for insurers
`Python` · `Anthropic API` · `Pydantic` · `Streamlit`

Classifies incoming insurance documents with an LLM and structured output. Rule-based escalation hands unclear cases to a person. On 30 synthetic test documents, 20 were processed automatically (67 %) at about 0.05 USD per run.

[Repository](https://github.com/AleksejWeidemann/posteingang-ki) · [Live demo](https://posteingang-ki.streamlit.app)

### ObstacleAssist: real-time obstacle detection (master's thesis)
`YOLOv8n` · `ONNX Runtime` · `OpenCV` · `Android / Kotlin`

Android app that detects obstacles for visually impaired people and announces them by speech. Runs fully on the device without internet. mAP@0.50 of 0.611 and a median latency of 148–163 ms on commodity hardware, evaluated in three real urban scenarios.

[Repository](https://github.com/AleksejWeidemann/ObstacleAssist)

## Tech stack

| Area | Tools |
|---|---|
| GenAI & RAG | Azure OpenAI · Anthropic API · Azure AI Search · hybrid search · structured output |
| Engineering | Python · Pydantic · Streamlit · pytest · Docker · Git · Claude Code |
| Cloud | Azure Container Apps · Azure Container Registry |
| ML & Computer Vision | YOLOv8 · ONNX Runtime · OpenCV · scikit-learn · TensorFlow/Keras |
| Data | Pandas · NumPy · SQL · Power BI |
| Domain | EU AI Act · IT project and portfolio management |
| Certifications | Microsoft Azure Fundamentals (AZ-900) · Databricks Fundamentals |

## Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aleksej%20Weidemann-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aleksej-weidemann)
[![Email](https://img.shields.io/badge/Email-aleksejweidemann%40outlook.com-0078D4?logo=microsoftoutlook&logoColor=white)](mailto:aleksejweidemann@outlook.com)
