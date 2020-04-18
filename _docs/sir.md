---
title: SIR Model
permalink: /docs/modeling/
---

The SIR model is a epidemiological model to simulate the time evolution of disease spreading.
At the core is the division of the whole population $$ N $$ in three subsets $$ S $$ ("Susceptible"), $$ R $$ ("Recovered") and $$ I $$ ("Infected").
Therefore at all times, $$ I + S + R = N $$ holds.
The model then consists of three ordinary non-linear differential equations - one for each subset.
The two model parameters $$ \beta $$ (average number of people getting infected by one infected) and $$ \gamma $$ (average recoveries per time step).
The ratio of these two numbers $$ R_0:=\frac{\beta}{\gamma} $$ is called the "basic reproduction number" and is a key variable that determines the trajectory of the epidemic.

The logistic regression can be seen as the integrated result of this set of differential equations.
In this sense both models should be equally powerful to model the datasets at hand.
However, if we want to look into the future (especially considering changes of political policies and measures) the logistic regression will always be a simple extrapolation from the existing data.
In contrast, with a differential model as the SIR, we can evolve a single time step and even consider model parameters to be time dependent ( $$ \beta = \beta(t) $$ ).
In this sense the SIR can be used to fit every timestep of the evolution to existing data and therefor provide a model parameter for every timestep.

There is extensions of this model to spacial models (spatial SIR models) which also attempt to model the spatial evolution of the disease.

You can find more information at the [Wikipedia](https://en.wikipedia.org/wiki/Compartmental_models_in_epidemiology).
