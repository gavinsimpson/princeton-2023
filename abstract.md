# We need to talk about non-linearity

## Gavin Simpson (he / him / his)

### Assistant Professor, Department of Animal & Veterinary Sciences, Aarhus University, Denmark

Twitter: @ucfagls
Web: fromthebottomoftheheap.net

## About

Generalized Additive Models (GAMs) are an extension to the generalized linear model, where the relationships between covariates and the variable of interest are not specified by the analyst but are learned from the data themselves. GAMs are especially useful when the relationships between covariates and response do not fit simple parametric forms, and have found particular use for modelling a wide range of data types and problems, especially in spatial and longitudinal settings. While use of GAMs has increased in many disciplines, many researchers remain unfamiliar with their inner workings and capabilities. Learning in a GAM is achieved by viewing the effect of a covariate on the response as a smooth function, rather than following a fixed parametric form (e.g. linear, quadratic), and representing these smooth functions in the model with penalized splines, where a wiggliness penalty is used to avoid over-fitting.

In this talk, I will explain what a GAM is and illustrate how penalized splines work to learn features from the data, focusing on the practical aspects of fitting GAMs to data using R packages like mgcv and brms. I'll illustrate the talk with examples from my own work and from linguistics and cognitive science.
