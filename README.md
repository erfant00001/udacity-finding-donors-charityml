# Finding Donors for CharityML

![Python](https://img.shields.io/badge/Python-3.x-blue) ![scikit-learn](https://img.shields.io/badge/scikit--learn-supervised-f7931e) ![License](https://img.shields.io/badge/License-MIT-green) ![Udacity](https://img.shields.io/badge/Udacity-Intro%20to%20Machine%20Learning-02b3e4)

A **supervised learning** project that predicts whether an individual earns more than **\$50,000 / year** from U.S. census data, to help a fictional charity (*CharityML*) target likely donors.

> Completed for the **Udacity — Intro to Machine Learning Nanodegree** (Supervised Learning).

## Overview

The notebook walks through a full supervised-learning workflow:

- exploring and preprocessing the census data (log-transforming skewed features, normalising, one-hot encoding),
- establishing a naive-predictor benchmark,
- training and comparing several `scikit-learn` classifiers,
- tuning the best model with grid search, and
- examining feature importance to see which attributes most predict income.

## Files

| File | Description |
|------|-------------|
| `finding_donors.ipynb` | The complete project notebook |
| `visuals.py` | Helper visualisation code (provided by Udacity) |
| `census.csv` | The dataset (~32k records) — tracked with Git LFS |
| `project_description.md` | Original project brief |

## Data

A modified version of the [UCI Census Income](https://archive.ics.uci.edu/ml/datasets/Census+Income) dataset (Ron Kohavi, 1996): ~32,000 records, 13 features, target `income` ∈ {`<=50K`, `>50K`}.

## Acknowledgements

Starter code, dataset, and specification provided by **Udacity** (*Intro to Machine Learning Nanodegree*). Implementation by Erfan Taatizadeh.

## ⚠️ Academic integrity

Shared as a personal portfolio / learning reference. If you are enrolled in this Nanodegree, do **not** submit this code as your own — see the [Udacity Honor Code](https://www.udacity.com/legal/en-us/honor-code).

## License

[MIT License](LICENSE) for the author's contributions; Udacity starter code remains Udacity's property.
