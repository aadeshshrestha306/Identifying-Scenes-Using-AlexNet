## A simple Convolutaion Neural Network built on PyTorch

#### The ConvNet is trained on Intel Image Classification Dataset from Kaggle which can be found [here](https://www.kaggle.com/datasets/puneet6060/intel-image-classification).

The dataset is divided into 3 directories :

##### seg_pred
##### seg_test
##### seg_train

The recommemded folder structre:

pred_data
    |-images...
test-data
    |-class-1
        |-images...
    |-...
    |-class-6
train_data
    |-class-1
        |-images...
    |-...
    |-class-6
main.ipynb


6 different sub-directories can be found inside the test and train folders.

The model achieved ~88% accuracy on training data and ~79% accuracy on test data.
