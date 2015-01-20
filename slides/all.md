% Get to know us!
% Apeksha Saxena, Gaurav Saraf
% Shivani Angane and Yiyang Wang

# Apeksha Saxena

- Second year Masters student
- Passionate about Animal Welfare
- Enjoys cooking, dancing and travelling
- Can be reached at asaxena2@ncsu.edu


# Gaurav Saraf

- Second year Masters student
- Enjoys reading and travelling
- Have maintained a nomadic life till now having lived in 10 different cities.
- Reach me at gsaraf@ncsu.edu

<img align=right src="../img/gaurav.png">

# Shivani Angane

- Second year Masters student
- Enjoy painting!
- Peek into my world of art from [here](http://reachshivani.yolasite.com)!
- Reach me at ssangane@ncsu.edu!

<img align=right src="../img/s_minion.jpg">


# Yiyang Wang

* Original&Official Name : Yiyang Wang
* English Name : Samuel Or Sam
* Game player ( contact me if u r good at dota2)

# Project Proposal Introduction

- One of the important features for any software is its size which is also a crucial estimate for the defect proneness of the software
- An interesting theory of relative defect proneness (RDP)  states that in large-scale software systems, smaller modules will be proportionally more defect-prone compared to larger modules
- Our project aims at studying the research results for ‘Defect Density Estimation’
- As part of this study, we would be replicating the results of [‘Theory of relative defect proneness’](http://link.springer.com.prox.lib.ncsu.edu/article/10.1007%2Fs10664-008-9080-x) for a software using available data sets to test the RDP theory
- A major part of this is investigating the functional form of the size-defect relationship for software modules
- With the results we can show that preferring the smallest-first strategy as opposed to the largest-first can lead to greater cost effectiveness and adhere to good quality assurance practices

# Cox Modelling Technique

* Software modules evolve, change in size, and experience corrective and non-corrective changes over time.
* Cox modelling with recurrent events is especially suited to model software quality of such software.
* An event corresponds to a defect fix made to a C++ class. The risk of experiencing an event at any time _t_ is modelled by a hazard functions and is given by:
 
  $\lambda_i(t) = \lambda_0(t)e^{\beta x_i(t))}$

* Conditional Cox models to be used with four states corresponding to 0, 1–5, 6–25, and >25 prior events, labeled from 1 to 4, respectively 

# Data Description
- For the purpose of this analysis ‘size’ is been measured in terms of the software’s Lines Of Code(LOC) at the module level
- The method makes use of 10 different products from the public repositories of KOffice suite(open source in C++)
- Each *class* is considered as a module as opposed to each *file* (object oriented programming)
- Data sets for each of the 10 products to be created using a set of predefined rules
- These rules are based on class additions, deletions, updations, the time that the changes were made, etc
- The data so formulated is fed to statistical analysis environment like R for cox modeling


# How Cox Modeling Works

- In Cox modeling, every observed unit might have one or more observations, each with its own corresponding row including time stamps, event data and covariates (size). 
- The covariate are treated as predictors while the others (time stamps and event columns) are used to derive relative risk.

# Identifying the link function 

- For each of the 10 products in the KOffice Suite a **link function** needs to be identified which is achieved by plotting each covariate against log-relative risk
- The fundamental reason for this is to find a transformation of size as a covariate so that the same differences in the transformed covariate values will have the same multiplicative effect on the hazard, helping preserve the proportionality assumption in the Cox models
- According to the paper, it was observed that all but one of these product had a logarithmic curve when their link function graphs were plotted.
- Given this commonality, for this study *ln size* will be used as a predictor instead of just *size*
- The link function will then be used to find the functional-form of the size-defect relationship



# In the morning


<center>

  Right     Left     Center     Default
-------     ------ ----------   -------
     12     12        12            12
    123     123       123          123
      1     1          1             1
    456     78         910          12
	 12     12        12            12
         29     29         29           29
	
Table:  Demonstration of simple table syntax.

</center>

The ziffness of dorkies must:

- Eat eggs
- Drink coffee
- Gobble sugar

# In the evening

As shown here:

<img align=right src="../img/plot/plot1.png">

- z-ness has large variance [@item1; @item2].
- x is symmetric to y  [@item3, pp. 33-35]
- as predicted by theory [@item1]


# During the week

This is how we roll

rolling ![all the dat](../img/dot/dot1.png)

# Conclusion

- And the answer is...
- $f(x)=\sum_{k=0}^\infty\/{pk}(1-p)^k$

# References
