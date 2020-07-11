# 将整数转换为one-hot的几种方法

## 1.np
利用单位矩阵的“维度:x_dim”和及其“索引:index”的方法
y = np.eye(x_dim)[x]
```py
import numpy as np
x_dim = 10
x = [1,2,3,4,5,6,7,8,9,10]
y = np.eye(x_dim)[x]
```
