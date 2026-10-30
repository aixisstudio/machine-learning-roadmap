# Machine Learning Roadmap

[English](README.md) | **Français** | [Español](README.es.md) | [中文](README.zh-CN.md) | [日本語](README.ja.md) | [Русский](README.ru.md)

De Python au ML en production — une feuille de route guidée

Le chemin

1. Fondations (4-8 wks)
- Python + NumPy + Pandas — fluency first
- Mathématiques: algèbre linéaire (vecteurs/matrix mults), calcul (gradients), base de probabilité — [3Blue1Brown](https://www.youtube.com/@3blue1brown) pour l'intuition

2. Classic ML (6-10 wks)
- Spécialisation ML d'Andrew Ng (Coursera)
- scikit-learn: régression → arbres → ensembles
- Construire: prédire quelque chose sur un jeu de données réel (Kaggle Titanic → Prix de la maison)

3. Apprentissage profond (8-12 wks)
- didacticiels fast.ai ou PyTorch — tenseurs, autogrades, boucles d'entraînement
- CNN (vision), RNN/transformateurs (séquence)
- Construire : classificateur d'image, puis peaufiner un petit LLM

4. Pile moderne (en cours)
- Architecture des transformateurs — *Attention est tout ce dont vous avez besoin*
- Des cambrioleurs Transformateurs visage + réglage fin PEFT/LORA
- RAG: emboîtements + vecteurs DB + récupération

5. Production
- Service (FastAPI, vLLM), évaluations, suivi, coût
- MLOps: expériences (MLflow), version de données (DVC), déploiement

Pratique
Resource Focus
|---|---|
Concours & ensembles de données
Cours de huggingFace, gratuit, pratique
Haut vers le bas enseignement pratique profond
Papiers avec code SOTA + implémentations

Note réaliste
Vous n'avez pas besoin d'un doctorat — vous avez besoin de représentants: construire, casser, reconstruire. La feuille de route compresse ce qui a pris des années d'équipes en mois de pratique ciblée.

Étape 4 : Spécialisation

Titre Apprendre Construire
|---|---|---|
Transformateurs, tokenisation, réglage fin
Vision, diffusion, YOLO
Q-learning de RL, PPO
Docker, CI/CD, monitoring
LLMs, agents, évaluations Assistant de production

Le canon

- **CS229** (Ng) — le classique
- **Fast.ai** — pratique-première
- **Plonger dans l'apprentissage profond** (d2l.ai) — code-avant
- **Réseaux neuronaux: Zéro à Héros** (Karpathie) — construire à la main
- **Hands-On ML** (Géron) — l'ouvrage de référence

Projets de portefeuille qui sont remarqués

1. Reproduire un papier connu — prouver la rigueur
2. Finissez un modèle ouvert sur les données de niche — montrer la pensée de domaine
3. Déployer un modèle avec surveillance — maturité de la production
4. Contribuer à une bibliothèque connue ML — signal communautaire

---
## Contribuer

Les pull requests sont les bienvenues : ouvre une PR, elle sera relue et fusionnée. Maintenu par [aixisstudio](https://github.com/aixisstudio), auteur de [Snitch](https://github.com/aixisstudio/Snitch), pare-feu applicatif open source.

## Licence: MIT
