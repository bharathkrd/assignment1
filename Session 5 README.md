# assignment1S5F1
Target:
We have the code right and used ReLU() in the base model.

Results:
Parameters: 194,884
Best Training Accuracy: 99.39
Best Test Accuracy: 98.96

Analysis:
We still can work on the model in order to reduce the gap b/w training and test.
As far as parameters are concerned, we see an increase at   Conv2d-3 Conv2d-5 Conv2d-12 Conv2d-10
Overfitting model.

S5F2
Target:
We have used the regularisation techniques in the model.

Results:
Considerable reduction in number of parameters
Best Training Accuracy: 99.89 
Best Test Accuracy: 99.27%

Analysis:
Test accuracy is more that training accuracy and can be considered as a good model.
however we have not achieved the desired model.


S5F3
Target:
To Use dropout as part of regularization.

Results:
As expected, using dropout has reduced the gap between, training accuracy and test accuracy.
Best Training Accuracy: 99.38
Best Test Accuracy: 99.10%
Parameters : 10,970

Analysis:
As the parameters are decreasing we may not be able to achieve the desired accuracy.
We may need to add more capacity.


S5F4
Target:
Using GAP Layer

Results:
Same as earlier. Could not meet the accuracy of 99.4 and parameters less than 10000.
Best Training Accuracy: 99.31
Best Test Accuracy: 98.80%
parameters : 11,994

Analysis:
Could not attain the consistant accuracy.


S5F5
Target:
Used dropout on each layer except on l-1


Results:
Achieved consistant output.
Best Training Accuracy: 99.23
Best Test Accuracy: 99.44
parameters : 13,808

Analysis:
The model is not over-fitting at all.can use image augmentation further.

