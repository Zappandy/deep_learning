# Softmax Regression

## Classification Problem

In classification image problems, each pixel feature may be represented as x1, x2, x3, and x4. Their labels may be stored with numbers, but if these values are not ordered, it's much better to rely on one-hot encoding. I.e. we create vectors with binary values for each label. For instance, let's say we have 3 pictures: a cat, a chicken, and a dog. We can store these as follows:

-(1, 0,0) cat
-(0, 1, 0) chicken
-(0, 0, 1) dog
