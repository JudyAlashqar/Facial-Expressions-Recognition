# Facial-Expressions-Recognition
Deep Learning-based Python Project to Classify Facial Expressions into 7 Classes: Happy, Sad, Disgusted, Surprised, Scared, Angry and Neutral.
## Dataset
Facial Expressions Recognition (FER) Dataset https://www.kaggle.com/datasets/msambare/fer2013

## Model
Convolution Layer (32) => Batch Normaliztion Layer => Pooling Layer => 
Convolution Layer (64) => Batch Normaliztion Layer => Pooling Layer => 
Convolution Layer (128) => Batch Normaliztion Layer => Pooling Layer => 
Convolution Layer (256) => Batch Normaliztion Layer => Pooling Layer => 
Droput (0.5) =>
Dense Layer (128) =>
Dense Layer (7)

## Results
Accuracy equals to 63.4% on the 20% test split.
