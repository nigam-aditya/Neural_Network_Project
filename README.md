An image recognition model using artificial neural network. 
The source code are in two files - /Neural Network/training_and_saving_model.py and /Neural Network/prediction_with_model.py. The images used for prediction are also in the same folder
Keras library is used for making this project using python as the language.
Training data used for the model is from the cifar10 dataset, which consists 32*32 images labeled into 10 different categories. A sequential model with two convolutional set of layers is used. The model structure and trained weights are saved to seperate files to use in prediction.
The trained model is then used on new images to predict which category they belong to. 
The aim of this project is to understand deep learning techniques to build AI Recogniton system.
