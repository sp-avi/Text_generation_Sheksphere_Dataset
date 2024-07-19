# Text Generation Using TensorFlow and Tiny Shakespeare Dataset
This repository contains code for a text generation model using TensorFlow and the Tiny Shakespeare dataset. The model is based on an LSTM network and can generate Shakespeare-like text based on a given seed string.

## Table of Contents
Introduction
Dataset
Installation
Usage
Training
Text Generation
Contributing
License

## Introduction
This project demonstrates text generation using a character-level LSTM model. The model is trained on the Tiny Shakespeare dataset, which consists of text from Shakespeare's works. The trained model can generate new text that mimics the style of Shakespeare.

## Dataset
The Tiny Shakespeare dataset is a small corpus of Shakespeare's writings. It is available through TensorFlow Datasets and can be easily loaded using the tfds library.

## Installation
To run this project, you need to have Python installed along with the required libraries. You can install the dependencies using:
`pip install tensorflow tensorflow-datasets numpy`

## Usage

1.Clone the repository:
`git clone https://github.com/your_username/text-generation-tiny-shakespeare.git
cd text-generation-tiny-shakespeare`

2.Run the training script:
`python train.py`

3.Generate text:
`python generate_text.py`

## Training
The training script (train.py) performs the following steps:

Load the Tiny Shakespeare dataset using TensorFlow Datasets.

Preprocess the text data to create input-target sequences.

Define and compile an LSTM model for text generation.

Train the model and save checkpoints during training.

## Text Generation
The text generation script (generate_text.py) performs the following steps:

Load the trained model and latest checkpoint.

Define a function to generate text based on a seed string.

Generate and print text based on a given start string.

You can modify the generate_text.py script to change the seed text and the number of characters to generate.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or new features.
