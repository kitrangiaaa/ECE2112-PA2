# NUMERICAL PYTHON (NUMPY)

## 1. NORMALIZATION PROBLEM: 
#### <p align="justify"> Normalization is one of the most basic preprocessing techniques in data analytics. This involves centering and scaling process. Centering means subtracting the data from the mean and scaling means dividing with its standard deviation. Mathematically, normalization can be expressed as:  𝑍 = 𝑋 − 𝑥̅  / 𝜎. In Python, element-wise mean and element-wise standard deviation can be obtained by using .mean() and .std() calls. In this problem, create a random 5 x 5 ndarray and store it to variable X. Normalize X. Save your normalized ndarray as X_normalized.npy

<img width="1127" height="41" alt="Screenshot 2025-09-02 at 11 43 35 PM" src="https://github.com/user-attachments/assets/802c1e0d-3765-4bdd-bf53-825e2ec07dd0" />
<p align="justify"> First, I used the import numpy as np to access the NumPy Library. 

<img width="1127" height="413" alt="Screenshot 2025-09-02 at 11 52 01 PM" src="https://github.com/user-attachments/assets/20360cde-1188-47b0-b851-c50e3d0b40cf" />
<p align="justify"> I then proceed to use "x = np.random.random((5,5))" to produce a 5x5 array containing random sets of numbers. After printing it, I stored the mean formula in "a" and the standard deviation formula in "b". In the following code, I typed the normal formula, which is normal = (x-a)/b, and printed it again so that the normal value with respect to "x" will be shown.

## 2. DIVISIBLE BY 3 PROBLEM:
#### <p align="justify"> Create the following 10 x 10 ndarray which are the squares of the first 100 positive integers. From this ndarray, determine all the elements that are divisible by 3. Save the result as div_by_3.npy

<img width="1127" height="441" alt="Screenshot 2025-09-02 at 11 53 07 PM" src="https://github.com/user-attachments/assets/2d910e03-6d87-4b8d-9ba2-77b5f9867bd9" />
<p align="justify"> For the second problem, I input "k = np.arange(1,101)" to produce an array with values of 1-100. I stored the code in "i" to square the values of 1-100 and then reshaped it into a 10x10 array which I stored in "g". After that, I printed the values and stored the code responsible for making the values divisible by 3 in "t" and printed it again.
