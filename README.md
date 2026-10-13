## Madaka Amarnath

Final-year B.Tech CSE at NIT Andhra Pradesh (2027). I build machine learning systems end to end, and I care most about evaluating them honestly: splits that match how a model will be used, intervals instead of single numbers, and checks that what ships is what was measured.

[Portfolio](https://amarnath10i-portfolio.vercel.app) · [Kaggle](https://kaggle.com/amarnath10) · amarnath10chinu@gmail.com

### Selected work

| Project | What it is | Measured result |
|---|---|---|
| [fraud-sentinel](https://github.com/Amarnath10i/fraud-sentinel) | Real-time card fraud detection: point-in-time features in SQL and streaming, gradient boosting from scratch, calibrated cost-based decisions, drift monitoring | PR-AUC 0.992 on six later months; calibrated decisions 4.5× cheaper than a best-F1 threshold |
| [CinemaTime](https://github.com/Amarnath10i/CinemaTime) | Two-stage recommender on MovieLens 32M (EASE, implicit ALS, LightGBM LambdaRank) served by a NumPy engine | NDCG@20 0.141 on a held-out year, +13% over the best single model |
| [Atom](https://github.com/Amarnath10i/Atom) | Knowledge tracing for an AI tutor: LightGBM vs BKT, Elo, DKT and SAKT on 16M practice attempts | AUC 0.742, +0.152 over the hand-set rule it replaced, exact serving parity |
| [VARUNA](https://github.com/Amarnath10i/VARUNA) | Flood forecasting on 239 Indian river catchments: regional LSTM, LightGBM, conceptual models, conformal intervals, flood triggers | Median NSE 0.44; flood-day interval coverage from 6.5% to 62% |
| [car_manual_assistant](https://github.com/Amarnath10i/car_manual_assistant) | Question answering over a 416-page car manual in English, Hindi and Telugu, with abstention | Page Hit@5 0.92 / 0.84 / 0.80; abstention AUROC 0.91–0.95 |
| [neural-operators](https://github.com/Amarnath10i/neural-operators) | Fourier Neural Operators vs DeepONet, CNN and linear baselines on Burgers and Darcy flow, with tested solvers | 0.39% error on Burgers; "zero-shot super-resolution" measured to be no better than interpolating the coarse prediction |

Also: [LAMA-EmbodiedAI](https://github.com/Amarnath10i/LAMA-EmbodiedAI) (an agent that learns object affordances under an interaction budget), [autoeng-studio](https://github.com/Amarnath10i/autoeng-studio) (vehicle design and simulation with stated uncertainty), and [repo-runner](https://github.com/Amarnath10i/repo-runner) (paste a GitHub URL, get a live demo).

### Research

- [Hyperspectral–multispectral image fusion](https://github.com/Amarnath10i/Research-On-Hyperspectral-ImageFussion): when fusion is identifiable and what a network merely invents (ongoing)
- DAXNet: polyp segmentation with edge-aware state-space models (code on publication)

### Open source

Open pull requests to [docling](https://github.com/docling-project/docling/pull/4600), [uutils/coreutils](https://github.com/uutils/coreutils/pull/14845), [transformers.js](https://github.com/huggingface/transformers.js/pull/1753) and [hermes-agent](https://github.com/NousResearch/hermes-agent/pull/122473).

### Tools

Python, SQL, PyTorch, LightGBM, scikit-learn, pandas · FastAPI, PostgreSQL, Docker · TypeScript, React, Next.js
