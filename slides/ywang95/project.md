
# How Cox Modeling Works

- In Cox modeling, every observed unit might have one or more observations, each with its own corresponding row including time stamps, event data and covariates (size). 
- The covariate are treated as predictors while the others (time stamps and event columns) are used to derive relative risk.

# Identifying the link function 

- For each of the 10 products in the KOffice Suite a **link function** needs to be identified which is achieved by plotting each covariate against log-relative risk
- The fundamental reason for this is to find a transformation of size as a covariate so that the same differences in the transformed covariate values will have the same multiplicative effect on the hazard, helping preserve the proportionality assumption in the Cox models
- According to the paper, it was observed that all but one of these product had a logarithmic curve when their link function graphs were plotted.
- Given this commonality, for this study *ln size* will be used as a predictor instead of just *size*
- The link function will then be used to find the functional-form of the size-defect relationship


