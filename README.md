# Character-recogonition-using-CNN
## Description-
    This program is a Python script for arctic wildlife image classification. It uses a pre-trained ResNet50V2 neural network for feature extraction and adds custom layers for classification. The dataset includes images of arctic fox, polar bear, and walrus, split into training and testing sets. The model is trained with data augmentation for improved performance. The script also visualizes training history and evaluates the model using a confusion matrix. Additionally, it demonstrates inference on sample images, predicting and displaying class probabilities for arctic fox and walrus. The code is structured for a machine learning project, facilitating image classification of arctic wildlife species.
## Explanation-
    Image Loading and Preprocessing:
      -Loads and preprocesses images of arctic fox, polar bear, and walrus.
      - Resizes images to 224x224 pixels.
    Data Splitting:
      -Separates data into training and testing sets.
    Model Construction:
      -Uses a pre-trained ResNet50V2 model.
      -Adds classification layers and data augmentation.
    Model Compilation and Training:
      -Compiles model with Adam optimizer and categorical crossentropy loss.
      -Trains the model on the training data for 25 epochs.
    Model Evaluation:
      -Plots training and validation accuracy.
      -Generates a confusion matrix for evaluation.
    Inference on Sample Images:
      -Loads and preprocesses sample images.
      -Predicts and prints class probabilities for arctic fox and walrus images.
