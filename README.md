MLProjectStructure - Template
==============================

A short description of the project.

Project Organization
------------

    ├── .gitignore         <- The .gitignore file specifies things that git should ignore. This default template includes entries for R, Python and VS Code.
    │     
    ├── LICENSE
    │   
    ├── README.md          <- Manual
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g. generated with `pip freeze > requirements.txt`.
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported.
    │
    ├── assets             <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting.
    │
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries.
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │   
    └── src                <- Source code for use in this project.
        ├── __init__.py    <- Makes src a Python module.
        │
        ├── exception.py   <- Custom exception file to get info about exception like which file, which line.
        │
        ├── logger.py      <- Custom logger to log basic info.
        │
        ├── utils.py       <- Helper script for evaluation or other common stuffs.
        │
        ├── components     <- Scripts to turn raw data into features for modeling.
        │
        └── pipeline       <- Scripts to train models and then use trained models to make
            │                 predictions.
            ├── predict_model.py
            └── train_model.py





