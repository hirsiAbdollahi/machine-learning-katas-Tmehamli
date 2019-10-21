![Supported Python Versions](https://img.shields.io/badge/Python->=3.6-blue.svg?logo=python&logoColor=white)

# Machine Learning Katas

This repository contains a series of exercises (*katas*), with associated theory and code examples, for practicing your Machine Learning and Deep Learning skills.

The katas are written as mostly self-correcting [Jupyter](https://jupyter.org/) notebooks that can be executed either locally or through [Colaboratory](https://colab.research.google.com/) (Google account needed). To do so, open any notebook and click this button: ![Open In Google Colaboratory](https://colab.research.google.com/assets/colab-badge.svg).

Alternatively, you may clone or download this repository and run a Jupyter notebook server on your local machine.

> This material is part of the Machine Learning course taught at [ENSC](https://ensc.bordeaux-inp.fr). [ENSEIRB-MATMECA](https://enseirb-matmeca.bordeaux-inp.fr) and [IOGS](https://www.institutoptique.fr). See also [Acknowledgments](ACKNOWLEDGMENTS.md).

## Machine Learning Tools

### Base Packages

- 📚 Overview [ [source](https://github.com/bpesquet/website/blob/master/content/english/slides/ai/python-data-science/index.md) | [slides](https://www.bpesquet.fr/en/slides/ai/python-data-science/) ]
- ▶️️ Demos
  - [Python Cheatsheet](http://nbviewer.jupyter.org/github/bpesquet/machine-learning-katas/blob/master/notebooks/demos/tools/Python.ipynb)
  - [NumPy](http://nbviewer.jupyter.org/github/bpesquet/machine-learning-katas/blob/master/notebooks/demos/tools/NumPy.ipynb)
  - [Pandas](http://nbviewer.jupyter.org/github/bpesquet/machine-learning-katas/blob/master/notebooks/demos/tools/Pandas.ipynb)
  - [Matplotlib and Seaborn](http://nbviewer.jupyter.org/github/bpesquet/machine-learning-katas/blob/master/notebooks/demos/tools/Matplotlib.ipynb)
- ⛩ Katas
  - [Tensor Management](notebooks/katas/tools/TensorManagement.ipynb)
  - [Data Analysis](notebooks/katas/tools/DataAnalysis.ipynb)

### Machine Learning Librairies

- 📚 Overview
  - Keras [ [source](https://github.com/bpesquet/website/blob/master/content/english/slides/ai/keras/index.md) | [slides](https://www.bpesquet.fr/en/slides/ai/keras/) ]

## Machine Learning Workflow

- 📚 Overview [ [source](https://github.com/bpesquet/website/blob/master/content/english/slides/ai/ml-fundamentals/index.md) | [slides](https://www.bpesquet.fr/en/slides/ai/ml-fundamentals/) ]
- ▶️️ Demos
  - Data Preprocessing [ [scikit-learn](http://nbviewer.jupyter.org/github/bpesquet/machine-learning-katas/blob/master/notebooks/demos/workflow/DataPreprocessing.ipynb) ]
  - Performance Evaluation [ [scikit-learn](http://nbviewer.jupyter.org/github/bpesquet/machine-learning-katas/blob/master/notebooks/demos/workflow/PerformanceEvaluation.ipynb) ]
- ⛩ Katas
  - [Code Preprocessing Functions From Scratch](notebooks/katas/workflow/PreprocessingFunctions.ipynb)
  - [Code Classification Metrics From Scratch](notebooks/katas/workflow/ClassificationMetrics.ipynb)

## Machine Learning Algorithms

### K-Nearest Neighbors

- 📚 Overview [ [source](https://github.com/bpesquet/website/blob/master/content/english/slides/ai/k-nearest-neighbors/index.md) | [slides](https://www.bpesquet.fr/en/slides/ai/k-nearest-neighbors/) ]
- ▶️️ Demos
  - Classify Planar Data [ [scikit-learn](http://nbviewer.jupyter.org/github/bpesquet/machine-learning-katas/blob/master/notebooks/demos/algorithms/KNN_PlanarData.ipynb) ]
  - Classify Fruits [ [scikit-learn](http://nbviewer.jupyter.org/github/bpesquet/machine-learning-katas/blob/master/notebooks/demos/algorithms/KNN_Fruits.ipynb) ]
- ⛩ Katas
  - [Diagnose Breast Tumors](notebooks/katas/algorithms/KNN_BreastCancer.ipynb)
  - [Code K-NN From Scratch](notebooks/katas/algorithms/KNN_Scratch.ipynb)

### Linear Regression

- 📚 Overview [ [source](https://github.com/bpesquet/website/blob/master/content/english/slides/ai/linear-regression/index.md) | [slides](https://www.bpesquet.fr/en/slides/ai/linear-regression/) ]
- ▶️️ Demos
  - Regression On Planar Data [ [TensorFlow Playground](https://playground.tensorflow.org/#activation=tanh&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=25&networkShape=&seed=0.27079&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=regression&initZero=false&hideText=false&showTestData_hide=false&activation_hide=true&noise_hide=false&discretize_hide=true&dataset_hide=true&batchSize_hide=true&percTrainData_hide=true&numHiddenLayers_hide=true&problem_hide=true) ]
  - Predict Country Happiness [ [Homemade-ML](https://nbviewer.jupyter.org/github/trekhleb/homemade-machine-learning/blob/master/notebooks/linear_regression/multivariate_linear_regression_demo.ipynb) ]
- ⛩ Katas
  - [Predict Housing Prices](notebooks/katas/algorithms/LinearRegression_BostonHousing.ipynb)
  - [Code Linear Regression From Scratch](notebooks/katas/algorithms/LinearRegression_Scratch.ipynb)

### Logistic Regression

- 📚 Overview [ [source](https://github.com/bpesquet/website/blob/master/content/english/slides/ai/logistic-regression/index.md) | [slides](https://www.bpesquet.fr/en/slides/ai/logistic-regression/) ]
- ▶️️ Demos
  - Classify Planar Data [ [TensorFlow Playground](https://playground.tensorflow.org/#activation=sigmoid&batchSize=10&dataset=gauss&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=&seed=0.61489&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false&numHiddenLayers_hide=true&percTrainData_hide=true&discretize_hide=true&problem_hide=true&activation_hide=true) ]
- ⛩ Katas
  - [Associate Flowers With Their Class](notebooks/katas/algorithms/LogisticRegression_Iris.ipynb)

### Neural Networks

- 📚 Overview [ [source](https://github.com/bpesquet/website/blob/master/content/english/slides/ai/neural-networks/index.md) | [slides](https://www.bpesquet.fr/en/slides/ai/neural-networks/) ]
- ▶️️ Demos
  - Classify Planar Data [ [Keras](http://nbviewer.jupyter.org/github/bpesquet/machine-learning-katas/blob/master/notebooks/demos/algorithms/DNN_PlanarData.ipynb) ]
  - Tackle Overfitting [ [Keras](http://nbviewer.jupyter.org/github/bpesquet/machine-learning-katas/blob/master/notebooks/demos/algorithms/DNN_Tuning.ipynb) ]
- ⛩ Katas
  - [Classify Fashion Items](notebooks/katas/algorithms/DNN_FashionMNIST.ipynb)
  - [Associate News To Topics](notebooks/katas/algorithms/DNN_ReutersNews.ipynb)

### Ensemble Methods: Decision Trees, Random Forests And Boosting

- 📚 Overview [ [source](https://github.com/bpesquet/website/blob/master/content/english/slides/ai/ensemble-methods/index.md) | [slides](https://www.bpesquet.fr/en/slides/ai/ensemble-methods/) ]
- ▶️️ Demos
  - [Classify Flowers With Decision Trees](http://nbviewer.jupyter.org/github/bpesquet/machine-learning-katas/blob/master/notebooks/demos/algorithms/DecisionTree_Iris.ipynb)
- ⛩ Katas
  - [Tune A Decision Tree](notebooks/katas/algorithms/DecisionTree_Tuning.ipynb)
  - [Predict Diabetes Evolution](notebooks/katas/algorithms/RandomForest_Diabetes.ipynb)
  - [Classify Handwritten Digits](notebooks/katas/algorithms/Ensemble_MNIST.ipynb)
  - [Discover Boosting Libraries](notebooks/katas/algorithms/Boosting_Libraries.ipynb)