# Celebrity-Face-Recognition
The Deep Learning Model is trained using Tensorflow Framework and it gives validation accuracy value of 85%

![Dataset Images](https://raw.githubusercontent.com/aangfanboy/celebrities_face_recognation_dataset/master/fig.png)


## Description:
The below Python code will unzip the above downloaded dataset by the user and split it into the training set and and validation set based on the given ratio.**Transfer Learning** has been implemented  with the **MobileNetV2** model and **imagenet** weights. The pre-trained model consists of 155 layers and the whole layers of the pretrained model is retrained to get the better accuracy.Image Augmentation has been implemented to avoid the overfitting of the model.
The model has been trained for the 50 epochs and the **Validation Accuracy of 85%** has been yielded.Note:The model performs well on the cropped images.

## Dataset Content:

This images has been collected from Pinterest and cropped. There are 105 celebrities and 17534 faces

## Prerequisites:

The below libraries are needed to execute the Python code

* Python 3.8
* Tensorflow 2.1.0
* Numpy
* Matplotlib

#### Dataset Link: https://www.kaggle.com/hereisburak/pins-face-recognition 
#### Kaggle Link: https://www.kaggle.com/srikeshram/celebrity-face-recognition


## Repository Contains:
* Python Code (.ipynb)
* Trained Weights(.h5)




## License:

This project is licensed under the Apache License 2.0- see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgements:
* hereisburak for Dataset
* Inspiration
* etc...
