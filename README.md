
## Understanding impact of Imblearn and PCA
---
### Using different imbalance learning techniques like SMOTE, RandomUnderSampler, TomekLinks; in association with PCA
---
An imbalanced classification problem is an example of a classification problem where the distribution of examples across the known classes is biased or skewed. The distribution can vary from a slight bias to a severe imbalance where there is one example in the minority class for hundreds, thousands, or millions of examples in the majority class or classes.

Imbalanced classifications pose a challenge for predictive modeling as most of the machine learning algorithms used for classification were designed around the assumption of an equal number of examples for each class. This results in models that have poor predictive performance, specifically for the minority class. This is a problem because typically, the minority class is more important and therefore the problem is more sensitive to classification errors for the minority class than the majority class.

In this notebook we look to understand how we can solve this problem using different techniques like SMOTE, TomekLinks, RandomUnderSampler, etc. We also try to implemet PCA to reduce the number of collinear features, so as to avoid the problem of multi-collinearity & also arrive at a simpler model; without having too much of a negative impact on the predictive ability of the model.

#### Skills and Tools
LabelBinarizer, RandomForestClassifier, TomekLinks, SMOTE, RandomUnderSampler, Pipeline, PCA
