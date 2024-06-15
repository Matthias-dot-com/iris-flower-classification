# Iris Flower Classification

## Overview
This project is a machine learning application that classifies iris flowers into three species: Setosa, Versicolor, and Virginica based on their features: sepal length, sepal width, petal length, and petal width. The classification is performed using various machine learning algorithms implemented in Python.

## Table of Contents
- [Overview](#overview)

- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)


## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/Matthias-dot-com/iris-flower-classification.git
    cd iris-flower-classification
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required libraries:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
1. **Jupyter Notebook**:
    - You can run the Jupyter Notebook to see detailed analysis and step-by-step implementation:
      ```sh
      jupyter notebook notebooks/iris.ipynb
      ```

## Dataset
The dataset used is the famous Iris dataset. It consists of 150 samples from each of three species of Iris flowers (Iris setosa, Iris versicolor, and Iris virginica). Four features were measured from each sample: the lengths and the widths of the sepals and petals.

- Sepal length in cm
- Sepal width in cm
- Petal length in cm
- Petal width in cm
- Class: Iris-setosa, Iris-versicolor, Iris-virginica

## Model
Various machine learning algorithms are used to classify the Iris species:
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest

## Results
The performance of the models is evaluated using metrics such as accuracy, precision, recall, and F1-score. The best performing model can be selected based on these metrics.

## Contributing
Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

1. Fork the repository.
2. Create a new branch:
    ```sh
    git checkout -b feature/your-feature-name
    ```
3. Commit your changes:
    ```sh
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```sh
    git push origin feature/your-feature-name
    ```
5. Create a pull request.
