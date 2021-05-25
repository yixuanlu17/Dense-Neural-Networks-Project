# 🏢Dense-Neural-Networks-Project🏢
This is my first Neural Network model I've done during my Master's term. 

## Dataset Information 
This dataset is famous Boston Housing Dataset 🤯 which contains information collected by the U.S Census Service concerning housing in the area of Boston Mass. It was obtained from the StatLib archive (http://lib.stat.cmu.edu/datasets/boston), and has been used extensively throughout the literature to benchmark algorithms. However, these comparisons were primarily done outside of Delve and are thus somewhat suspect. The dataset is small in size with only 506 cases.

This dataset, though small, is very representative. The code for this dataset can be used on other data, with universality. 

## Requirements 

### Libraries are required as follows
```
import pandas as pd 
import numpy as np 
from matplotlib import pyplot as plt #for plotting
from sklearn import preprocessing
```

## Results

<img width="499" alt="Screen Shot 2021-05-24 at 20 55 13" src="https://user-images.githubusercontent.com/83843271/119428370-58913f00-bcd2-11eb-9167-a630162f1b96.png">

```
_______________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
dense_66 (Dense)             (None, 64)                896       
_________________________________________________________________
dense_67 (Dense)             (None, 8)                 520       
_________________________________________________________________
dense_68 (Dense)             (None, 1)                 9         
=================================================================
Total params: 1,425
Trainable params: 1,425
Non-trainable params: 0
_________________________________________________________________
```


