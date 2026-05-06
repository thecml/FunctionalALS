# A meaningful prediction of functional decline in amyotrophic lateral sclerosis based on multi-event survival analysis (2025)

**Published in PLOS ONE 20(11):1–16, 2025**  
[Full paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0336476)

This work introduces a multi-event survival model that predicts when ALS patients are likely to experience functional decline across five key abilities. Using the PRO-ACT dataset (N=3220), the method provides individualized survival curves for each function and enables counterfactual predictions to assess how changes in clinical variables affect expected decline.

Requirements
--------
To run the models, please refer to [Requirements.txt](https://github.com/thecml/functionalals/blob/main/requirements.txt).
The code was tested in a virtual environment with `Python 3.9`.

How to use
--------
1. Install requirements by running: `pip install -r requirements.txt`
2. Download the PRO-ACT dataset from [the PRO-ACT website](https://ncri1.partners.org/ProACT)
3. Make directories `mkdir data` and `mkdir results`
4. Put the PRO-ACT files inside the data directory and run `python src/make_dataset.py`
5. Train the survival models by running `python src/train_models.py`.

Citation
--------
If you find this paper useful in your work, please consider citing it.

```bibtex
@article{lillelund_meaningful_2025,
    doi = {10.1371/journal.pone.0336476},
    author = {Lillelund, Christian Marius and Kalra, Sanjay and Greiner, Russell and {The Pooled Resource Open-Access ALS Clinical Trials Consortium (PRO-ACT)}},
    journal = {PLOS ONE},
    title = {A meaningful prediction of functional decline in amyotrophic lateral sclerosis based on multi-event survival analysis},
    year = {2025},
    volume = {20},
    pages = {1-16},
    number = {11},
}
```
