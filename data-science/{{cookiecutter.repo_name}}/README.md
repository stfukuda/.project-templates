# {{ cookiecutter.project_name }}

{{ cookiecutter.description }}

## Requirements

To use this project, you need to install the following components:

+ [Docker](https://www.docker.com/)

## Project Organization

    .
    ├── configs            <- Configuration files to be read by hydra.
    │
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── logs               <- Training log, lint log file.
    │
    ├── models             <- Trained and serialized models or model predictions, model summaries.
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-initial-data-exploration.ipynb`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting.
    │
    ├── src                <- Source code for use in this project.
    |   ├── __init__.py    <- Makes src a Python module.
    |   ├── data           <- Scripts to download or generate data.
    |   ├── features       <- Scripts to turn raw data into features for modeling.
    |   ├── models         <- Scripts to train models and then use trained models to make predictions.
    |   └── visualization  <- Scripts to create exploratory and results oriented visualizations.
    |
    ├── .env               <- Environment variables loaded by docker-compose.yml and the python-dotenv library.
    |
    ├── .gitattributes     <- A file that sets a line feed code for each specified file in Git.
    |
    ├── .gitignore         <- Files for setting files that you want to intentionally exclude from tracking in the Git repository.
    |
    ├── docker-compose.yml <- A file in which the configuration (services) of the docker container to be used is written.
    |
    ├── LICENSE            <- License file.
    |
    └── README.md          <- The top-level README for developers using this project.

--------

## Credits

Project based on the [cookiecutter data science project template.](https://drivendata.github.io/cookiecutter-data-science/) #cookiecutterdatascience
