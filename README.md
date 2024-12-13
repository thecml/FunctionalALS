# FunctionalALS
Source code for "A meaningful prediction of functional decline in amyotrophic lateral sclerosis based on multi-event survival analysis", 2024.
Under review.

Requirements
--------
To run the models, please refer to [Requirements.txt](https://github.com/thecml/functionalals/blob/main/requirements.txt).
The code was tested in a virtual environment with `Python 3.9`.

How to use
--------
1. Install requirements by running: pip install -r requirements.txt
2. Download the PRO-ACT dataset from [the PRO-ACT website](https://ncri1.partners.org/ProACT)
3. Make directories `mkdir data` and `mkdir results`
4. Put the PRO-ACT files inside the data directory and run `python src/make_dataset.py`
5. Train the survival models by running `python src/train_models.py`.

Citation
--------
TBA
