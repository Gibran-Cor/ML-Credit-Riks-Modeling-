![investing-4013413_1280](https://github.com/Gibran-Cor/ML-Credit-Riks-Modeling-/assets/142538044/b9cb96e6-a4e2-40cc-a40c-f1ab7e3178fe)
# ML-Credit-Riks-Modeling-
**Overview**
This GitHub repository contains the code and resources for a project focused on predicting the probability of default for credit card customers. The dataset used in this project is sourced from Kaggle and comprises information on 459,000 customers. The primary objective is to build a robust classification model that can assist in predicting whether a customer is likely to default on their credit card.

**Problem Statement**
The central challenge addressed in this project is to develop a classification model capable of accurately predicting the probability of default for credit card customers. The dataset reveals that most features are not equally distributed among their categories. Specifically, there is a high number of delinquencies and a low number of full payments across various features. The imbalanced nature of the data poses a challenge that needs to be addressed in the model development process.

**Project Strategies**
We approach the problem with two distinct strategies:

- **Conservative Strategy:**
In the conservative strategy, the emphasis is on minimizing false positives. This means that the model should be designed to avoid incorrectly classifying non-defaulters as defaulters. The conservative strategy is geared towards risk aversion, prioritizing the identification of customers who are unlikely to default.

-  **Aggressive Strategy:**
Conversely, the aggressive strategy is focused on minimizing false negatives. In this approach, the model is designed to be more permissive, potentially accepting a higher rate of false positives in exchange for correctly identifying customers who are likely to default. The aggressive strategy is geared towards capturing potential defaulters more comprehensively.

  **Repository Structure**
The repository is organized as follows:

*data: This directory contains the dataset obtained from Kaggle.

*notebooks: This directory houses Jupyter notebooks used for data exploration, preprocessing, model training, and evaluation.

*src: The source code for the classification model is stored in this directory. It includes modules for data preprocessing, feature engineering, model training, and evaluation.

*reports: This directory contains any reports or visualizations generated during the analysis.
