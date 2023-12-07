# Image Captioning Model with VGG16 Encoder-Decoder Architecture
## Overview
This project involves the development of an image captioning model based on the encoder-decoder architecture. The encoder utilizes a pre-trained VGG16 model to extract image features, while the decoder consists of a feedforward neural network with LSTM layers to generate captions for the images.

## Motivation
This project is driven by the desire to learn more about transfer learning techniques. By using a pre-trained VGG16 model to help us understand images and an LSTM-based decoder to describe them in words, we are showing how powerful transfer learning can be. It makes complex tasks like adding captions to pictures much better.

# Data Preprocessing
Dataset Used: Flickr 8k Dataset
The project utilized the Flickr 8k dataset, a collection of images with corresponding textual descriptions. This dataset serves as a valuable resource for training and evaluating image captioning models. Flickr8K Dataset

## Text Preprocessing and Tokenization
The input text data underwent essential preprocessing and tokenization to prepare it for input into the decoder model. This step ensures that textual descriptions are in a suitable format for further processing.

## Image Data Preprocessing
Image data was preprocessed to make it compatible with the VGG16 encoder. This involved resizing, normalization, and formatting to be fed into the encoder for feature extraction. Model Performance Assessment The model's performance was evaluated using standard metrics, including BLEU-1 and BLEU-2 scores.

### BLEU-1 Score: 0.40
### BLEU-2 Score: 0.27
These scores demonstrate the model's capability in capturing both unigrams and bigrams when generating image captions. A BLEU-1 score of 0.40 indicates its proficiency in capturing individual words, while a BLEU-2 score of 0.27 reflects its ability to capture pairs of words effectively. This image captioning model, with its VGG16-based encoder and LSTM-based decoder, exhibits promising performance in generating relevant and coherent captions for images, making it a valuable tool for various applications involving image understanding and description. Further fine-tuning and optimizations can potentially enhance its performance even further.
