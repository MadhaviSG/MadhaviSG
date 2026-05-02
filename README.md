<!--
  GitHub Profile README for github.com/MadhaviSG

  Setup:
    1. Create a public repo named exactly "MadhaviSG"
    2. Add this file as README.md
    3. Commit. GitHub renders it on your profile.

  Maintenance:
    - When Voice Grocery and Scotty-Scheduler repos are publication-ready,
      uncomment the link lines marked TODO below.
-->

# Madhavi Gulavani

**ML / AI Engineer** · MS ECE @ Carnegie Mellon (AI/ML) · Graduating May 2026
Looking for full-time ML / AI Engineer roles starting May 2026.

---

I'm a graduating master's student at CMU specializing in machine learning, with **6 years of prior production software engineering experience** in fintech (Java/Spring Boot microservices at Fidelity Investments and Principal Financial Group, ~2,000 TPS on AWS). That background shapes how I approach ML — I care about systems that actually run, not just notebooks that work once.

Currently:
- **Graduate Research Assistant** at the [CMU Language Technologies Institute](https://www.lti.cs.cmu.edu/), working on agent safety evaluation infrastructure with [Prof. Graham Neubig](https://phontron.com/) and [Prof. Maarten Sap](https://maartensap.com/).
- **Graduate Teaching Assistant** for [11-785 Introduction to Deep Learning](https://deeplearning.cs.cmu.edu/) (~400 students).

---

## What I work on

| Area | What that means in practice |
|---|---|
| **Agent safety & evaluation** | OpenAgentSafety benchmark infrastructure, trajectory analysis, real-time safety monitoring with Gray Swan Cygnal API |
| **LLM systems** | RAG, multi-agent orchestration (LangGraph), tool use via MCP, local + cloud LLM serving |
| **Applied deep learning** | Transformer ASR, multimodal retrieval, metric learning, generative models |
| **MLOps & cloud** | Vertex AI, GCP/AWS, Terraform, Kubernetes, model serving at scale |

---

## Selected work

🛡️ **OpenAgentSafety Infrastructure** &mdash; Sole engineer migrating the OpenAgentSafety benchmark to the OpenHands SDK. 359 LLM safety tasks across 8 risk categories, per-task Docker isolation, redesigned bash-accessible NPC system. Published HuggingFace dataset for open-source LLM safety eval. Advised by Prof. Graham Neubig.
&rarr; Open-source contributions: [`OpenHands/benchmarks`](https://github.com/OpenHands/benchmarks)

🏆 **Scotty-Scheduler** &mdash; Multi-agent RAG course advisor built in 24 hours. Won **Best Use of MistralAI** at the CMU AI Agents Hackathon 2025. Stack: LangGraph · LlamaIndex · Pinecone · Mistral-7B · Modal.

🚕 **NYC Taxi Fare + RAG Travel Assistant** &mdash; End-to-end MLOps on GCP. XGBoost fare predictor (3.6 RMSE) trained with Vertex AI HyperTune, served via App Engine + 5 GCP services, with a LangGraph multi-agent layer routing between fare prediction and a Vertex AI RAG Engine powered by Llama 3.1-70B.

🧠 **[EEG-Multimodal-Project](https://github.com/MadhaviSG/EEG-Multimodal-Project)** &mdash; Custom 1D Vision Transformer aligning 122-channel EEG signals to CLIP's text space via LoRA + Knowledge Distillation. Recall@5 of 17.52% (~2× baseline); 95% parameter reduction via LoRA. Trained on the Pittsburgh Supercomputer Center cluster. *Team project — CMU 11-785.*

🎙️ **Voice Grocery Agent** &mdash; Real-time voice agent with hot-swappable LLM backends (GPT-4o ↔ Ollama) exposed via MCP. LiveKit + Whisper + Silero VAD, ~3-5s end-to-end latency over a 3M-product catalog (Open Food Facts).

🔬 **MyTorch + Transformer ASR** &mdash; NumPy deep learning library implemented from scratch (autograd, CTC loss, beam search) + an encoder-decoder Transformer ASR system in PyTorch with joint CTC+CE loss, achieving 8.78% CER.

> Detailed write-ups for each project are on my portfolio (link below).

---

## Currently building (public WIP)

🎬 **[multimodal-recsys-agent](https://github.com/MadhaviSG/multimodal-recsys-agent)** &mdash; Production-shaped two-tower retrieval + FAISS + LightGBM ranker on MovieLens 25M. Building in public — design rationale and progress visible in commits.

Also in flight: a culturally-aware image-to-music generative model (CMU 18-789), and a self-directed LLM inference curriculum covering KV cache, FlashAttention, quantization, speculative decoding, and vLLM internals.

---

## Stack I reach for

**Languages** Python · Java · TypeScript · SQL
**ML / DL** PyTorch · HuggingFace Transformers · PEFT/LoRA · scikit-learn · XGBoost · LightGBM · FAISS
**LLM & Agents** LangGraph · LlamaIndex · MCP · Pinecone · Vertex AI RAG Engine · Ollama · OpenHands SDK
**Cloud / MLOps** AWS · GCP (Vertex AI, App Engine) · Azure · Terraform · Docker · Kubernetes · Helm
**Tools** Weights & Biases · Modal · GitHub Actions · FastAPI · Spring Boot

---

## Find me

[Portfolio](https://your-portfolio-url.com) · [LinkedIn](https://linkedin.com/in/madhavi-gulavani) · mgulavan [at] andrew [dot] cmu [dot] edu

If you're hiring for **ML / AI Engineer roles starting May 2026** — or building something interesting in agent safety, applied LLMs, or ML systems — I'd love to hear from you.

<!--
  TODO when ready:
    - Replace https://your-portfolio-url.com with real portfolio URL
    - Add link to Voice Grocery repo when polished
    - Add link to Scotty-Scheduler repo when improved
-->
