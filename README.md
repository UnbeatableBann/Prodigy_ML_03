# Cat and Dog Classification Using SVM

This repository contains a project that implements a Support Vector Machine (SVM) to classify images of cats and dogs. The dataset used is the well-known Kaggle dataset of cat and dog images.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)

## Introduction

Image classification is a fundamental task in computer vision. This project demonstrates how to use a Support Vector Machine (SVM) to classify images of cats and dogs. The SVM is a powerful supervised learning algorithm that is effective for binary classification tasks.

## Dataset

The dataset used in this project is the Kaggle dataset of cat and dog images. It contains a large number of images of cats and dogs that can be used to train and evaluate the model. You can download the dataset using the Kaggle API.

To download the dataset using the Kaggle API:

1. Ensure you have the Kaggle API installed. If not, you can install it using:
    ```bash
    pip install kaggle
    ```

2. Authenticate the Kaggle API by placing your `kaggle.json` API token in the appropriate directory (Use your username):
    - On Windows: `C:\Users\<YourUsername>\.kaggle\kaggle.json`
    - On Mac/Linux: `~/.kaggle/kaggle.json`

3. Download the dataset:
    ```bash
    !kaggle datasets download -d salader/dogs-vs-cats
    ```

4. Extract the downloaded dataset into the `data` directory of the project.

## Installation

To run this project locally, you need to have Python installed. Follow these steps to set up the environment:

1. Clone this repository:
    ```bash
    git clone https://github.com/UnbeatableBann/cat-dog-classification-svm.git
    cd cat-dog-classification-svm
    ```

2. Create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Prepare the dataset:
    - Ensure the dataset is downloaded from Kaggle and extracted into the `data` directory of the project.

2. Run the Jupyter Notebook:
    ```bash
    jupyter notebook cat_dog_classification.ipynb
    ```

3. Follow the steps in the notebook to preprocess the data, train the SVM model, and evaluate its performance.

## Results

The project outputs the classification accuracy and visualizations of the correctly and incorrectly classified images. These results demonstrate the effectiveness of the SVM model for the binary image classification task.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please open an issue or submit a pull request.
