# Shrey Kadia

Senior AI Engineer in Ahmedabad, India. I build production LLM systems (agents, real-time voice AI, retrieval) and like to understand how they work underneath.

**[shreykadia.com](https://shreykadia.com)** · [LinkedIn](https://linkedin.com/in/srkadia) · [Email](mailto:srkkadia@gmail.com)

## What I'm building

I'm building the AI layer of [Mitoo](https://mitoo.ai), a multi-tenant business platform, at Mehta Softech. I've built these on my own:

- **A multi-agent assistant** across 6 product apps, with 28 agents and ~640 tools. A permission layer removes every action the user isn't allowed to take before the model ever sees it. Common recruiter tasks went from ~1.5 min to ~15 s.
- **A self-hosted AI phone agent** (FreeSWITCH/SIP, Claude on Bedrock, streaming STT/TTS) that calls every new lead within 15 minutes, qualifies it and writes the call back to the CRM.
- **An AI voice interviewer** on LiveKit that has run 50+ screening interviews in 5 languages.
- **A QLoRA fine-tune of Qwen2.5-3B** with its own eval harness (schema validity, exact match, skill overlap), served locally through GGUF and Ollama.

That code is private. The write-ups are on [shreykadia.com](https://shreykadia.com).

## In public

**[llm-lab](https://github.com/srkadia/llm-lab)**: the parts of an LLM built from scratch in NumPy, one experiment per module. Module 1 is an autograd engine plus a test of how small ε should be in a gradient check. In float32, a correct gradient can come out 25% wrong. Attention and a tiny GPT are next.

## Before this

Two years as a data scientist on credit risk: LightGBM models, MLflow, FastAPI on AWS. Accuracy up 15%, loan approvals down from 48 to 36 hours. Projects from then: [LoanGuard](https://github.com/srkadia/LoanGuard), [Crop Recommender](https://github.com/srkadia/CRS).

## Tools

    Languages     Python · TypeScript (NestJS) · SQL
    LLMs          AWS Bedrock (Claude) · HuggingFace · QLoRA / Unsloth · Ollama
    Voice         LiveKit · FreeSWITCH / SIP · Deepgram · Sarvam · Silero VAD
    Data          PostgreSQL + pgvector · Redis · BullMQ
    Cloud & ops   AWS (Lambda, Step Functions, ECS, EC2, S3) · Docker · MLflow · GitHub Actions
