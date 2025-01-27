## A simple Convolutaion Neural Network built on PyTorch

#### The ConvNet is trained on Intel Image Classification Dataset from Kaggle which can be found [here](https://www.kaggle.com/datasets/puneet6060/intel-image-classification).

The dataset is divided into 3 directories :

##### seg_pred
##### seg_test
##### seg_train

The recommended folder structure:

##### pred_data<br>
##### &nbsp;&nbsp;&nbsp;&nbsp;|-images...<br>
##### test-data<br>
##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-class-1<br>
##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-images...<br>
##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-...<br>
##### &nbsp;&nbsp;&nbsp;&nbsp;|-class-6<br>
##### train_data<br>
##### &nbsp;&nbsp;&nbsp;&nbsp;|-class-1<br>
##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-images...<br>
##### &nbsp;&nbsp;&nbsp;&nbsp;|-...<br>
##### &nbsp;&nbsp;&nbsp;|-class-6<br>
##### main.ipynb<br>


6 different sub-directories can be found inside the test and train folders.

The model achieved ~88% accuracy on training data and ~79% accuracy on test data.
