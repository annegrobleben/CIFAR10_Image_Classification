This notebook is based on an assignment done as part of a Master in Data Science & AI at Nuclio Digital School (2024), it shows how to train a convoluational neural network (CNN) that assigns images in the CIFAR10 dataset from the Keras library to 10 different categories with an accuracy of at least 80% on the test set. It is divided into eight sections:

1. Libraries
2. Model network architecture
3. Optimizer, error function
4. We prepare the data
5. Training
6. Model Optimization
- Model2
- Model3
- Model4
- Model5
- Model6
7. We evaluate the results
8. We save the models for future evaluations

The dataset is loaded directly from the Keras library and split into training set, validation set and test set. A total number of six networks are trained throughout this assignment. After several parameter adjustments, data augmentation and further and optimizations Model3 turns out to be the best performing model, which is used to make the final predictions. 

This notebook was created in Google Colab. In order to run it it is highly recommended to use Google Colab or a similar service that provides GPU runtime needed to train neural networks. 
