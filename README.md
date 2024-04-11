# Toxic Comment Classification with CNN

This project uses Convolutional Neural Networks (CNN) to classify toxic comments. The dataset used is the `jigsaw_toxic_comments` dataset.

## Dependencies

The project uses the following Python libraries:

- Keras
- pandas
- wandb
- numpy
- zipfile
- matplotlib
- os

## Dataset

The dataset is extracted from a zip file located at `/content/drive/MyDrive/Datasets/Toxic Comments/jigsaw-toxic-comment-classification-challenge.zip`.

## Word Embeddings

The project uses the Stanford GloVe (Global Vectors for Word Representation) for word embeddings. The GloVe file is extracted from a zip file located at `/content/drive/MyDrive/Datasets/Toxic Comments/glove.6B.zip`.

## Model Architecture

The model architecture is a Convolutional Neural Network (CNN).

## Configuration

The configuration for the model includes:

- Architecture: CNN
- Dataset: jigsaw_toxic_comments
- Weights: Stanford GloVe.6B
- Max Sequence Length: 100
- Max Vocab Size: 20000
- Embed Size: 100
- Validation Split: 0.2
- Batch Size: 128
- Epochs: 10

## Weights and Biases

The project uses Weights & Biases for experiment tracking and visualization.

## Running the Project

To run the project, open the `Toxic_Comment_with_CNN.ipynb` notebook and execute the cells in order.