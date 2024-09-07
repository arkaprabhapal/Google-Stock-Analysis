# Google-Stock-Analysis
https://colab.research.google.com/drive/1k1_FRopQYCMNfxE8KT4j0LV1I17d-XUw?usp=sharing

import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.preprocessing import MinMaxScaler
from keras.models import Sequential
from keras.layers import Dense,LSTM,Dropout
data = pd.read_csv('Google_train_data.csv')
data.head()
