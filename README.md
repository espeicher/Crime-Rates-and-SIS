# Crime-Rates-and-SIS

On November 8th, 2017, Toronto Public Health opened the city’s first permanent supervised injection service (SIS) as part of a harm reduction strategy aimed at curbing rising overdose deaths in the city of Toronto. At present, nine such services operate around the city, providing a safe and hygienic environment for people to inject pre-obtained drugs under the supervision of qualified staff. Research suggests SIS have benefits both for individuals and communities, but critics have long contended that the inclusion of such a service in a community leads to a rise in crime.
The intent of this project would be to employ predictive analytics to investigate the correlation between crime rate and the presence of a supervised injection service in Toronto neighbourhoods.
Does opening an SIS in a neighbourhood correspond to a statistically significant change in the crime rate? If so, what is the change, and in what type of crime?
As crime rates throughout the city change continually, isolating change due to a single factor among various trends can be problematic. However, it should be possible to first establish which Toronto neighbourhoods are demographically similar as a baseline. Applying pattern mining and clustering techniques in R to demographic Census data would establish similar neighbourhoods to facilitate comparison. Regression analysis in R would then allow the change in crime rates of Toronto neighbourhoods to be compared to the appearance of an SIS over time.

The datasets employed would include:

Neighbourhood Crime Rates (https://open.toronto.ca/dataset/neighbourhood-crime-rates/)
Neighbourhood Profiles (https://open.toronto.ca/dataset/neighbourhood-profiles/)
Wellbeing Toronto – Demographics (https://open.toronto.ca/dataset/wellbeing-toronto-demographics/)
