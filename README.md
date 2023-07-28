# ParametricContinuousDistributionEstimation
This work was done using Jupyter Notebook and the Python programming language. The following libraries were used: matplotlib, numpy, pandas, scipy. 
To use this project, you need to move the file "mars.txt" to the path "D:\mars.txt."

I have studied the methods of parametric estimation of the distribution of a continuous indicator and mastered the capabilities of Python libraries for conducting parametric distribution estimation.

During the work, the distribution of service time was estimated for each individual operator. For each sample:
- Histograms and/or kernel density function plots were analyzed, and assumptions were made about possible distribution laws (minimum of 4 variants).
- The likelihood of the identified distributions was tested using the Kolmogorov-Smirnov goodness-of-fit test.
- For the most probable distribution, the following were displayed on the screen:
  a) Estimates of the parameters of this distribution.
  b) The plot of the estimated probability density function along with the histogram and/or kernel density function.
  c) The plot of the estimated distribution function along with the empirical distribution function.
  d) The probability paper of this distribution along with the theoretical line.

Using the two-sample Kolmogorov-Smirnov test, it was checked whether the distributions of service time for different operators are the same.
