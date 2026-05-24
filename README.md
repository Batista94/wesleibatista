# Weslei Batista | Data Scientist & Machine Learning Engineer

<p align="center">
  <a href="#english">English</a> • 
  <a href="#portuguese">Português (Brasil)</a>
</p>

---

<div id="english">

## 🇺🇸 English Version

Data Scientist and ML Engineer at **AI/R Compass UOL**. Currently consulting for large-scale infrastructure and Energy operations, focusing on the development of specialized machine learning models and automated data governance.

### 🧠 Domain Expertise
* **People Analytics & HR Tech:** AI models for organizational structural analysis and automated corporate goal tracking.
* **Conversational AI & NLP:** LLM orchestration for enterprise-grade chatbots and semantic search engines.
* **Computer Vision:** Image analysis systems designed for privacy-first environments (LGPD), optimizing infrastructure costs.
* **Industrial Operations:** Data integration for predictive logistics, improving asset availability and unloading efficiency.

### 🏗️ Engineering & Architecture
I architect high-integrity distributed systems and deterministic data pipelines:
* **Forensic Data Invariants:** Implementation of strict database-level consistency models (UTC mandatory pipelines, symmetric Basis Points rounding, and `BIGINT` monetary representation to eliminate floating-point drift).
* **Decoupled Event Sourcing:** Designing infrastructure-agnostic domain cores (`lib/domain/`) with deterministic event replay, periodic state snapshots, and time-travel auditing to eliminate mutability disputes.
* **Zero-Trust Telemetry Ingestion:** Cryptographic edge sealing (SHA-256 evidence hashing + tenant-isolated HMAC signatures) and idempotency layers to securely process telemetry from untrusted edge devices.
* **Solo-Enterprise Rigor:** Maintaining high-complexity systems autonomously via automated security scanners, dockerized visual regressions (Hermetic Goldens), and automated pgTap database tests.

### 💼 Proprietary Projects
* **VeraProb:** An Agnostic Forensic Engine engineered for SLA/Financial Protection and B2B contract governance of high-frequency operational telemetry. It ingests untrusted telemetry streams at scale, ranks evidence, and issues immutable, cryptographically sealed verdicts auditable in <10 seconds.
    * **Architecture:** DDD with strict C4 boundaries, Event Sourcing core for deterministic historical replay, and database-level append-only restrictions (no updates/deletes).
    * **Stack:** Flutter (Wasm/CanvasKit) + Riverpod 3, Supabase (PostgreSQL + Native RLS), Deno Edge Functions, Drift (offline fact-queue storage), MapTiler.

---

</div>

<div id="portuguese">

## 🇧🇷 Versão em Português

Data Scientist e Machine Learning Engineer na **AI/R Compass UOL**. Atuando como consultor em projetos de larga escala no setor de Energia, focado no desenvolvimento de modelos de machine learning e governança automatizada de dados.

### 🧠 Domínios de Atuação
* **People Analytics & HR Tech:** Modelos de IA para análise de estruturas organizacionais e gestão automatizada de metas.
* **IA Conversacional & NLP:** Orquestração de LLMs para chatbots corporativos e sistemas de busca semântica.
* **Visão Computacional:** Sistemas de análise de imagem projetados para conformidade com privacidade (LGPD) e otimização de infraestrutura.
* **Operações Industriais:** Integração de dados para logística preditiva, melhorando a disponibilidade de ativos e eficiência de descarga.

### 🏗️ Engenharia & Arquitetura
Priorizo sistemas determinísticos e integridade de dados em nível forense:
* **Invariantes Forenses de Dados:** Implementação de modelos rígidos de consistência no banco de dados (pipelines em UTC mandatório, arredondamento simétrico de Basis Points e representação monetária em `BIGINT` para eliminar desvios de ponto flutuante).
* **Event Sourcing Desacoplado:** Design de núcleos de domínio agnósticos a infraestrutura (`lib/domain/`) com replay determinístico de eventos, snapshots de estado periódicos e auditoria "time-travel" para eliminar disputas de mutabilidade de dados.
* **Ingestão Telemetria Zero-Trust:** Selagem criptográfica na borda (hashing de evidência SHA-256 + assinaturas HMAC isoladas por tenant) e camadas de idempotência para processar com segurança telemetria de dispositivos periféricos não confiáveis.
* **Rigor Solo-Enterprise:** Manutenção autônoma de sistemas de alta complexidade via scanners de segurança integrados, regressões visuais dockerizadas (Hermetic Goldens) e testes automatizados de banco de dados via pgTap.

### 💼 Projetos Proprietários
* **VeraProb:** Motor forense agnóstico (Agnostic Forensic Engine) projetado para governança de contratos B2B, proteção financeira e validação de SLAs através de telemetria operacional de alta frequência. Processa fluxos de dados brutos não confiáveis (untrusted) e emite vereditos imutáveis e auditáveis em menos de 10 segundos.
    * **Arquitetura:** DDD com limites rígidos de C4, motor em Event Sourcing para replay determinístico da linha do tempo e restrição de escrita append-only diretamente no banco de dados.
    * **Stack:** Flutter (Wasm/CanvasKit) + Riverpod 3, Supabase (PostgreSQL + RLS nativo), Deno Edge Functions, Drift (fila de fatos local via SQLite), MapTiler.

---

</div>

### 🛠️ Tech Stack
* **Machine Learning & Analytics:** Python (Scikit-Learn, PyTorch), LLMs, LangChain, Transformers, Databricks.
* **Data & Cloud Infrastructure:** PostgreSQL (RLS, pgTAP), Supabase, Drift (SQLite), Spark, AWS, Azure.
* **Architecture & Patterns:** Clean Architecture (C4 Boundaries), Event Sourcing, Domain-Driven Design (DDD), WebAssembly (Wasm-ready APIs).

### 🎓 Education & Certifications
* **MBA in AI & Big Data** – USP/ICMC (2024).
* **Oracle Certified:** AI Agent Studio Foundations (2025).
* **AWS Partner:** Agentic AI Essentials (2025).

### 📫 Links
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/wesleirbatista/)](https://www.linkedin.com/in/wesleirbatista/)
