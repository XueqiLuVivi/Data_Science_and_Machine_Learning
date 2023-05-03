# Perception

### TAsk
In this project, I will build a perceptron model from scratch and implement the perceptron learning algorithm for binary species classification. Our task will be to classify y labels with 0 and 1 using two features "mean radius" and "mean texture".

### Dataset
We use breast_cancer dataset loaded from sklearn.datasets.

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter) 

b) texture (standard deviation of gray-scale values) 

c) perimeter 

d) area 

e) smoothness (local variation in radius lengths) 

f) compactness (perimeter^2 / area - 1.0) 

g) concavity (severity of concave portions of the contour) 

h) concave points (number of concave portions of the contour) 

i) symmetry 

j) fractal dimension ("coastline approximation" - 1)


The mean, standard error and "worst" or largest (mean of the three
largest values) of these features were computed for each image,
resulting in 30 features. For instance, field 3 is Mean Radius, field
13 is Radius SE, field 23 is Worst Radius.

All feature values are recoded with four significant digits.

Missing attribute values: none

Class distribution: 357 benign, 212 malignant

## Libraries

Pandas https://pandas.pydata.org/

Matplotlib https://matplotlib.org/

Numpy https://numpy.org/

Seaborn https://seaborn.pydata.org/

Scikit-learn https://scikit-learn.org/
