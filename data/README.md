# Dataset

## Default of Credit Card Clients

**Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/350/default%2Bof%2Bcredit%2Bcard%2Bclients)

**Dataset ID:** 350

**Purpose:** Predict whether a credit-card client will default on their payment in the following month.

### How to obtain the data

The dataset is publicly available through the UCI Machine Learning Repository.

This project uses the `ucimlrepo` Python package to retrieve the dataset programmatically. Install the dependencies listed in the project's `requirements.txt` file, then load the dataset using the code in the data-loading module.

Personally, I downloaded myself the same dataset from [Kaggle's dataset repository](https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset).

### Data storage

Downloaded datasets and generated data files are excluded from Git to keep the repository lightweight and avoid committing unnecessary copies of source data.

- `data/raw/`: original downloaded files, if needed.
- `data/processed/`: derived datasets created during preprocessing.

These files are generated locally and are not included in the repository.

### Target variable

The target is `default.payment.next.month`, which indicates whether a client defaulted on their payment in the following month.

### Limitations

The dataset represents a historical credit-card client population in Taiwan. Results from this dataset should not be assumed to generalise to other countries, financial institutions, or current lending portfolios.