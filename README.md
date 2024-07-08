# GNN applied to Lipophilocity Regression
In this task I analized over 4000 chemical compounds annotated with a lipophilocity value in order to learn a regression model for predicting lipophilicity of new compounds.

The **architecture** is a standard convolutional Graph Neural Network with 4 layers and tanh activations. I used the pytorch library **Geometric**.

The $R^2$ accuracy obtained on the test set is $32$%

Possible improvements are the usage of **Attention Graph NN** models, hyperparameter tuning (i.e. learning rate), using AdamW instead of Adam.
