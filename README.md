# 🧠 LLMs Beyond Pretraining

> Hands-on experiments in fine-tuning, PEFT, LoRA, RAG, and LLM agents — going well beyond the pretraining phase.

[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 📌 Overview

Modern LLMs are powerful out of the box — but the real magic happens *after* pretraining. This repository is a practical exploration of the techniques used to adapt, align, and extend large language models for specific tasks and use cases.

The notebooks here cover a progression from efficient fine-tuning methods all the way to building RAG pipelines and agentic workflows with open-source models like **LLaMA 3.1**.

---

## 📂 Notebooks

| # | Notebook | What it covers |
|---|----------|----------------|
| 1 | [`explore_llama3_1.ipynb`](explore_llama3_1.ipynb) | Loading, prompting, and exploring Meta's LLaMA 3.1 model — understanding its capabilities, tokenizer, and generation behaviour |
| 2 | [`llm-finetuning-with-lora-1.ipynb`](llm-finetuning-with-lora-1.ipynb) | Parameter-efficient fine-tuning using **LoRA** (Low-Rank Adaptation) — how to adapt a large model with a fraction of the compute |
| 3 | [`explore_RAG_with_llama_3_1.ipynb`](explore_RAG_with_llama_3_1.ipynb) | Building a **Retrieval-Augmented Generation (RAG)** pipeline with LLaMA 3.1 — grounding LLM outputs in external knowledge |

---

## 🔑 Key Concepts Explored

- **Fine-tuning** — adapting a pretrained LLM on a downstream task
- **PEFT (Parameter-Efficient Fine-Tuning)** — updating only a small subset of model parameters
- **LoRA / qLoRA** — low-rank matrix decomposition for memory-efficient training
- **RAG (Retrieval-Augmented Generation)** — combining vector search with LLM generation for grounded, factual responses
- **LLaMA 3.1** — hands-on work with Meta's open-source frontier model

---

## 🚀 Getting Started

### Prerequisites

```bash
pip install transformers peft accelerate bitsandbytes torch
pip install langchain sentence-transformers faiss-cpu
```

### Run locally

```bash
git clone https://github.com/palash147/LLMs_beyond_pretraining.git
cd LLMs_beyond_pretraining
jupyter notebook
```

> **Note:** A GPU (16GB+ VRAM recommended) is needed for running LLaMA 3.1 locally. Google Colab (A100/T4) works well for most notebooks.

---

## 🗺️ Roadmap

Topics planned for future exploration:

- [ ] qLoRA fine-tuning on custom datasets
- [ ] DPO / RLHF alignment techniques
- [ ] Function-calling and tool-use agents
- [ ] Multi-agent orchestration
- [ ] Deploying fine-tuned models with vLLM / Ollama

---

## 📚 References & Resources

- [Hugging Face PEFT library](https://github.com/huggingface/peft)
- [LoRA paper — Hu et al., 2021](https://arxiv.org/abs/2106.09685)
- [RAG paper — Lewis et al., 2020](https://arxiv.org/abs/2005.11401)
- [Meta LLaMA 3.1](https://ai.meta.com/blog/meta-llama-3-1/)
- [LangChain docs](https://python.langchain.com/)

---

## 🤝 Contributing

Contributions, experiments, and improvements are welcome! Feel free to open an issue or submit a pull request.

---

## 👤 Author

**Palash** · [GitHub](https://github.com/palash147) · [LinkedIn](https://www.linkedin.com/in/palash147/)
