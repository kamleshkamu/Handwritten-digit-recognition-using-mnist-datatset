# Handwritten-digit-recognition-using-mnist-datatset
METHODOLOGY
The proposed method use the mnist dataset and three different classifier for handwritten digit recognition.
Training of datasets is done. Training data is used by the learning algorithm, usually in a supervised learning model, to increase accuracy
The label (answer) is provided for each row in the dataset, so the algorithm can learn which data corresponds to which handwritten digit.
However, in order to really know how well the program is doing, we need to run it on data that it’s never seen before. That’s where the cross validation set comes in.
We’ll split the training set in half. The first half will remain as the training data. The second half will serve as the cross validation data. We’ll provide the training portion to the learning algorithm, along with the answers.
After training has completed, we’ll run the algorithm again on our cross validation data to see just how accurate the solution really is. Since we have the digit labels (answers) for both the training and cross validation sets, we can calculate an accuracy percentage.
Using the above technique, we can compare different learning algorithm and find best algorithm for mnist dataset 






