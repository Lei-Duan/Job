
### Normailty
The normality assumption does not affect the variance or the bias of the OLS estimates. OLS estimates may still be BLUE without the normality assumption. However, material deviations from the normality assumption may mean that the p-values (before and after HAC corrections) are not reliable.


### Correcting for Heteroscedasticity & Autocorrelation
There is conflicting evidence that the residuals are heteroscedastic. All tests show that the residuals are first-order autocorrelated. **Hence, the OLS estimates are inefficient, unbiased, and consistent. In other words, the p-values from OLS are too small. We need to correct the p-values in order to perform valid statistical inference.** These corrections are called heteroskedasticity and autocorrelation consistent (HAC) methods.

Two popular corrections are:

1. Newey-West
2. Andrews

Both corrections leave the OLS coefficient unaltered. However, the corrections increase the standard errors (and increase the p-values) of each coefficient estimate

### efficiency vs biased

http://www.1point3acres.com/bbs/thread-431724-1-1.html


### Recursion and Dynamic Programming   
https://stackoverflow.com/questions/1065433/what-is-dynamic-programming   

### what is Hadoop ( in Chinese )    
https://chu888chu888.gitbooks.io/hadoopstudy/content/Content/3/chapter3.html
