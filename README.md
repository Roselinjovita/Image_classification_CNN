# Image_classification_CNN

This project demonstrates image classification on a dataset of dogs, cats, and pandas using Convolutional Neural Networks (CNN) in PyTorch. It includes model training, evaluation, and visualization using a confusion matrix.

##  Dataset

* Dataset:Animal Image Dataset
* Classes: Dog, Cat, Panda


   * Load the data
   * Train the model
   * Test and view results
 
About the Project – How Image Classification Works
This project performs image classification to identify whether an image is a dog, cat, or panda using a Convolutional Neural Network (CNN) built with PyTorch.

##  How It Works:
### Dataset Preparation

The dataset contains labeled images of dogs, cats, and pandas.

Images are loaded using ImageFolder and resized, normalized, and converted into tensors using transforms from torchvision.

### CNN Architecture

The model uses multiple Convolutional layers to extract features like edges, textures, and patterns from the images.

Pooling layers reduce the size and help in generalizing.

Fully connected layers convert the extracted features into class probabilities.

Softmax is used in the final layer for classification into 3 classes.

### Training the Model

The model is trained on labeled images using cross-entropy loss and an optimizer like Adam.

During training, the model adjusts its weights using backpropagation to reduce the loss.

### Evaluation

After training, the model is evaluated on a test set.

A confusion matrix is generated to visualize how well the model distinguishes between the classes.

### Prediction

You can test the model on new images to see whether it's a dog, cat, or panda.



## 📊 Output

<img width="487" height="505" alt="Screenshot 2025-07-26 142838" src="https://github.com/user-attachments/assets/ab77dec1-25fa-419e-aaf2-967ca4b4314d" />




