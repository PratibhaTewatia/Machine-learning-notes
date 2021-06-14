Principle component analysis

PCA is a dimentionality reduction technique that transforms the columns of a dataset into new set of features called principal components.

Visualizating the separation of classes or clusters is hard for data with more than 3 dimensions ( features ). With PCA it becomes easy

from sklearn.preprocessing import MinMaxScalar and StandardScalar

Create an object of these classes

from sklearn.decomposition import PCA
