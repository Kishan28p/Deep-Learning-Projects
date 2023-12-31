# Automated Image Captioning-flickr8k

**Dataset :** https://www.kaggle.com/datasets/aladdinpersson/flickr8kimagescaptions

## Project Information

Image Captioning is a fascinating way for computers to describe images using words.The dataset consists of 8k images and 5 captions for each image. The features are extracted from both the image and the text captions for input. The features will be concatenated to predict the next word of the caption.
CNN is used for image and LSTM is used for text.

**BLEU score** is a metric used to evaluate the quality of machine-generated text

**Environment:** colab

## Libraries

- numpy
- keras
- tensorflow
- nltk

## Neural Network

- VGG16 Network
- CNN-LSTM Network

**NOTE:** The Architecture and parameter used in this network are capable of producing accuracy of ****76.17%**** on Validation Data which is not pretty good. It is possible to Achieve more accuracy on this dataset using other CNN network and fine tuning of network parameters for training. 
