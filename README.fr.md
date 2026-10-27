# Machine Learning Roadmap

[English](README.md) | **Français** | [Español](README.es.md) | [中文](README.zh-CN.md) | [日本語](README.ja.md) | [Русский](README.ru.md)

De Python au ML en production — une feuille de route guidée

_Le contenu détaillé (listes, liens, descriptions) est en anglais pour rester maintenable — les sections ci-dessous te guident._

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
## Contribuer

Les pull requests sont les bienvenues : ouvre une PR, elle sera relue et fusionnée. Maintenu par [aixisstudio](https://github.com/aixisstudio), auteur de [Snitch](https://github.com/aixisstudio/Snitch), pare-feu applicatif open source.

## Licence: MIT
