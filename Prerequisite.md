# Prerequisite

Make sure you have:
1. `python 3.11+ (or higher)` installed
2. `Azure CLI` installed

## Python Environment

Make sure you have `python 3.11+ (or higher)` installed.

- Check python version
```bash
python --version
```

> If your python version is not 3.11+, please install python 3.11+ from [python.org](https://www.python.org/downloads/).

- Create a virtual environment
```bash
python -m venv .venv
```

- Activate the virtual environment
```bash
.venv\Scripts\activate     # Windows PowerShell

source .venv/bin/activate   # Mac/Linux
```

- Update pip
```bash
pip install --upgrade pip
```

- Install dependencies
```bash
pip install -r requirements.txt
```

## Azure Environment

- Install Azure CLI (check [azure cli](https://learn.microsoft.com/cli/azure/install-azure-cli))
```bash
# For Windows
winget install --exact --id Microsoft.AzureCLI

# For Linux
curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash

# For Mac (if you have brew)
brew update && brew install azure-cli
```

- Check Azure CLI version
```bash
az --version
```

- Azure CLI login and select subscription
```bash
az login
```

- Check Azure CLI default subscription
```bash
az account show
```
