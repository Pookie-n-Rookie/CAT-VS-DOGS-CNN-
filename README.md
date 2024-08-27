# CAT-VS-DOGS-CNN-

This project implements a Convolutional Neural Network (CNN) to classify images of cats and dogs using the dataset from [Microsoft Cats vs Dogs Dataset](https://www.kaggle.com/datasets/shaunthesheep/microsoft-catsvsdogs-dataset).

## Dataset

The dataset can be downloaded from Kaggle using the following link: [Microsoft Cats vs Dogs Dataset](https://www.kaggle.com/datasets/shaunthesheep/microsoft-catsvsdogs-dataset).

## Getting Started

### Prerequisites

Make sure you have the following Python packages installed:
- TensorFlow
- Keras
- NumPy
- pandas
- scikit-learn
- matplotlib
- PIL (Pillow)

You can install these packages using pip:

```bash
pip install tensorflow keras numpy pandas scikit-learn matplotlib pillow

export KAGGLE_CONFIG_DIR=path/to/your/kaggle.json
Running the Model
Prepare the Dataset

Ensure that the images are organized into appropriate directories for training and validation. Typically, you would organize them into train/cats, train/dogs, val/cats, and val/dogs.

Train the Model
```bash

### Setup

#### Download the Dataset

Go to [Microsoft Cats vs Dogs Dataset](https://www.kaggle.com/datasets/shaunthesheep/microsoft-catsvsdogs-dataset) and download the dataset. You will need to sign in to Kaggle and use your API key to access the dataset programmatically.

#### Obtain Kaggle API Key

To fetch the dataset programmatically, you need your Kaggle API key. Follow these steps to get it:

1. Sign in to your Kaggle account.
2. Go to the "Account" tab of your user profile ([https://www.kaggle.com/account](https://www.kaggle.com/account)).
3. Scroll down to the "API" section and click on "Create New API Token."
4. This will download a file named `kaggle.json`. This file contains your API credentials.

