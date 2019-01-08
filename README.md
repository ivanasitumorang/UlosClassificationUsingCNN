# UlosClassificationUsingCNN
Klasifikasi gambar ulos menggunakan CNN  

import cv2, os  
import numpy as np  
import tensorflow as tf   
import matplotlib.pyplot as plt  
import pandas as pd  
import pickle 

from sklearn.utils import shuffle  
from tqdm import tqdm 
from keras.models import *  
from keras.layers import *  
from keras.optimizers import *  
from keras import backend as K  
from sklearn.cross_validation import train_test_split  
from sklearn.model_selection import StratifiedKFold  
from keras.utils import np_utils  
from contextlib import redirect_stdout  

# Initialize  
Pastikan sudah menginstall library berikut :  
  Keras  
  Tensorflow  
  Pickle  
  Pandas  
  Cv2    
  Os   
  Numpy  
  Matplotlib  
  Sklearn  
  
# Cara install library :  
  Menggunakan conda   
    Contoh : conda install -c conda-forge keras   (Untuk library keras)  
    
  Menggunakan pip  
    Contoh : pip install tensorflow   (Untuk library tensorflow)  
