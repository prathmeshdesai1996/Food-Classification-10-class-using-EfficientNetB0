#Multiclass Classification Fine-tuned Transfer Learning ML Project
This project aims to classify images of 10 different types of food using transfer learning with the `EfficientNetB0` model. The last 10 layers of the model were unfrozen and fine-tuned using a dataset of 7,500 training images and 2,500 test images.

##Dataset
The dataset used for this project consists of 10 classes of food images, with 750 images for each class. The images were preprocessed by resizing them to 224x224 and normalizing the pixel values to be in the range of [0, 1].

##Model
The EfficientNetB0 model was used as the base model for transfer learning. The model was pre-trained on the ImageNet dataset and the last 10 layers were unfrozen and fine-tuned using the food dataset.

##Results
The model achieved an accuracy of 84% on the test dataset.

##Requirements
The following packages are required to run the code:

- tensorflow
- efficientnet
- matplotlib

##Files
The following files are included in this project:

train.ipynb: Jupyter Notebook for training the model.
model/: Directory containing the trained model and its weights.
data/: Directory containing the dataset used for training and testing.
README.txt: This file.

##Usage
To train the model, run train.ipynb. The model and its weights are saved in the model/ directory. The dataset used for training and testing is located in the data/ directory.
