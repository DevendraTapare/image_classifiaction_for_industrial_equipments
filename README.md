# image_classifiaction_for_industrial_equipments
Develop a machine learning model that can classify images of industrial equipment into two categories: 'defective' and 'non-defective'.

Link for Dataset : https://www.kaggle.com/datasets/mhskjelvareid/dagm-2007-competition-dataset-optical-inspection/data

# Image Classification Using TensorFlow and Keras
This project focuses on building and training a convolutional neural network (CNN) for image classification using TensorFlow and Keras. The model is designed to classify images into predefined categories using a dataset of images.

## Features
* Data Preprocessing: Images are preprocessed using TensorFlow's ImageDataGenerator, including resizing, rescaling, and splitting the dataset into training and validation sets.
* Model Architecture: A custom CNN is built with multiple convolutional and pooling layers, followed by fully connected layers for binary classification.
* Training and Validation: The model is trained using the binary cross-entropy loss function and Adam optimizer, with performance tracked across epochs.
Dataset
The project uses a dataset stored in the directory DAGM_KaggleUpload.
Dataset comprises images belonging to 11 different classes.
Images are resized to 150x150 pixels before training.
Technologies Used
Python
TensorFlow/Keras
NumPy
Scikit-learn
Setup and Usage
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/repo-name.git
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Place the dataset in the directory DAGM_KaggleUpload.
Run the Jupyter Notebook to preprocess data, train the model, and evaluate performance.
Future Improvements
Implement augmentation techniques to enhance model generalization.
Add functionality for multi-class classification.
