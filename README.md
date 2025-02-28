# Bayesian Machine Learning Projects

## Project 1: wine

***Overview***

This project explores Bayesian statistics using a white wine dataset, covering:

* Part 1: Analysis of continuous predictors using normal and exponential likelihoods with conjugate priors
* Part 2: Analysis of wine quality using multinomial-Dirichlet models
* Part 3: Bayesian inference to compare alcohol content between different wine quality grades

***Requirements***

R with packages: tidyverse, dirmult, HDInterval

***Key Findings***

Large sample size reduces the impact of prior choices on continuous variables
Uninformative priors with high values can significantly impact categorical posterior distributions
Wines rated 'A' have significantly higher alcohol content than wines rated 'F' (difference: ~1.25-1.65%)

## Project 2: coal_disasters

***Overview***

This project explores MCMC methods and Bayesian modeling through two case studies:

***Part 1: Coal Mining Disasters Changepoint Analysis***

Implementation of a Gibbs sampler to detect when coal mining safety improved  
Comparison of different Metropolis-within-Gibbs approaches (uniform vs. local proposals)  
Evaluation of sampler efficiency through acceptance rates  

***Part 2: White Wine Quality Classification***

Bayesian logistic regression using brms to classify wine quality  
Variable selection and comparison of two different predictive models  
MCMC diagnostics including trace plots and forest plots  

***Key Findings***

Coal mining disasters showed a significant decrease (approximately 69%) after a changepoint around 1891-1892  
Sampling efficiency is highly dependent on proposal distribution design (7% vs. 68% acceptance rates)  
Wine quality is strongly predicted by density (negative relationship) and residual sugar (positive relationship)  

## Project 3: coffee_shops

***Overview***

This project applies hierarchical Bayesian modeling to analyze how store manager personality traits impact sales at a regional coffee shop chain:

* Hierarchical Model: Analysis of sales performance across 20 coffee shop locations using a random slopes design
* Fixed Effects: Examination of how conscientiousness and neuroticism affect sales of different product categories
* Random Effects: Identification of store-specific variations in performance beyond personality effects

***Key Findings***

Conscientiousness has a strong positive effect on food sales (1.36 units per SD increase) but a more modest effect on coffee sales (0.35 units)  
Neuroticism shows a trend toward negative effects on sales but with uncertainty in the estimates  
Substantial store-level variation exists in both baseline performance and food vs. coffee sales patterns  
Several stores significantly outperform expectations (Store 14: +3.46 SD above average)  
