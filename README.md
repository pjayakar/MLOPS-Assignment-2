# MLOps Assignment 2 — Hugging Face Fine-Tuning, Experiment Tracking & Model Deployment

Fine-tuning DistilBERT on the UCSD Goodreads book review dataset to classify reviews into 8 genres, with experiment tracking via Weights & Biases and model deployment to Hugging Face Hub.

## Setup Instructions

1. Clone the repository:
   git clone https://github.com/pjayakar/MLOPS-Assignment-2.git
   cd MLOPS-Assignment-2

2. Install dependencies:
   pip install -r requirements.txt

3. Run on Kaggle:
   Import MLOps-assignment2.ipynb into Kaggle, enable GPU T4 x2 under Settings → Accelerator, add WANDB_API_KEY and HF_TOKEN under Add-ons → Secrets, then run all cells.

## Results

| Metric    | Score  |
|-----------|--------|
| Accuracy  | 0.5888 |
| F1 Score  | 0.5933 |
| Eval Loss | 2.3896 |

## Links

- Kaggle Notebook: https://www.kaggle.com/code/pinakijg25ait2045/mlops-assignment-2
- Hugging Face Model: https://huggingface.co/pjayG25AIT2045/distilbert-goodreads-genres
- W&B Dashboard: https://wandb.ai/pinakijayakar01-iitj/mlops-assignment2
