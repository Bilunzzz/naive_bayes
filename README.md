# Naive Bayes Classifier

## Project Overview
This repository implements a **Naive Bayes classifier** to solve a classification problem. The model is built and tested on a dataset, and it demonstrates how the algorithm works in predicting outcomes based on given features.

## Dataset
The dataset used in this project is the **Social Network Ads** dataset. This dataset contains data points related to user characteristics and whether or not they purchased a product.

### Files:
- **`Social_Network_Ads.csv`**: Contains the dataset used in the project.
- **`naive_bayes.ipynb`**: Jupyter notebook where the Naive Bayes classification model is implemented and tested.

## Getting Started

To run the notebook, you need the following libraries installed:

- **pandas**: For data manipulation.
- **numpy**: For numerical operations.
- **matplotlib**: For data visualization.
- **scikit-learn**: To build and evaluate the Naive Bayes classifier.

### Installation

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib scikit-learn
```

### Runing the Project

1. Clone the repository :

```bash
git clone https://github.com/Bilunzzz/naive_bayes.git
```

2. Navigate to the project directory :

```bash
cd naive_bayes
```

3. Open and run the **`naive_bayes.ipynb`** notebook in Jupyter.

## Naive Bayes Algorithm

The Naive Bayes algorithm is a probabilistic classifier based on applying **Bayes' theorem** with strong independence assumptions between the features. It is especially effective for problems with high-dimensional data and is commonly used for text classification, spam filtering, and recommendation systems.

### How it Works :
1. The algorithm calculates the probability of each class given the input data.

2. It assumes that each feature contributes independently to the probability of the outcome.

3. Based on the calculated probabilities, it classifies the input data into the most probable class.

### Results

The notebook demonstrates the accuracy and performance of the Naive Bayes classifier on the Social Network Ads dataset. It includes:

- Data exploration and visualization
- Data preprocessing (feature scaling)
- Model training and testing
- Evaluation using accuracy, confusion matrix, and classification report

### Contributing

If you'd like to contribute to this project, feel free to open a pull request or raise an issue for discussion.
