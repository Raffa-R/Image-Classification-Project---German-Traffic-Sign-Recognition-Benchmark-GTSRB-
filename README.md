# Image-Classification-Project---German-Traffic-Sign-Recognition-Benchmark-GTSRB-

-The dataset contains traffic sign boards from the streets captured into image files. There are 43 unique classes in total.

-The dataset is from: [German Traffic Sign Recognition Benchmark GTSRB](https://sid.erda.dk/public/archives/daaeac0d7ce1152aea9b61d9f1e19370/published-archive.html)

-This dataset is made available under the “CC0 1.0 Universal (CC0 1.0) Public Domain Dedication” license. The text of the license is available here: https://creativecommons.org/publicdomain/zero/1.0/

# Data Splitting
There are a total of 39209 data in the German Traffic Sign Recognition Benchmark GTSRB dataset. 

The dataset is divided into three parts: Train set, Validation set, and Test set. 80% of the dataset will be used to train the model (train set), then from the train set, 25% of the data is randomly taken for validation (validation set) (In other words, 60% of the dataset will be used for the train set and 20% of the dataset is used for the validation set), and 20% of the dataset is used to test the model (test set).

![Data Splitting](https://github.com/Raffa-R/Image-Classification-Project---German-Traffic-Sign-Recognition-Benchmark-GTSRB-/blob/main/assets/Data%20Splitting.PNG)

# Model Structure
The following is the model structure built in the creation of the German Traffic Sign Recognition Benchmark (GTSRB) image classification model.

![Model Structure](https://github.com/Raffa-R/Image-Classification-Project---German-Traffic-Sign-Recognition-Benchmark-GTSRB-/blob/main/assets/Model%20Structure.PNG)

# Model Training
![Model Training](https://github.com/Raffa-R/Image-Classification-Project---German-Traffic-Sign-Recognition-Benchmark-GTSRB-/blob/main/assets/Model%20Training.PNG)

The model was trained for 30 epochs. However, the model training stopped at epoch 11. This is due to the callbacks used in model training, where model training stops when training accuracy and validation accuracy > 0.95. 

# Training and Validation Accuracy and Loss Graphs
![Training and validation acc](https://github.com/Raffa-R/Image-Classification-Project---German-Traffic-Sign-Recognition-Benchmark-GTSRB-/blob/main/assets/Training%20and%20validation%20acc.png)

![Training and validation loss](https://github.com/Raffa-R/Image-Classification-Project---German-Traffic-Sign-Recognition-Benchmark-GTSRB-/blob/main/assets/Training%20and%20validation%20loss.png)

# Model Testing
After the model training is complete, the model will enter the testing phase, where the model is tested using the test set. Here are the results of the model testing.

![Model Testing](https://github.com/Raffa-R/Image-Classification-Project---German-Traffic-Sign-Recognition-Benchmark-GTSRB-/blob/main/assets/Model%20Testing.PNG)

Based on the image above, the results of the model testing achieved an accuracy of around 96%.
