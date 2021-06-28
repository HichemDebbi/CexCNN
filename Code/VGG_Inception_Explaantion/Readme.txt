Requirements: Tensorflow and keras
Two main notebook are needed to generate the experiments:
1. _Filters_Importance, which  is used for computing the counterfactual info of each filter, with respect to each category.
The causal information learned is stored in a dictionnary.
2. _Explaantions consumes the causal information in order to geenrate the explanations as heatmaps

PS: some results are let on the notebook to be consulted, and some images are put in the folder for running the experiments.