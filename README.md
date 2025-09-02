# NUMERICAL PYTHON (NUMPY)

## 1. NORMALIZATION PROBLEM: 
#### <p align="justify"> Normalization is one of the most basic preprocessing techniques in data analytics. This involves centering and scaling process. Centering means subtracting the data from the mean and scaling means dividing with its standard deviation. Mathematically, normalization can be expressed as:  𝑍 = 𝑋 − 𝑥̅  / 𝜎. In Python, element-wise mean and element-wise standard deviation can be obtained by using .mean() and .std() calls. In this problem, create a random 5 x 5 ndarray and store it to variable X. Normalize X. Save your normalized ndarray as X_normalized.npy

<img width="1127" height="41" alt="Screenshot 2025-09-02 at 11 43 35 PM" src="https://github.com/user-attachments/assets/802c1e0d-3765-4bdd-bf53-825e2ec07dd0" />
<p align="justify"> First, I used the import numpy as np to access the NumPy Library. 

<img width="1127" height="413" alt="Screenshot 2025-09-02 at 11 52 01 PM" src="https://github.com/user-attachments/assets/20360cde-1188-47b0-b851-c50e3d0b40cf" />
<p align="justify"> I then proceed to use "x = np.random.random((5,5))" to produce a 5x5 array containing random sets of numbers. After printing it, I stored the mean formula in "a" and the standard deviation formula in "b". In the following code, I typed the normal formula, which is normal = (x-a)/b, and printed it again so that the normal value with respect to "x" will be shown.

