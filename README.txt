This file explains the procedure to estimate the smooth local projections (SLP) in the terms Barnichon and Brownlees (2019).
Acknowledgements: The codes were retrieved from the supplementary material of Barnichon and Brownlees (2019) and adapted to the needs of the present paper. 
In particular, Mainfile.m, locproj.m locproj_cv, locproj.conf were retrieved from Barnichon and Brownlees (2019) supplementary material.
Instead, lagmaker and LP were retrieved from the Barcelona Summer School 2021 course material (Time Series Course) and a special mention goes to Lucca Gambetti and Nicolò Maffei-Faccioli. 


In order to replicate the main results of the paper, please note:



Panel A, B, C and D: 

In MainFile: 

1) Select load 'Dataset - Level - 1997-2019.mat'.

2) Select the variables corresponding to the log level specification.

3) Select the dependent variables one at a time. Remember you can choose:

a) MPU
b) SMU

4) Select the corresponding shock one at a time:

5) Select controls. Remember to include the linear trend (TT) in this specification and to check the autocorrelation function of the shock to include its lags (lags already created).

6) Run the code and get the IRFs and the 10% confidence interval one at a time.


Panel E and F:

In MainFile: 

1) Select load 'Dataset - Diff - 1997-2019.mat'.

2) Select the variables corresponding to the first difference of logs specification.

3) Select the dependent variables one at a time. Remember you can choose:

a) MPU
b) SMU

4) Select the corresponding shock one at a time.

5) Select controls. Remember to check the autocorrelation function of the shock to include its lags (lags already created).

6) Run the code and get the IRFs and the 10% confidence interval one at a time.



