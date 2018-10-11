# Sign-Language-Classifer
Two prototype models CNN's to classify photos of sign language letters.

![](https://github.com/morrissa/Sign-Language-Classifer/blob/master/asl_alphabet_test/D_test.jpg?raw=true) ![](https://github.com/morrissa/Sign-Language-Classifer/blob/master/asl_alphabet_test/L_test.jpg?raw=true)

The model uses a stacked CNN architecture with 50% dropout and varying strides throughout the image processing within the layers. The final model/prototype achieved a 89% accuracy.

The reason I kept the two prototypes seperate, was to remind me that data engineering, preprocessing, and also balancing out representation in the train/test split can make or break a model. In which the first prototype I did a manual work around to seperate all the categories (letters and symbols images) into train and test based on representation of images. However, this resulted in a model that did not validate or generalise well. 

The second prototype I took advantage of the Keras balancing of train/test and more preprocessing and as a result got a model that validated well and also passed test cases. 

The data can be obtained from Kaggle.com
