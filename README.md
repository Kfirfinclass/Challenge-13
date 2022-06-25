# Challenge 13

This neural model was created to assist the team at Alphabet Soup to help them create a model that predicts whether applicants will be successful if funded by Alphabet Soup.

Original Model Results
268/268 - 0s - loss: 0.5528 - Accuracy: 0.7317 - 120ms/epoch - 448us/step
Loss: 0.5527744889259338, Accuracy: 0.7316617965698242

Alternative Model 1 Results
268/268 - 0s - loss: 0.5708 - Accuracy: 0.7303 - 120ms/epoch - 448us/step
Loss: 0.5708416104316711, Accuracy: 0.7302623987197876

Alternative Model 2 Results
268/268 - 0s - loss: 0.5963 - Accuracy: 0.7301 - 216ms/epoch - 806us/step
Loss: 0.5963131189346313, Accuracy: 0.7301457524299622

The original model produced the best apporach. 

## Technologies

import pandas as pd
from pathlib import Path
import tensorflow as tf
from tensorflow.keras.layers import Dense
from tensorflow.keras.models import Sequential
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler,OneHotEncoder
---

## Installation Guide

conda install -c conda-forge
python3 -m pip install tensorflow

---

## Usage

Review the 3 models.


---

## Contributors

Kfir Bar
kfirfinclass@gmail.com

---

## License

This code is exclusive to those who are provided a direct access. A user-key feature can be added later.
#Challenge-11
