# Handwritten-digit-recognition-using-mnist-datatset
METHODOLOGY:
1.The proposed method use the mnist dataset and three different classifier for handwritten digit recognition.
2.Training of datasets is done. Training data is used by the learning algorithm, usually in a supervised learning model, to increase accuracy
3. The label (answer) is provided for each row in the dataset, so the algorithm can learn which data corresponds to which handwritten digit.
4. However, in order to really know how well the program is doing, we need to run it on data that it’s never seen before. That’s where the cross validation set comes in.
5. We’ll split the training set in 2 parts. The first part will remain as the training data. The second part will serve as the cross validation data. We’ll provide the training portion to the learning algorithm, along with the answers.
6. After training has completed, we’ll run the algorithm again on our cross validation data to see just how accurate the solution really is. Since we have the digit labels (answers) for both the training and cross validation sets, we can calculate an accuracy percentage.
7. Using the above technique, we can compare different learning algorithm and find best algorithm for mnist dataset 

