# Stock Prediction MLOps

[![check.yml](https://github.com/sohang3112/stock-prediction-mlops/actions/workflows/check.yml/badge.svg)](https://github.com/sohang3112/stock-prediction-mlops/actions/workflows/check.yml)
[![publish.yml](https://github.com/sohang3112/stock-prediction-mlops/actions/workflows/publish.yml/badge.svg)](https://github.com/sohang3112/stock-prediction-mlops/actions/workflows/publish.yml)
[![Documentation](https://img.shields.io/badge/documentation-available-brightgreen.svg)](https://sohang3112.github.io/stock-prediction-mlops/)
[![License](https://img.shields.io/github/license/sohang3112/stock-prediction-mlops)](https://github.com/sohang3112/stock-prediction-mlops/blob/main/LICENCE.txt)
[![Release](https://img.shields.io/github/v/release/sohang3112/stock-prediction-mlops)](https://github.com/sohang3112/stock-prediction-mlops/releases)

Stock Prediction MLOps group project for IIT MTech (AI). Made by group members: Sohang, Ayush, Anish, Gargi, Ambeth..

## Installation

Use the package manager [uv](https://docs.astral.sh/uv/):

```bash
uv sync
```

## Usage

```bash
uv run stock-prediction-mlops
```

## MLOps Template Used

[CookieCutter - MLOps Package](https://github.com/fmind/cookiecutter-mlops-package) was used to initially generate basic template, which avoids the hassle of manually integrating MLOps tools.

These commands (given in above package) were used initially to generate files (they do NOT need to be run again):

```bash
$ pip install cookiecutter
$ cookiecutter gh:fmind/cookiecutter-mlops-package
```