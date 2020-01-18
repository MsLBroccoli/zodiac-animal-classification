# zodiac-animal-classification
Bertelsmann Udacity Scholarship AI Track Challenge to classify the chinese zodiac animals

Description
=========================================================================================

The goal is to classify the 12 chinese zodiac animals (rabbit, rooster, pig, ox, monkey, dog, rat, dragon, snake, tiger, goat, horse). The dataset can be downloaded at https://www.kaggle.com/elderyouth/chinese-zodiac-signs.
I implemented a pretrained ResNeXt-101-32x8d model with a modified fully connected layer using the Pytorch library for the classification. The code to preprocess the input data and display the training/validation progress and test results is based on the code examples of the Bertelsmann Tech Scholarship Challenge Course - AI Track Nanodegree Program from Udacity.
The model achieved a test accuracy of 93% on the test set.
