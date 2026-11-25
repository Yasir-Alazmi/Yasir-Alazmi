# Yasir Alazmi

**AI / ML engineer · B.Sc. Artificial Intelligence, University of Hail (expected January 2027) · Saudi Arabia**

I build machine learning systems end to end: training and evaluating models, then putting them behind tested APIs and shipping them. I care most about honest evaluation: every number in the projects below links to a committed result file.

[LinkedIn](https://www.linkedin.com/in/yasir-alazmi) · [Kaggle](https://www.kaggle.com/yasirnalazmi) · [Email](mailto:yasir.alazmi@outlook.sa)

---

## Selected work

### [Skin lesion classification (HAM10000)](https://github.com/Yasir-Alazmi/skin-lesion-classification)
Seven-class dermoscopy classification in PyTorch (timm).
- A ConvNeXt-S ensemble reaches **0.819 balanced accuracy** (95% CI 0.783–0.852) on a lesion-grouped held-out test set of 1,503 images. A ViT-B/16 baseline reaches 0.712.
- I found image-level leakage behind an earlier 94.2% accuracy result, retracted it, and re-evaluated with lesion-level splits and bootstrap confidence intervals.
- Training sweeps ran on Kaggle GPUs. Negative results are reported too.
- 43 tests, CI.

### UFUQ: bilingual academic assistant for University of Hail students (graduation project)
A retrieval-augmented assistant that answers student questions in Arabic and English from 273 official university documents. I designed and built it, and lead the project team. It is live at [ufuq.space](https://ufuq.space). The code is private for now.
- Hybrid retrieval in PostgreSQL: full-text search and pgvector HNSW, merged with Reciprocal Rank Fusion. Embeddings are bge-m3, served with Ollama.
- A PDF ingestion pipeline with a page-quality gate and an OCR cross-check for damaged pages.
- A Fastify/TypeScript API and a Next.js web app, deployed with Docker Compose and Nginx on AWS.

### [Hybrid retrieval for RAG: reference implementation](https://github.com/Yasir-Alazmi/enterprise-production-rag)
BM25 and dense retrieval fused with Reciprocal Rank Fusion, behind a FastAPI service with role-based access applied inside retrieval.
- On BEIR SciFact (300 queries), the hybrid reaches **nDCG@10 0.679** (BM25 alone: 0.661) and **Recall@100 0.955** (BM25 alone: 0.876).
- 68 tests, Docker, CI. This is a reference implementation and is not deployed.

### [Clinical ML benchmark (NHANES and Framingham)](https://github.com/Yasir-Alazmi/Comparative-Analysis-of-Machine-Learning-Models-for-Healthcare-Diagnostics)
I compared 11 classifiers on CDC NHANES (n = 11,288) using bootstrap confidence intervals and paired tests.
- Regularised logistic regression matched the tree ensembles: ROC-AUC 0.833 on the held-out set, not significantly different from the runner-up, Random Forest (paired bootstrap p = 0.14).
- External validation on Framingham shows how much performance drops under distribution shift.
- The repository also includes conformal prediction and a subgroup fairness check.

---

## Skills

| Area | Tools I have used in the projects above |
|---|---|
| Machine learning | Python, PyTorch, timm, scikit-learn, XGBoost, LightGBM, CatBoost, SHAP, OpenCV, pandas, NumPy |
| Evaluation | held-out and group-aware splits, bootstrap CIs, paired tests, calibration, conformal prediction, BEIR retrieval metrics |
| LLM and retrieval | RAG, BM25 plus dense hybrid search, Reciprocal Rank Fusion, pgvector, Ollama, sentence-transformers |
| Backend | FastAPI, Fastify (TypeScript), Next.js, PostgreSQL, SQLite, MongoDB, JWT and role-based access |
| Delivery | Docker, Docker Compose, Nginx, AWS EC2, GitHub Actions, pytest |
| Optimisation | OR-Tools CP-SAT |

**Languages:** Arabic (native), English.

<sub>Some implementation work in these repositories was done with AI coding assistants. I designed it, reviewed it and tested it.</sub>
