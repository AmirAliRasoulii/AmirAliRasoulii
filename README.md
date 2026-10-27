<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AmirAliRasoulii/AmirAliRasoulii/main/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AmirAliRasoulii/AmirAliRasoulii/main/header-light.svg">
  <img alt="Amirali Rasouli — AI Engineer and NLP Specialist. LLM applications, retrieval and backend systems." src="https://raw.githubusercontent.com/AmirAliRasoulii/AmirAliRasoulii/main/header-light.svg" width="100%">
</picture>

<br>

I design and build **LLM applications for Persian**: retrieval systems, agent workflows, and the Python services that connect them to real products. My work also spans document intelligence and dataset pipelines, with a focus on evaluation, traceability, and reliable execution.

## Selected repositories

### 01 &nbsp; SOHA AI Assistant

**Agent orchestration · Typed contracts · Evidence**

An assistant core built around explicit execution and data contracts. The public repository includes an asynchronous orchestration baseline, evidence and answer planning, authorization boundaries, and idempotent turn finalization.

<sub>Public scope: an in-process core and architecture, under active development.</sub>

[Repository →](https://github.com/AmirAliRasoulii/soha-ai-assistant) &nbsp;·&nbsp; [Architecture](https://github.com/AmirAliRasoulii/soha-ai-assistant/tree/main/docs/architecture) &nbsp;·&nbsp; [Core runtime](https://github.com/AmirAliRasoulii/soha-ai-assistant/tree/main/src/ai_assistant/core)

---

### 02 &nbsp; Farsi Corpus Forge

**Persian data · Quality evaluation · Human review**

A pipeline for adapting research corpora into Persian and generating separate non-offensive datasets. It combines translation fidelity checks, two independent quality judges, resumable SQLite checkpoints, data lineage, and an Excel workflow for human review.

[Repository →](https://github.com/AmirAliRasoulii/farsi-corpus-forge) &nbsp;·&nbsp; [Translation pipeline](https://github.com/AmirAliRasoulii/farsi-corpus-forge/tree/main/persianization) &nbsp;·&nbsp; [Offline demo](https://github.com/AmirAliRasoulii/farsi-corpus-forge/tree/main/mock_demo)

---

### 03 &nbsp; Multi-Judge Offense Pipeline

**LLM-as-a-judge · Consensus · Auditable annotation**

A Persian and English annotation pipeline for offensive language and toxicity. Four independent LLM judges feed a consensus engine, with schema validation, moderation-based tie resolution, persistent checkpoints, and human adjudication for cases that need review.

[Repository →](https://github.com/AmirAliRasoulii/multi-judge-offense-pipeline) &nbsp;·&nbsp; [Annotation engine](https://github.com/AmirAliRasoulii/multi-judge-offense-pipeline/tree/main/offense_judge) &nbsp;·&nbsp; [Examples](https://github.com/AmirAliRasoulii/multi-judge-offense-pipeline/tree/main/examples)

<br>

**Document intelligence:** my [paperless-ngx fork](https://github.com/AmirAliRasoulii/paperless-ngx), based on the [upstream paperless-ngx project](https://github.com/paperless-ngx/paperless-ngx), is also part of my document-management work.

## Toolkit

| Area | Tools & methods |
| :--- | :--- |
| **LLM applications & retrieval** | LangGraph · RAG · embeddings · hybrid search |
| **Evaluation & observability** | Ragas · Langfuse · LLM-as-a-judge · human review |
| **Backend engineering** | Python · Django / DRF · FastAPI · WebSockets |
| **Data & deployment** | PostgreSQL · Redis · Docker · Linux |
| **Model serving** | vLLM · llama.cpp · Ollama |
