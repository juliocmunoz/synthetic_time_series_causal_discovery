# Synthetic Time Series for Causal discovery

This repository captures a set of synthetic time series for causal discovery. Each time series in generated for 3 observavble variables ${X_1, X_2, X_3}$
and a target variable ${Y_1}$. The tool used is proposed in [Lawrence (2020)](https://github.com/causalens/cdml-neurips2020).

Each synthethic time is generated based on a causal structure (the image of each structure is included in their respective folder). 
The values of the observable variables are taken based on additive noise in terms of a given distribution 
`(Guassian, Student's t, Laplace, Uniform)`. In this way, we generated 10 sets of time series that share the same causal structure but the values of the 
observable variables have slightly variations.

As for the causal estructuture generation child nodes have a functional dependence on their parents. We set the probability of causal links at 30%.
The maximum time step for this causal links varies for each set of time series in a given range `[2, 3, 4, 5, 6]`.
