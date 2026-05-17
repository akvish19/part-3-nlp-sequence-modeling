# Part 3: NLP and Sequence Modeling Mini Project

This project demonstrates a basic NLP pipeline using a customer support sentiment dataset.

## Contents

- `notebook.ipynb` — analysis, preprocessing, baseline model, sequence model architecture, and results.
- `requirements.txt` — Python dependencies needed to run the notebook.
- `customer_support_text_classification.csv` — dataset used for the notebook.
- `results/` — generated evaluation and prediction artifacts.

## How to run

1. Create a Python environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```
2. Open `notebook.ipynb` in Jupyter or VS Code and run all cells.

## Notes

- The notebook compares TF-IDF + Logistic Regression with a sequence-based LSTM architecture.
- It includes a reflection on RNNs, LSTMs, attention, and transformers.
