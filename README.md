# PANDA-and-NUMPY
All the details about PANDA and NUMPY
# PANDAS(1/10/2025)
import numpy as np

import pandas as pd

import matplotlib.pyplot as plt

import glob

import re

import math

import warnings

warnings.filterwarnings("ignore")

Series

Create Series

#Create series from Nump Array

v = np.array([1,2,3,4,5,6,7])

s1 = pd.Series(v)

s1


dtype: int32

#Datatype of Series

s1.dtype

dtype('int32')

