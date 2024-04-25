
poetry init

bash '''Example
[tool.poetry]
name = "KC-House-Prices"
version = "0.2.0"
description = ""
authors = ["Alysson Vidal <alysson.vidal@ses.saude.com>"]
readme = "README.md"

[tool.poetry.dependencies]
python = "^3.11"

[build-system]
requires = ["poetry-core"]
build-backend = "poetry.core.masonry.api"
'''


poetry env info
poetry env info -p

poetry config virtualenvs.in-project true

poetry install

poetry sheel

deactivate



poetry add pandas
poetry add numpy
poetry add matplotlib
poetry add seaborn
poetry add scikit-learn
poetry add lightgbm
poetry add xgboost
poetry add optuna
poetry add shap
poetry add folium

poetry add --group dev jupyter





