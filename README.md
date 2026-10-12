# FragmentBERT: BERT-MLM and RL for Fragment-Based Molecule Optimization

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bhaskargiri4u/M.Tech.-Dissertation/blob/main/Final_Dissertation.ipynb)

Dissertation project. The notebook `Final_Dissertation.ipynb` runs in Google Colab and covers:

1. **Phase 1:** MOSES data preparation for BERT-MLM
2. **Phase 2:** FragmentBERT tokenizer
3. **Phase 3:** Masked language model pretraining
4. **Phase 4.1:** MLM-based fragment substitution
5. **Phase 4.2:** Chemical substitution analysis
6. **Phase 4.3:** RL optimization (Stable-Baselines3)

## Setup
```
pip install -r requirements.txt
```
Place the MOSES subset at `data/moses_1L.csv` (the notebook currently reads it from Google Drive).

## Run
Open the notebook in Colab (GPU recommended) and run the phases in order.
