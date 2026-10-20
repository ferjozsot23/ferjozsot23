# Fernando Soto / ML·AI Engineer

Software Engineer at Thoughtworks · MSc Artificial Intelligence, USFQ (2026) · Quito, Ecuador

I work on NLP applied to social media auditing and economic forecasting. My current research combines news text with macroeconomic data to predict country risk in Ecuador, and audits TikTok's recommendation algorithm to measure psychological risk in content served to young users.

---

## Research

**USFQ Data Hub — Country Risk Perception**  
NLP on Ecuadorian news media combined with macroeconomic time series (EMBI, CPI, employment, trade flows) to predict country risk perception using ML. In progress.

**TikTok Algorithmic Auditing** — MSc thesis  
Sock puppet methodology with custom metrics (SFH, CWR, PSI, AV) to audit TikTok's FYP and assess psychological risk of recommended content for Spanish-speaking youth. 2 papers in preparation.

---

## Projects

| Project | What it does | Stack |
|---|---|---|
| [tiktok-fyp-auditor](https://github.com/ferjozsot23/tiktok-fyp-auditor) | FYP data collection via sock puppet accounts. Playwright automation + Whisper large-v3 transcription. 470 videos collected. | Python · Playwright · Whisper |
| [tiktok-psych-risk-classifier](https://github.com/ferjozsot23/tiktok-psych-risk-classifier) | Binary risk classifier on video transcripts. BETO embeddings, RepeatedStratifiedKFold 5×5, Wilcoxon testing. SVM F1 = 0.764. | Python · BETO · scikit-learn |
| [agentic-graphrag](https://github.com/ferjozsot23/agentic-graphrag) | Three-agent GraphRAG pipeline with ChromaDB + NetworkX and custom LLM-as-judge evaluation. | Python · OpenAI · ChromaDB |
| [merchant-churn-predictor](https://github.com/ferjozsot23/merchant-churn-predictor) | XGBoost churn model with SHAP explainability and React dashboard. Built in 48h at Interact2Hack 2026. | Python · XGBoost · React |
| [ablation-rag](https://github.com/ferjozsot23/ablation-rag) | Ablation of 5 RAG architectures (BM25 to LangGraph agent) over SEC 10-K/10-Q filings, with LLM-validated ground truth, RAGAS metrics and cost analysis. IEEE-format paper. | Python · LangGraph · BGE-M3 · FAISS · RAGAS |
| [hateval-beto-finetuning](https://github.com/ferjozsot23/hateval-beto-finetuning) | Progressive layer-freezing study of BETO for Spanish hate speech detection. Test accuracy 0.83, embedding separability via t-SNE/silhouette. IEEE-format paper. | Python · PyTorch · Transformers · scikit-learn |
| [sam2-transfer-learning](https://github.com/ferjozsot23/sam2-transfer-learning) | SAM 2 encoder + FPN head for semantic segmentation. mIoU 0.60 (+0.14 over a from-scratch U-Net), 113 logged runs, cross-validation by track. Paper. | Python · PyTorch · SAM 2 |

---

nandojozesoto@gmail.com · Open to remote ML/AI roles