# Digits-Classification-with-SVM
Classification of digits from 0-9 with the help of various kernels present in the svm classifier.
In this project we are trying to classify first 10 digits of the number system.
For this we have used the load_digits dataset of the sklearn datasets module.
Further we have done train test split of 78 and 22 percent respectively.
Now first we have used radial basis function kernel of the svm classifier with gamma 0.001 and provides good result with 5 misclassifications only out of 396 and a accuracy of 98.73% approx.
To improve upon this we have now implemented the polynomial svm classififer with degree 3 as the optimal degree which gives only 3 wrong classifications with accuracy of above 99%.
Finally we can plot the confussion matrix to take detailed review of which numbers were mis-classified. 
