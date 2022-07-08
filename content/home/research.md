---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Research Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's yo/Users/amitjain/Documents/GitHub/NewWebsite/content/home/experience.mdur current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research Assistant
    company: CASS Lab
    company_url: ''
    company_logo: org-gc
    location: The Pennsylvania State University
    date_start: '2018-01-01'
    date_end: ''
    description: |1-
        * **Stochastic Reachability Analysis using Sparse-Collocation Method:** 
            * Reachability analysis of a general non-linear system is computed in the presence of uncertainties in the initial condition, control input and external disturbances 
            * Computed the numerical solution of the transition probability density function (pdf) of a general non-linear system using transformation of variables
            * Dynamical system is propagated using the minimum number of collocation points, which are computed through the non-product quadrature method known as the Conjugate Unscented Transformation (CUT) method
            * Utilized minimum set of polynomial expansion as a convex optimization problem to find the sparse approximation solution
        * **Stochastic Reachability Analysis for the Hypersonic Re-entry Problem:** 
            * Used CUT method to drive the uncertainty in control input to compute the reachability set for the hypersonic reentry model
            * Multi-dimensional expectation integrals are computed using CUT to get desired order statistical moments
            * Numerical results for the first and second order moments are computed for two different maneuvers and are verified using Monte Carlo (MC) simulations
        * **Computationally Efficient Approach for Stochastic Reachability Set Analysis:** 
            * Formulated the problem of computing reachability set of a system in a probabilistic manner
            * Utilized the Convolution and Principle of Maximum Entropy (PME) techniques to find the pdf of a system at any given time
            * Verified numerical results using MC simulations
        * **An Optimal Trajectory Planning Based on Load Distribution for a Multi-lift System:** 
            * Developed an optimal trajectory planning method for a multi-lift system using direct and indirect collocation method
            * Applied direct collocation-based method to find a solution
            * Implemented indirect collocation-based method to verify the solution obtained from the direct collocation method
            * Used non-linear solvers such as fmincon and fsolve to solve the optimization problem
            
        

design:
  columns: '2'
---
