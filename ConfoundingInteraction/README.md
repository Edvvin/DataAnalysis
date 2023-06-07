# Confounding Interaction
This is a short analysis to answer the following problem:


> "Researchers have found that underweight newborns whose mothers smoked during pregnancy are less likely to die than underweight newborns whose mothers did not smoke. Granted that smoking during pregnancy increases the risk of infant death, provide a hypothesis that could explain this finding."

It is done by simulating the data generating process and then performing a logistic regression to estimate the effects of smoking, underweight birth and the interaction term. The idea was to generate such data that the logistic regression evaluates the study as being such that interaction term is the opposite of the rest of the terms.

To see the rest of the analysis open [ConfoundingInteraction.ipynb](https://github.com/Edvvin/DataAnalysis/blob/master/ConfoundingInteraction/ConfoundingInteraction.ipynb)
