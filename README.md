# Fernando Soto / Software Engineer · Applied AI & ML

Developer at Thoughtworks (~3 years building production backend services on AWS) · MSc Artificial Intelligence, USFQ (expected 2027, GPA 4.0) · Quito, Ecuador

I build LLM applications with RAG, vector search (FAISS, BGE-M3), LangGraph agents and rigorous evaluation (RAGAS, Cohen's kappa), and apply NLP to economic forecasting and algorithmic auditing of social media. Python, PyTorch, AWS, CI/CD.

---

## Research

**USFQ Data Hub · Country Risk Perception**  
NLP pipeline (BGE-M3, BERTopic) turning Ecuadorian news into topic and semantic-volatility features, combined with macroeconomic time series (EMBI, CPI, employment, trade flows) to forecast country risk. In progress.

**TikTok Algorithmic Auditing** · MSc thesis  
Sock puppet methodology with custom metrics (SFH, CWR, PSI, AV) to audit TikTok's FYP and assess psychological risk of recommended content for Spanish-speaking youth. LLM risk assessments evaluated against expert labels (Cohen's kappa).

---

## Projects

| Project | What it does | Stack |
|---|---|---|
| [ablation-rag](https://github.com/ferjozsot23/ablation-rag) | Ablation of 5 RAG architectures (BM25 to LangGraph agent) over SEC 10-K/10-Q filings, with LLM-validated ground truth, RAGAS metrics and cost analysis. IEEE-format paper. | Python · LangGraph · BGE-M3 · FAISS · RAGAS |
| [sam2-transfer-learning](https://github.com/ferjozsot23/sam2-transfer-learning) | SAM 2 encoder + FPN head for semantic segmentation. mIoU 0.60 (+0.14 over a from-scratch U-Net), 113 logged runs, cross-validation by track. Paper. | Python · PyTorch · SAM 2 |
| [hateval-beto-finetuning](https://github.com/ferjozsot23/hateval-beto-finetuning) | Progressive layer-freezing study of BETO for Spanish hate speech detection. Test accuracy 0.83, embedding separability via t-SNE/silhouette. IEEE-format paper. | Python · PyTorch · Transformers · scikit-learn |
| [tiktok-fyp-auditor](https://github.com/ferjozsot23/tiktok-fyp-auditor) | FYP data collection via sock puppet accounts. Playwright automation + Whisper large-v3 transcription. 470 videos collected. | Python · Playwright · Whisper |
| [tiktok-psych-risk-classifier](https://github.com/ferjozsot23/tiktok-psych-risk-classifier) | Binary risk classifier on video transcripts. BETO embeddings, RepeatedStratifiedKFold 5×5, Wilcoxon testing. SVM F1 = 0.764. | Python · BETO · scikit-learn |
| [agentic-graphrag](https://github.com/ferjozsot23/agentic-graphrag) | Three-agent GraphRAG pipeline with ChromaDB + NetworkX and custom LLM-as-judge evaluation. | Python · OpenAI · ChromaDB |
| [merchant-churn-predictor](https://github.com/ferjozsot23/merchant-churn-predictor) | XGBoost churn model with SHAP explainability and React dashboard. Built in 48h at Interact2Hack 2026 (2nd place of 53). | Python · XGBoost · React |

---

nandojozesoto@gmail.com · Open to remote ML/AI roles