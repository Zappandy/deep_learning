# Softmax Regression

## Classification Problem

In a classification problem for example with a image making up of pixel we can rrrepresent ech pixel as features for instance x1, x2, x3 x4 and the label of the oimage can be represeted with also with numbers, but if the image is not belong tito a ordering list, the best way to represent the label is with a one-hot encoding, this is making by putting a vector of zeros and ones, where each one represent the position of the label, so for example if we have 3 images, belong to cat,chiken and dog we can represent the labels with the following vector

(1, 0,0) correspond to cat
(0, 1, 0) correspond to chiken
(0, 0, 1) corrspond to dog
