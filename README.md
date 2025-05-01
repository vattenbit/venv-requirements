# venv-requirements
This repository stores the latest requirements for my experiments.

## Venv list

| Name | Python Version | Description              |
|-----------------|----------------|--------------------------|
| ansible11       | 3.x            | Virtualenv for Ansible 11|

## Generate Venv
First, you need to create a virtual environment using Python 3
```bash
python3 -m venv ansible11
```
Next, activate the virtual environment and install the dependencies listed in `requirements.txt` using the `pip` tool.
```bash
source ansible11/bin/activate
pip install -r ansible11/requirements.txt
```