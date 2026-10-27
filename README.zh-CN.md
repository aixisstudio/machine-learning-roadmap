# Machine Learning Roadmap

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | **中文** | [日本語](README.ja.md) | [Русский](README.ru.md)

从 Python 到生产级 ML — 路线图

_详细内容（列表、链接、描述）以英文维护 — 以下章节为你指引。_

## 🗺️ The path

### 1. Foundations (4-8 wks)
- Python + NumPy + Pandas — fluency first
- Math: linear algebra (vectors/matrix mults), calculus (gradients), probability basics — [3Blue1Brown](https://www.youtube.com/@3blue1brown) for intuition

### 2. Classic ML (6-10 wks)
- Andrew Ng's ML Specialization (Coursera)
- scikit-learn: regression → trees → ensembles
- Build: predict something on a real dataset (Kaggle Titanic → House Prices)

### 3. Deep learning (8-12 wks)
- fast.ai or PyTorch tutorials — tensors, autograd, training loops
- CNNs (vision), RNNs/transformers (sequence)
- Build: image classifier, then fine-tune a small LLM

### 4. Modern stack (ongoing)
- Transformers architecture — *Attention Is All You Need*
- HuggingFace transformers + PEFT/LoRA fine-tuning
- RAG: embeddings + vector DBs + retrieval

### 5. Production
- Serving (FastAPI, vLLM), evals, monitoring, cost
- MLOps: experiments (MLflow), data versioning (DVC), deployment

## 🧪 Practice
| Resource | Focus |
|---|---|
| Kaggle | Competitions & datasets |
| HuggingFace courses | Free, hands-on |
| fast.ai | Top-down practical deep learning |
| Papers with Code | SOTA + implementations |

## ⚠️ Realistic note
You don't need a PhD — you need reps: build, break, rebuild. The roadmap compresses what took teams years into months of focused practice.

---
## 贡献

欢迎提交 Pull Request，我们会审查并合并。由 [aixisstudio](https://github.com/aixisstudio) 维护，他也是开源应用防火墙 [Snitch](https://github.com/aixisstudio/Snitch) 的作者。

## 许可证: MIT
