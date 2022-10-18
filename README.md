# Color-2-pH-Value

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

This project offers a web server and a model that transforms a measurement based on the pH color scale to a reliable value of pH using Machine Learning. The work done here is based on [ygarg704/ph-value-recognition-based-on-rgb-color](https://github.com/ygarg704/ph-value-recognition-based-on-rgb-color) with some improvements on the model building and the web UI/UX.

## Prerequisites

- Python 3.8 or later
- Venv or conda

## Setup

First you need to setup your python virtual environment. If you are using venv use the command as follows:

```zsh
# Create virtual environment
python -m venv color_2_ph_value

# Activate your virtual environment
source ./color_2_ph_value/bin/activate
```

Then you need to install the required libraries using

```zsh
pip install -r requirements.txt
```
