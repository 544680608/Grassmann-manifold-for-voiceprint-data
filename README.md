# Grassmann-manifold-for-voiceprint-data
Grassmann manifold for voiceprint data

 import numpy as np
from scipy.linalg import svd
import scipy.io
import numpy as np
from scipy.linalg import eig
from scipy.linalg import svd


######考虑到输入数据是我们采集的数据，数据是保密的，所以读者只能根据实际需要更改输入；
###### 为了输入方便，此代码没有使用ten-fold cross 验证；
###### 这里只提供 project kernel，BCkernel 和canonical kernel读者可以自行更改，最后再加入经验核对齐操作即可。





