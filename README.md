# Flowsight
**"Reproducible & explainable graph-based network intrusion detection on NetFlow v3 data — retraining GraphIDS, auditing its benchmarks, and opening the black box."**

Flowsight is the system; this repository documents the study behind it: rethinking how graph-based NIDS are trained and evaluated.

**Platform note:** Development started on Google Colab (archived repo: najeeb160/explainable-nids) and migrated to Kaggle before model training.  

**Reasons:** Kaggle provides a predictable weekly GPU allowance (30 h/week, scheduled reset) vs. Colab free tier's variable availability; background execution (Save & Run All runs up to 12 h without keeping the browser open); P100/T4 GPUs with 29 GB RAM and 4 vCPUs, which benefits GraphIDS' graph preprocessing and neighbor sampling; and first-class dataset mounting, which removes per-session download/unzip overhead.

## Roadmap
[] Phase 0 — Kaggle environment setup (GraphIDS, GPU, dataset gates)  
[] Phase 1 — Dataset exploration and quality audit  
[] Phase 2 — GraphIDS retraining and evaluation  
[] Phase 3 — Explainability analysis  
[] Phase 4 — Temporal evaluation  
[] Phase 5 — Final report  


## Repository structure
    ├── rethinking-graph-nids/
            └── notebooks/
            |      └── 
            ├── .gitignore
            ├── LICENSE
            ├── README.md

undefined
