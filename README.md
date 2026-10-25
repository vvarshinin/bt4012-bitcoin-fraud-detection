# BT4012 Bitcoin Fraud Detection

## Requirements

- Python 3.11
- Jupyter Notebook
- The packages listed in `requirements.txt`

## Setup

Create and activate a Python 3.11 virtual environment.

```bash
python3.11 -m venv .venv
source .venv/bin/activate
```

Install the project dependencies:

```bash
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
brew install libomp
```

## Running the notebook

Register the virtual environment as a Jupyter kernel:

```bash
python -m ipykernel install --user --name bt4012-fraud --display-name "Python (BT4012 Fraud)"
python -m jupyter notebook
```