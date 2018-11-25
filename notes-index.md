
Table of Contents
-----------------

* <b> Module 1. Linear Regression Methods in Fixed, Moderate and High dimensions </b>
  * Ordinary Least Squares (OLS)
    * Estimation
      * BLUE, Gauss-Markov Theorem
    * Confidence Sets
      * Confidence Interval for a single Linear Parametric Function (LPF)
      * Confidence Regions for multiple LPFs
      * Simultaneous Confidence Intervals for multiple LPFs
      * Prediction Interval
    * Hypothesis Testing
      * Testing for the signifance of a single LPF
        * Testing for the signifance of individual predictors: t-test
      * ANOVA Table and testing hypothesis involving several LPFs 
        * Testing for the signifance of the entire model: F-test
  * Variable/Model Selection
    * Forward Selection
    * Backward Selection
    * AIC, BIC, Cp
    * Best Subset
    * Cross Validation (CV) [[Download Slides]](https://www.dropbox.com/s/13qskvow8ytv9cf/cross-validation.pdf?dl=0) 
  * Penalized/Shrinkage Methods For Moderate and High dimensional problems
    * Multicollinearity and VIF 
    * Curse of Dimensionality 
    * Ridge
    * Lasso
    * Computational complexity, path algorithms, LARS and glmnet
    * Selecting the penalty parameter by CV
    * Elastic Net
    * Group Lasso
    * Fused Lasso
  * Categorical Predictors
  * Least Squares in Heteroskedastic Models 
    * Generalized Least Squares
    * Weighted Least Squares
  * Quantile Regression   
  * M-Estimation
    * Huber loss, Robustness and rlm R package
  
  
* <b> Module 2. Non-Linear Regression</b>
  * Transforming the Response: Box-Cox method
  * Transforming the Predictors
    * Polynomial Regression
    * Regression Splines
    * Local Regression
    * Generalized Additive Models (GAM)
    * Dimension Reduction Methods
      * Principal Component Regression
      * Partial Least Squares
<!-- * Regression Trees-->  
<!-- * Neural Networks-->
    
   
 * <b> Module 3. Generalized Linear Models (GLM) </b>
   * Popular Models
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
   * Random Effects, Correlated Responses and GLMM
     * Normal Linear Mixed Model
     * Generalized Linear Mixed Model (GLMM)
   <!-- * Joint Modeling and Time to event-->
   * High-dimensional (HD) Versions
     * Estimation in HD glm and glmnet R package
     * Hypothesis testing in HD glm
     * Estimation in HD lmm 
     * Estimation in HD glmm with glmmlasso
     * Testing goodness of fit in glmm
         
* <b> Module 4. Causal Inference</b>
  * Causal Inference using regression on the treatment variables
    * Causal inference and predictive comparisons
    * Randomized experiments and Observational studies
    * Ignorable treatment assignments

  * Causal inference using more advanced models
    * Imbalance and lack of complete overlap
    * Propensity score matching
    * Regression discontinuity
    * Estimating causal effects indirectly using instrumental variables

-------------------------------------------------------------------------

[[Click here to download all notes]](https://www.dropbox.com/sh/75h9in74cck1nc0/AADnZ_Eodqh5z9cm798pa8r0a?dl=0)

--------------------------
Links to Separate Modules
-------------------------

Modules 1 and 2 
  * [Click here to download](https://www.dropbox.com/s/azj7dm228czl4ui/m1-and-2.pdf?raw=1)

Module 3 (Click links below to download sub-parts)
  * [[Part 1: Binary data]](https://www.dropbox.com/s/drxbnn0ydkjrndl/m3-binomial-glm.pdf?raw=1) 
  * [[Part 2: Count data]](https://www.dropbox.com/s/62zwb9e4weyz07f/m3-poisson-glm.pdf?raw=1) 
  * [[Part 3: Exponential Family]](https://www.dropbox.com/s/aucleen0392kx00/m3-exp-family.pdf?raw=1) 
  * [[Part 4: Misc and Mixed Models]](https://www.dropbox.com/s/wr9fddg6u5wyv4d/m3-misc-and-glmm.pdf?raw=1)
  * [[Part 5: High Dimensional GLM]]()
  * [[Part 6: High Dimensional GLMM]]() 
  
Module 4
* [Click here to download](https://www.dropbox.com/s/7t236nn1ijw8kg0/causal-inference.pdf?raw=1)
