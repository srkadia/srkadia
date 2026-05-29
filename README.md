# Shrey Kadia

**Senior AI Engineer** · Ahmedabad, India  
Building production AI systems that actually work at scale.

---

### About

I started as a Data Scientist in 2023 — credit risk models, feature engineering on 10M+ records, FastAPI deployments on AWS. Good foundation, but I wanted to build things people interact with, not just reports people read.

Moved into AI engineering and haven't looked back. Now I spend my time on agent architectures, real-time voice AI, LLM fine-tuning, and making all of it reliable in production. 3 years in, currently Senior AI Engineer at a product startup.

The problems I find most interesting: how do you make a small model punch above its weight? How do you build an agent that doesn't hallucinate actions? How do you serve LLMs cheaply without sacrificing quality?

---

### What I Work On Professionally

**Agentic AI Systems** — Multi-agent orchestration using LangGraph and AWS Bedrock. Designing orchestrator-to-subagent routing, session memory, tool use at scale, and streaming. The kind of system where a user describes what they want and agents figure out the rest.

**Real-time Voice AI** — Production voice agents built on LiveKit. Multilingual STT/TTS routing, adaptive VAD configuration, noise cancellation. The hard parts: latency, interruption handling, session reliability.

**LLM Fine-tuning & Inference** — QLoRA fine-tuning of small open-source models (Qwen, Mistral family) using teacher-student distillation from frontier models. GGUF quantization, Ollama deployment, EC2 serving. Getting 3B parameter models to match frontier model output quality on specific tasks.

**Serverless ML Pipelines** — AWS Step Functions + Lambda for multi-stage AI evaluation pipelines. Transcription, speaker analysis, LLM evaluation, automated report generation — chained, fault-tolerant, production-monitored.

---

### Stack

```
LLM & Training     QLoRA · GGUF · Teacher-student distillation
                   HuggingFace (peft, trl) · Ollama · AWS Bedrock

Agentic AI         LangGraph · LangChain · LangChain-AWS

Voice & RT         LiveKit Agents · Deepgram · Sarvam AI · Silero VAD

MLOps & Cloud      AWS (EC2, S3, Lambda, Step Functions, Athena, SQS)
                   FastAPI · Docker · MLflow · GitHub Actions

ML Foundations     LightGBM · XGBoost · ANN · BERT · Sentence Transformers · SpaCy

Data & Storage     PostgreSQL · Snowflake · MySQL · MongoDB
```

---

### Public Projects

These are older — built when I was deep in the ML/data science world. New practice projects coming as I go deeper on fine-tuning and inference optimization.

- **[LoanGuard](https://github.com/srkadia/LoanGuard)** — End-to-end loan default prediction pipeline. LightGBM + XGBoost + ANN, MLflow experiment tracking, Flask + EC2 deployment. 12% accuracy improvement over baseline.
- **[Crop Recommender System](https://github.com/srkadia/CRS)** — Crop recommendation by soil type and location. ResNet + Flask. 25% yield improvement in testing.

---

### Currently Learning

Fine-tuning training dynamics · vLLM & inference optimization · RAG evaluation (RAGAS) · Reading: QLoRA paper, PagedAttention (vLLM), RLHF survey

---

### Certifications
Oracle Cloud Infrastructure 2024 Generative AI Professional

---

[![LinkedIn](https://img.shields.io/badge/LinkedIn-srkadia-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/srkadia)
&nbsp;
[![Email](https://img.shields.io/badge/Email-srkkadia@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:srkkadia@gmail.com)
