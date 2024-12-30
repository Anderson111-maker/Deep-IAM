# Deep-IAM
The relevant coding of the experimental part in the paper 
File “Data processing and Kmeans”. Contains programs for preprocessing data and programs for cluster analysis.Due to the large size of the IPCC dataset used in the experiment, we have not uploaded it here.
File"Feature selection" contains experiments with the random forest model and interpretation of the model using shapley values. And for different models and scenarios, we draw boxplot to observe the differences in variable distributions.
File"Generative deep learning Model"contains programs for training three generative models: VAE, CGAN, and RCGAN. However, using the TSGM library, we found that even with random seeds, randomness occurs, so we also saved the parameters of each model.

Files with the "Policy" prefix merged classes C1-C4 into a combined C1234 class, C5-C6 into C56 class, and C7-C8 into C78 class. We then reproduced our previous experiments based on this new classification scheme. Notably, when training the VAE-Top6 model, we initially utilized parameters obtained from previous training sessions as a starting point for further training. However, our experiments revealed that training the model from scratch could achieve comparable results. Consequently, we did not use pre-trained parameters for other models.
