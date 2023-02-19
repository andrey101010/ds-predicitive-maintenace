[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/andrey101010/ds-predicitive-maintenace/blob/main/05_Pump_Sensors.ipynb)

# Data Science Project: Predicitive Machine Maintenace 
For this is a Kaggle dataset, which was used in this project and can be found under the following link:
https://www.kaggle.com/datasets/nphantawee/pump-sensor-data

## Approach
The main goal in this project is to build a ML algorithm which can predict machine failure in advance. For goal the data is analysed with some statistics and a EDA is perfomed. After data cleaning and feature enginnering two commonly used ML algorothms are applied. In a systematic study several time intervals before machine failure are investigated.

## Conclusions
Random forest is able to predict the machine failure in the future. This plot shows the predicited machine status (orange trace) and the real machine status (blue trace).  The features were moved 5760 rows or minutes back to check whether the ml algorothm is still able to predict machien status.
 
![Image](/images/5760_in_advance.png)

## Environment 
Use the [requirements](requirements.txt) file in this repo to create a new environment. For this you can either use `make setup` or the following commands:

```BASH
pyenv local 3.10.10
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```
