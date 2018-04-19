# Hurst Exponent
Calculates the Hurst exponent of a time series based on Rescaled range (R/S) analysis.  
Reference: https://en.wikipedia.org/wiki/Hurst_exponent 
# Environment  
Python 3.6.2 AMD64  
numpy (1.13.3+mkl)  
pandas (0.20.3)  
# User Guide  
import Hurst  
ts = list(range(50))  
hurst = Hurst.hurst(ts)
# Tips
The input ts has to be object list(n_samples,) or np.array(n_samples,).
