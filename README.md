# EDA-project

This project is centered around exploratory data analysis techniques and presentation of results to a client.

## Requirements

- pyenv
- python==3.11.3

## Virtual Environment

In this repo you will find a [requirements.txt](requirements.txt) file. It contains all the libraries you will need for this exercise.

Plotly in Jupyter Lab requires node. If you haven't installed it yet, you can do it with the following commands:

```sh
brew update
brew install node
```

You can install the virtual environment and the required packages like this:

```sh
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip  
pip install -r requirements.txt
```

If you are working on Windows type the following commands in the PowerShell:

```sh
python -m venv .venv
.venv\Scripts\Activate.ps1
```
### Unit testing (Optional)

If you write python scripts for your data processing methods, you can also write unit tests. In order to run the tests execute in terminal:

```bash
pytest
```

This command will execute all the functions in your project that start with the word **test**.