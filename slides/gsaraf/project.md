
# Cox Modelling Technique

* Software modules evolve, change in size, and experience corrective and non-corrective changes over time.
* Cox modelling with recurrent events is especially suited to model software quality of such software.
* An event corresponds to a defect fix made to a C++ class. The risk of experiencing an event at any time _t_ is modelled by a hazard functions and is given by:
 
  $\lambda_i(t) = \lambda_0(t)e^{\beta x_i(t))}$

* Conditional Cox models to be used with four states corresponding to 0, 1–5, 6–25, and >25 prior events, labeled from 1 to 4, respectively 

