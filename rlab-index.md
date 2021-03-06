--------------------------------------

[[Click here to go back to course home]](https://gmukherjee.github.io/gsba604/)

-------------------------------------

## Links to R labs
  
|Session| Link |
|-------|------|
|Tutorial on R basics|[Click here](https://www.dropbox.com/s/kx0ubups6bapmpe/1-R-tutorial.pdf?raw=1) @1|
|Tutorial on R Markdown | [Click here](https://www.dropbox.com/s/tvb9vn3qjluumoh/2-R-markdown.pdf?raw=1)|
|R-Lab 1| [Click here](https://www.dropbox.com/s/8c4lf3pbjb99xfj/lab-1.R?raw=1)|
|R-Lab 2| [Click here](https://www.dropbox.com/s/sd3ri05zjp7i2dh/lab-2.pdf?raw=1)|
|R-Lab 3| [Click here](https://www.dropbox.com/s/ie2hmqcy5etslaj/lab-3.pdf?raw=1)|
|R-Lab 4| [Click here](https://www.dropbox.com/s/7ikfxnatdn5kzub/lab-4.pdf?raw=1)|
|R-Lab 5| [Click here](https://www.dropbox.com/s/8yty4f935wz3tdr/lab-5.pdf?raw=1)|
|Tutorial on making an R Package | [Click here](https://www.dropbox.com/s/93art9d97mg90pz/building-R-packages.pdf?raw=1) @2|
|R-Lab 6| [Click here](https://www.dropbox.com/s/awygk31wf5ls39o/lab-6.pdf?raw=1)|
|R-Lab 7| [Click here](https://www.jaredknowles.com/journal/2013/11/25/getting-started-with-mixed-effect-models-in-r)@ 3|
|R-Lab 8| [Click here](https://www.jaredknowles.com/journal/2014/5/17/mixed-effects-tutorial-2-fun-with-mermod-objects)@ 3|
|R-Lab 9| [Click here](https://www.dropbox.com/s/rsgdhrc9d51tjnx/lab-9.pdf?raw=1)|
|R-Lab 10| [Part A](https://www.dropbox.com/s/9pq9n1nmk1twigd/lab-10-a.R?raw=1) and [Part B](https://www.dropbox.com/s/x93fyk0yq06c9b4/lab-10-b.R?raw=1) @2|

@1^[prepared by Rudy Angeles for Stats 305 @ Stanford]

@2^[prepared by Trambak Banerjee]

@3^[directly from Jared Knowles notes]

The R labs are from the following resources:

* J.J. Faraway. Practical Regression and Anova using R
* G. James, D. Witten, T. Hastie, and R. Tibshirani. An introduction to statistical learning.  New York: springer. 2013. 
* A. Agresti. Foundations of Linear and Generalized Linear Models, Wiley 2015. 
* A. Gelman and Hill. Data Analysis Using Regression and Multilevel Hierarchical Models, 2007.  

--------------------------------------------------------------------------


## Referencing of R-labs with Class Notes

* <b> Module 1. Linear Regression Methods in Fixed, Moderate and High dimensions</b>
  * Ordinary Least Squares (OLS)
    * Estimation [R-lab 1]
      * BLUE, Gauss-Markov Theorem
    * Confidence Sets [R-lab 2]
      * Confidence Interval for a single Linear Parametric Function (LPF)
      * Confidence Regions for multiple LPFs
      * Simultaneous Confidence Intervals for multiple LPFs
      * Prediction Interval
    * Hypothesis Testing [R-lab 2]
      * Testing for the signifance of a single LPF
        * Testing for the signifance of individual predictors: t-test
      * ANOVA Table and testing hypothesis involving several LPFs 
        * Testing for the signifance of the entire model: F-test
  * Variable/Model Selection [R-Lab 3]
    * Forward Selection
    * Backward Selection
    * AIC, BIC, Cp
    * Best Subset
    * Cross Validation (CV)
  * Penalized/Shrinkage Methods For Moderate and High dimensional problems [R-lab 3]
    * Multicollinearity and VIF 
    * Curse of Dimensionality 
    * Ridge
    * Lasso
    * Computational complexity, path algorithms, LARS and glmnet
    * Selecting the penalty parameter by CV
    * Elastic Net
    * Group Lasso
    * Fused Lasso
  * Categorical Predictors [R-lab 4]
  * Least Squares in Heteroskedastic Models [R-lab 4]
    * Generalized Least Squares
    * Weighted Least Squares
  * Quantile Regression [R-lab 4]  
  * M-Estimation [R-lab 4] 
    * Huber loss and Robustness
  
  
* <b> Module 2. Non-Linear Regression</b>
  * Transforming the Response: Box-Cox method [R-lab 5]
  * Transforming the Predictors [R-lab 5]
    * Polynomial Regression
    * Regression Splines
    * Local Regression
    * Generalized Additive Models (GAM)
    * Dimension Reduction Methods
      * Principal Component Regression
      * Partial Least Squares
   
 * <b> Module 3. Generalized Linear Models (GLM) </b>
   * Popular Models  [R-lab 6]
     * Binary Data (Logit and Probit)
     * Multinomial Response Models
     * Count Data (Poisson GLM)
      - Models for Contingency tables
      - Connections between logistic and log-linear models
     * Quasi-likelihood Models
   * General framework for studying theory and methods for GLMs
     * Moving Beyond Gaussianity
     * Exponential Dispersion Family
     * Divergence and general inference principles
   * Random Effects, Correlated Responses and GLMM [R-lab 9]
     * Normal Linear Mixed Model [R-lab 7]
     * Generalized Linear Mixed Model (GLMM) [R-lab 8]
   <!-- * Joint Modeling and Time to event-->
   * High-dimensional (HD) Versions

         
* <b> Module 4. Causal Inference</b> 
  * Causal Inference using regression on the treatment variables [R-lab 10 A]
  * Causal inference using more advanced models [R-lab 10 B]
   
--------------------------------------

[[Click here to go back to course home]](https://gmukherjee.github.io/gsba604/)

-------------------------------------
