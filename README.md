# Data Science Project Predicitive Machine Maintenace 
For this is a Kaggle dataset, which was used in this project and can be found under the following link:
https://www.kaggle.com/datasets/nphantawee/pump-sensor-data

The main goal in this project is to build a ML algorithm which can predict machine failure in advance. For goal the data is analysed with some statistics and a EDA is perfomed. After data cleaning and feature enginnering two commonly used ML algorothms are applied. In a systematic study several time intervals before machine failure are invesytigated.

# Environment 
Use the [requirements](requirements.txt) file in this repo to create a new environment. For this you can either use `make setup` or the following commands:

```BASH
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```