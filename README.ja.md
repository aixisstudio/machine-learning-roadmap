# Machine Learning Roadmap

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | [中文](README.zh-CN.md) | **日本語** | [Русский](README.ru.md)

Python から本番 ML までのロードマップ

_詳細なコンテンツ（リスト・リンク・説明）は保守のため英語です。以下のセクションがガイドになります。_

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
## 貢献

プルリクエストを歓迎します。レビューしてマージします。[aixisstudio](https://github.com/aixisstudio) による管理 — オープンソースのアプリケーションファイアウォール [Snitch](https://github.com/aixisstudio/Snitch) の作者です。

## ライセンス: MIT
