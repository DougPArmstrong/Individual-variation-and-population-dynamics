# Description

Code and data repository for manuscript entitled "Is individual heterogeneity in growth rates relevant to population dynamics of long-lived reptiles?" by Doug P. Armstrong, Matthew G. Keevil, Patrick D. Moldowan, Njal Rollinson, Jacqueline D. Litzgus, Ronald J. Brooks.

The research assesses whether accounting for individual heterogeneity affects interpretation of past and future population dynamics in a snapping turtle population with pronounced individual heterogeneity in somatic growth rates and size-specific reproductive outputs. This involves comparing results from integrated population models that: (1) incorporate individual heterogeneity using Bayesian hiearchical modelling which is projected to the future using data augmentation; (2) allow for size-based changes in vital rates but assume no individual heterogeneity; and (3) assume vital rates are not size-dependent. The models are fitted to 50 years of data on enounter histories, carapace lengths and clutch sizes of adult females in the North Madawaska River catchment of Algonquin Park, Canada. The code are written for OpenBUGS or related software (JAGS, NIMBLE).

## Repository contents:

`Population_data_1972-2012.txt`: Data on encounter histories, growth and clutch sizes of mature female snapping turtles in Algonquin Park, Canada, from 1972-2012.

`Population_data_2012-2012.txt`: Data on encounter histories of mature female snapping turtles in Algonquin Park, Canada, from 2012–2022.

`Population_model_with_individual_heterogeneity.txt`: OpenBUGS code for modelling dynamics of a snapping turtle population while accounting for size-dependence in survival and reproduction rates of adult females and individual heterogeneity in growth parameters and size-specific reproductive output.

`Population_model_without_individual_heterogeneity.txt`: OpenBUGS code for modelling dynamics of a snapping turtle population while accounting for size-dependence in survival and reproduction rates of adult females but assuming there is no individual heterogeneity in rates.

`Population_model_without_size-dependence.txt`: OpenBUGS code for modelling dynamics of a snapping turtle population while while assuming no size-dependence in survival or reproduction rates of adult females.

`Jolly-Seber_model.txt`: Jolly-Seber model for estimating annual abundances of mature female snapping turtles from encounter history data.

`Age_at_maturity_distribution`: OpenBUGS code and data for obtaining an age-at-maturity distribution for female snapping turtles based on minimum and maximum ages at maturity for known-aged females.
