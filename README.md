# Melanoma Detection Case Study
> To build a CNN based model which can accurately detect melanoma.
1. Melanoma is a type of cancer, that can be deadly, if not detected early and accounts for 75% of skin cancer deaths.
2. A lot of manual effort, needed in diagnosis, and lifes can be saved proided a soution can efficiently evaluate images.

## Table of Contents
* [Technologies Used](#technologies-used)
* [Inputs](#Inputs)
* [Steps](#Steps)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## Technologies Used
- Python 3
- Pandas
- Numpy
- Seaborn
- Tensorflow
- Keras
- matplotlib.Pyplot

## Inputs
1. There were 2357 images were given under 9 different classes. 
2. Out of these, 2239 were train images and 118 images were test images.

## Steps
1. Data was loaded into Google drive and Colabs was used to perform GPU action
2. Each image's size was standardized to 180x180
3. This batch of train data was passed through a custom CNN model
4. As a next step, each image was normalized and pass through a custom CNN Model
5. As a final step, class disbalnce was managed and 600 images of all each class was passed through a custom CNN.

## Conclusions
Ater final step:
1. Accuracy was increase significantly, however overfitting issue persisted.
2. Loss had also reduced, however still foudn to be highed for validation set.

## Acknowledgements
- This project was inspired by upGrad


## Contact
Created by @heman2402 - feel free to contact me!