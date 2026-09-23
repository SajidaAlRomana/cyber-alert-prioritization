# cyber-alert-prioritization
ML-based cyber alert prioritization using Random Forest and SHAP on the NSL-KDD dataset.

## Setup

The notebook loads the NSL-KDD dataset from a local file path. Before running it, update the file paths in the data-loading cells (where `pd.read_csv` is called) to point to your own local copy of `KDDTrain+.txt` and `KDDTest+.txt`. Download NSL-KDD from [Kaggle](https://www.kaggle.com/datasets/hassan06/nslkdd) if you don't already have it (the official UNB page has since taken the direct download offline)
