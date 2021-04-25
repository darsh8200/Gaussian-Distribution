# Gaussian-Distribution

## **TASK 1**

The below code is starting about the gaussian distribution which is the very base of regression (different types of kernels). It firstly divides the main equation into small different parts which in further consummate to yield gaussian distribution which are bivariate and all plots are mostly handled by plotly library as it provide diversed resources for plotting.

## **TASK 2**

Cholesky Decomposition is used in this code for constructing valid covariance matrix which will help us to get multiple samples of gaussian distribution for N=3 and N=5. In, reality we need our base covariance matrix positive definite (basic for gaussian distribution). 

## **TASK 3**

Here, actual and obtained values of mean, variance and covariance are compared to get a picture that contructed and generated samples resembles with original ones, which, in long run helps us to visualize the data more precisely.

## **TASK 4**

For this part, dimension of gaussian are shoot up to 100 dimensions in order to see how covariance function i.e. kernel works and how it yields us a covariance matrix. Also, all 3 kernels which are developed in code are visualized through a heatmap

## **TASK 5**

Here, the former code is animated via a heatmap by varying different hyper parameters of the many kernels which are being used in order to develop a covariance matrix

## **TASK 6**

For the below 3 tasks, covariance function which's used is squared exponential and for this part pattern observing is needed i.e what is been infered from animating covariance matrix.

## **TASK 7**

The dimension of gaussian distribution is now taken to 10 but now the mean and covariance, all are conditioned on the part that X1 = constant (2 dimension) and X2 = varying(8 dimension). That is, whole X is divided in two part one constant and one varying. Furthermore, covariance of unconditional and conditional are being observed on a heatmap.

## **TASK 8**

Here, one other part is included that 95% confidence interval which means we need a interval around the mean for 95% and it have been produced by a function in the below code. Furthermore, conditional and unconditional mean are being visualized.

