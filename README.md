# R-vs-Python

RとPythonで同じ操作をしたい

Rの`matrix`とPythonのnumpyの`numpy.array`

足し算

```R
> test1 <- matrix(c(c(1, 2, 3), c(2, 3, 4)), nrow = 3)
> test2 <- matrix(c(c(1, 3, 5), c(2, 4, 6)), nrow = 3)
> test1 + test2
     [,1] [,2]
[1,]    2    4
[2,]    5    7
[3,]    8   10
```

```Python
>>> import numpy as np
>>> test1 = np.array([[1, 2, 3], [2, 3, 4]]).T
>>> test2 = np.array([[1, 3, 5], [2, 4, 6]]).T
>>> test1 + test2
array([[ 2,  4],
       [ 5,  7],
       [ 8, 10]])
```
