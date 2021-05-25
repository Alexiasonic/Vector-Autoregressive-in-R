# Vector-Autoregressive-in-R

#=======================================================================================================
# This script replicates the example in Kilian and Lutkepohl (2017), Structural Vector Autoregressive
# Analysis, Cambridge University Press, Chapter 9 (page 239-240).
#
# The exercise focuses on the identification of an oil price shock and its impact on inflation and 
# real GDP. 
#
# The oil price shock is identified by using a recursive scheme (that is through Cholesky
# decomposition of the VAR's reduced form residuals covariance matrix).
# 
# These R codes allow to compute impulse response functions (IRFs), Forecast Error Variance 
# Decomposition (FEVD) and Historical Decomposition (HD).
# 
# Author: Alessia Paccagnini (UCD) and Fabio Parla (CBI)
# contact: fabioparla123@gmail.com
# Dublin, May 2021
