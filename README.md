# Gender_Classification
### A sequential Convolutional Neural Network (CNN) using the Keras library with a TensorFlow backend which can differentiate between male and female 

This model was trained on [Gender Classification Dataset](https://www.kaggle.com/datasets/cashutosh/gender-classification-dataset) dataset from kaggle

Link to the [pretrained model](https://drive.google.com/file/d/18Ja8LZlxgwcf2epPdJkrSSjfGr8SPErK/view?usp=sharing)

## Steps for installation
- $ git clone this repo
- Download the dataset from given website
- Extract the dataset
- Replace path in the file with your path to petimages folder
- Now open jupyter notebook
- Open this file using jupyter notebook
- Run the cells in the sequence they are in.

## Installing Jupyter Notebook
- $ pip install notebook <- this would install jupyter notebook
- $ jupyter notebook <- this would start notebook in local server

## Details about model

Layer | Shape | Params
--- |--- |---
Conv2D | (None, 88, 68, 32) | 896
MaxPooling2D | (None, 44, 34, 32) | 0
Conv2D | (None, 42, 32, 64) | 18496
MaxPooling2D | (None, 21, 16, 64) | 0
Flattenn | (None, 21504) | 0
Dense | (None, 64) | 1376320
Dense | (None, 1) | 65


## Graphs
- ![image](https://drive.google.com/file/d/1Er7Xx-nNMp7dGUNNfH6YhI7-vcK-02l5/view?usp=sharing)
- ![image](https://drive.google.com/file/d/1Byw_9-ClxrttLN2Ph1Ftr3i-uQUzUuTm/view?usp=sharing)
