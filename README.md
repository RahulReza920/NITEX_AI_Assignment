# Fashion MNIST Classification with Simplified ResNet-18
#Overview
This project aims to classify images from the Fashion MNIST dataset using a simplified version of the ResNet-18 architecture. The model is trained to predict the category of clothing items in the dataset.
Approach
Data Splitting
The dataset is divided into training and validation sets using a 80-20 split. This allows us to train the model on a portion of the data and validate its performance on a separate subset.
Model Architecture
The chosen architecture is a simplified ResNet-18 model. This architecture is known for its effectiveness in image classification tasks. It consists of residual blocks which help in mitigating the vanishing gradient problem.
Training
The model is trained using the Adam optimizer and sparse categorical cross-entropy loss function. Training is performed for 10 epochs with a batch size of 32.
All the code are tested in Kaggle using GPU T4x2 Enviroment.
