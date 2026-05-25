<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0d1117&height=4&section=header" width="100%"/>
</div>

<br/>

```
I build AI systems that stay reliable when the real world
disagrees with the training set.
```

<br/>

**Asfand Yar** · BSc Computer Science · University of Debrecen, Hungary  
Research collaborator with [Prof. Balázs Harangi](https://www.inf.unideb.hu/) (Deputy Dean, Faculty of Informatics)  
Incoming Forward Deployed Engineer · BMW Debrecen  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/asfand-yar-3966b8291/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:yarasfand886@gmail.com)
[![Profile Views](https://komarev.com/ghpvc/?username=asfandyar-prog&label=views&color=0d1117&style=flat-square)](https://github.com/asfandyar-prog)

---

### The Problem I Work On

Standard ML models are evaluated on clean benchmarks and deployed into messy reality.  
The gap between the two kills clinical AI systems before they help a single patient.

My work closes that gap through **test-time adaptation** — making models update themselves at inference, without labels, without retraining.

---

### Current Research

**JEPA-RobustViT** · BSc Thesis · *supervised by Dr. Bogacsovics Gergő & Sergio Correa (BMW)*

Investigating whether predictive self-supervised pretraining (I-JEPA) produces Vision Transformers inherently more robust to domain shift than reconstruction-based methods (MAE) or contrastive methods (DINO).

| Condition | Accuracy | ECE |
|-----------|----------|-----|
| PathMNIST (source) | 80.90% ± 0.17% | 0.014 |
| → DermaMNIST (shift) | 5.31% ± 0.15% | 0.889 |
| → BloodMNIST (shift) | 17.78% ± 0.24% | 0.749 |
| → RetinaMNIST (shift) | 10.58% ± 0.29% | 0.730 |

A 64× rise in ECE under zero-shot transfer. LayerNorm-only entropy minimization recovers this without any target labels.

→ [`JEPA-RobustViT`](https://github.com/asfandyar-prog/JEPA-RobustViT) · [Live Results Dashboard](https://asfandyar-prog.github.io/JEPA-RobustViT)

---

**PS3C Robust Inference** · Research Paper · *with Prof. Balázs Harangi*

The PS3C cervical cancer classification challenge (103,675 images, 7 teams) produced a gradient-boost ensemble with 0.9517 macro F1 on test. On the hidden clinical evaluation set: 0.9245. For individual models the drop reaches 17.7%.

The original paper never addressed why.

I identified preprocessing-induced distribution shift as the root cause and am building a three-stage fix: architecture-aware TTA across heterogeneous model families, sample-adaptive ensemble weighting, and split-conformal selective prediction with 95% coverage guarantees.

→ [`ps3c-robust-inference`](https://github.com/asfandyar-prog/ps3c-robust-inference) · *Target: Medical Image Analysis / ISBI 2027*

---

**MoleScan** · Applied Research · *supervised by Prof. Balázs Harangi · CITDS 2026*

Dermatology backend for mobile microscopy. ViT-B/16 fine-tuned on ISIC 2019 (25,331 images). 90.5% accuracy, 88.3% macro F1, ECE 0.064. LayerNorm TTA deployed at inference to handle the distribution gap between clinical training data and mobile-captured images.

→ [`molescan-backend`](https://github.com/asfandyar-prog/molescan-backend)

---

### Production

**QuantumMind** · 7-agent LangGraph platform · deployed to 60+ students  
Built from scratch during a 2-week sprint learning FastAPI and React simultaneously.  
Agents: Theory · Code · RAG · Review · Quiz · Debug · Orchestrator  
Stack: LangGraph · FastAPI · React · ChromaDB · MCP · SSE streaming

→ [`quantummind`](https://github.com/asfandyar-prog/quantummind)

---

### Teaching

Designed and delivered the University of Debrecen's first **Introduction to Quantum Computing** course using Qiskit — 60+ students, May 2025.  
Led **IBM Qiskit Fall Fest 2025** — 120+ participants, 70% engagement increase.  
Guest lectures: AI game-playing algorithms, decision trees alongside Assoc. Prof. Balázs Harangi.

→ [`quantum-computing-labs`](https://github.com/asfandyar-prog/quantum-computing-labs)

---

### Stack

```
Research     PyTorch · timm · HuggingFace · MedMNIST · SLURM
Agents       LangGraph · LangChain · MCP · RAG · PEFT/LoRA
Backend      FastAPI · Docker · SSE · Pydantic · uv
Quantum      Qiskit · Hybrid Quantum-Classical Systems
```

---

### GitHub

<div align="center">
<img height="160em" src="https://github-readme-stats.vercel.app/api?username=asfandyar-prog&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&hide_border=true&hide_title=true"/>
<img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=asfandyar-prog&layout=compact&langs_count=6&theme=github_dark&hide_border=true&hide_title=true"/>
</div>

---

<div align="center">
<sub>Debrecen, Hungary · UTC+2 · open to research collaborations and PhD opportunities from 2027</sub>
</div>
