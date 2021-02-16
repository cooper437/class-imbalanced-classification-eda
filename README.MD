## Class Imbalanced Modeling

A toy dataset of cargo shipment records along with their respective characteristics. We perform EDA and then train a simple tree-based classifier to predict the country of origin. The intention here is to spend a few hours exploring mitigation techniques for training machine learning models on class imbalanced datasets as certain countries in this dataset are much better represented than others.

To keep things simple all code including EDA, data/feature cleaning, model training, and model evaluation is in one notebook ./eda_train_eval.ipynb.

### Data
Unzip data files in the data directory. The notebook assumes the data is in the following directory structure:

data/ds-project-train.csv

data/ds-project-validation.csv

### Dependencies https://python-poetry.org/

Python 3.11.4 was used for this project.
Poetry was used for managing dependencies. To install dependencies run:

```bash
$ poetry install
$ poetry shell
```

With dependencies installed, and the virtual environment activated, the notebook can be run top-to-bottom in entirety to reproduce the results. I used VSCode with the Jupyter extension to run the notebook but it should work fine in Jupyter Lab as well.
