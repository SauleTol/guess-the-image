# guess-the-image
Dog Breed Classification Model

This project involves creating a machine learning model that predicts the breed of a dog based on its image. The model utilizes convolutional neural networks (CNNs), a type of deep learning model suitable for image classification tasks.

Dataset
The model is trained on a dataset containing images of dogs, categorized into different breeds. The link to dataset - https://www.kaggle.com/datasets/gpiosenka/70-dog-breedsimage-data-set

Technologies Used
Python: Programming language used for implementing the machine learning model and data preprocessing.
TensorFlow and Keras: Deep learning frameworks used to build and train the CNN model.
PIL (Python Imaging Library) / Pillow: Library used for image processing tasks such as loading and manipulating images.
NumPy and Pandas: Libraries used for data manipulation and analysis.
Jupyter Notebook: Environment used for developing and testing the model, providing an interactive platform for experimentation and analysis.
Model Architecture
The model architecture consists of several convolutional layers followed by max-pooling layers to extract features from the input images. The final layers include fully connected layers with dropout regularization to prevent overfitting and a softmax layer for multi-class classification of dog breeds.