Image Classification

 

You are given a data corpus of labeled images. The labels identify the handwritten Azerbaijani letters”.

 

Dataset consist of two files: test.txt and train.txt

Information about the images are separated by  “#”
There are given information about data type in the first line

PatN#PatType#PatProb#SizeH#SizeW#Data

PatN – index (label) of image

PatType – written form of the letter

PatProb - coefficient of correctness of writing the prototype [0, .., 10]. Correct spelling is rated “10” and the worst is “0”.

SizeH, SizeW - character size in height and width, respectively.

Data – pixels of image

 

Tasks:

- Load Data (10%)
- Train Multilayer (fully connected) Neural Networks on Train data, tune parameters and calculate accuracy for test data (20%)
- Train Convolutional Neural Networks on train data, tune parameters and calculate accuracy for test data  (50%)
- Comparison. Write a report which algorithm is best for your data and clarify your decision (20%)
