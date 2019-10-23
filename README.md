
If github in unable to render a Jupyter notebook, copy the link of the notebook and enter into the nbviewer: https://nbviewer.jupyter.org/

# Naive-Bayes-Non-Linear-Classifier

In this notebook we investigate the fact that Naive Bayes Classifier (NBC) is a **<font color=red size=6> non-linear classifier </font>** by observing its decision boundary. It can classify non-linear dataset by creating non-linear decision boundary. It doesn't need to augment the dataset (i.e., creating high-dimensional features).

Previously we observed that K-Nearest Neighbors (K-NN) is also a non-linear classifier.

However, K-NN was a **non-parametric** model, whereas NBC is a **parametric** model. 

We compare the NBC decision boundary with **K-NN** and **Logistic Regression** decision boundaries.

Our goal is to show that for a non-linear dataset, the NBC and K-NN models can "learn" very complex (non-linear) decision boundary, while Logistic Regression can only create a linear decision boundary.

- NBC and K-NN are inherently non-linear models.
- Logistic Regression is inherently a linear model.
