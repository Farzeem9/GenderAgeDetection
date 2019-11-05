# GenderAgeDetection
A classifier that can approximately guess the gender and age of the person (face) in a picture using Deep Learning and OpenCV on the Adience dataset.

The predicted gender may be one of ‘Male’ and ‘Female’, and the predicted age may be one of the following ranges- (0 – 2), (4 – 6), (8 – 12), (15 – 20), (25 – 32), (38 – 43), (48 – 53), (60 – 100) (8 nodes in the final softmax layer). It is very difficult to accurately guess an exact age from a single image because of factors like makeup, lighting, obstructions, and facial expressions. And so, it is more of a classification problem instead of a regression one.
