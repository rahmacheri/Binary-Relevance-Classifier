# Binary-Relevance-Classifier
Binary Relevance (BR) is by far the simplest approach to solve Multi-Label problems: The fundamental concept behind this
algorithm involves dividing the multi-label learning problem into qi distinct binary
classification problems for each pi label. Each binary classification problem is specifically
linked to one of the potential labels within the label space.

To implement this approach, SVM was utilized as a binary classifier base estimator. SVM
offers robust performance and flexibility in handling complex datasets. The Radial Basis
Function (RBF) kernel function was employed in conjunction with grid search technique to
optimize the gamma and cost parameters, enhancing the model's performance.

Furthermore, the one-vs-rest strategy was used for the construction of multiple binary
classifiers, each trained to predict the presence or absence of a specific label. This strategy
provides versatility in handling diverse label sets and contributes to the model's overall
accuracy. Additionally, the Calibrated Classifier (CV) was adopted to ensure reliable
probability estimates and further enhance the accuracy of the model's predictions.
