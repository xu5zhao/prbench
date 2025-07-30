# PRBench <img src="https://img.shields.io/badge/status-active-brightgreen"> <img src="https://img.shields.io/badge/data-1.9K_samples-blue">

**PRBench** is the first *comprehensive* benchmark for evaluating large‑language‑model (LLM) **scientific‑paper reading assistants**.  
It contains **1 865 expert‑annotated samples**, grouped into **three core tasks** and **twelve sub‑tasks**, each designed to test a distinct capability required in realistic paper‑reading scenarios :contentReference[oaicite:8]{index=8}.

| Task | Purpose | Example Skills Tested |
|------|---------|-----------------------|
| **Aspect‑based Summarization (AS)** | Fine‑grained factual extraction from full papers | Identify motivation, methods, results, etc. :contentReference |
| **Multi‑Turn Conversation (MT)** | Maintain coherent dialogue across turns | Progressive conceptual understanding, contextual exploration, depth of inquiry  |
| **External Information Comprehension (EIC)** | Incorporate knowledge beyond the paper | Cross‑article reasoning, domain knowledge, retrieval‑augmented QA  |

Evaluation relies on **RLScore**, a rubric‑based *LLM‑as‑a‑Judge* metric that outperforms traditional surface metrics such as ROUGE‑L and BERTScore in correlating with human judgment.

---

## 🌟 Highlights
* **Full‑text** coverage &nbsp;— every sample draws on complete papers instead of abstracts.  
* **Multiple documents + tasks + rubrics** — PRBench uniquely evaluates multi‑document reasoning, multi‑turn dialogue, and rubric‑driven scoring :contentReference[oaicite:13]{index=13}.  
* **Industry‑scale baseline results** for open‑weight, closed‑weight, and proprietary assistants (GPT‑4o, Gemini 1.5/2.0, Qwen‑Long, etc.).  
* **Plug‑and‑play scripts** for dataset download, preprocessing, model inference, and metric calculation.

---

## 📦 Dataset Access

The complete PRBench dataset can be downloaded via the following link:  
🔗 [Download via OneDrive](https://1drv.ms/f/c/516c3281c092f9dd/EvrH6oB_Z39GmYjPmumKcTMB_dYSNeb6Uc14FuGPYnWYyg?e=oZSNLP)
