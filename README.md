# Classification-of-Handwritten-Digits-Using-a-Multi-layer-Perceptron-MLP-
A machine learning project using a Multi-Layer Perceptron (MLP) neural network to classify handwritten digits from the MNIST dataset. The model is trained using scikit-learn, visualized with matplotlib, and evaluated on both training and test datasets. This project demonstrates practical implementation of classification tasks using neural networks.

This project is all about using machine learning to teach a computer how to recognize handwritten digits (0-9) from images. Think of it like how you might train a human to read handwritten numbers. My goal here is to build a model that can look at a picture of a handwritten digit and correctly identify which number it represents.

## Project Goal
The goal of this project is to classify handwritten digits from the MNIST dataset, which is a popular dataset used for machine learning tasks. The model we train will take an image of a handwritten digit, process the image, and predict what digit (from 0 to 9) the image represents.

## 🛠️ Tools & Libraries Used
For this project, I used a combination of tools and libraries that made it easier to build, train, and evaluate the model. Here’s what I used:

* Python: The programming language used for the entire project.
* Scikit-learn: A machine learning library in Python, which I used to create and train the model.
* Matplotlib: A plotting library to visualize the images and predictions.
* MNIST dataset: A dataset containing 70,000 images of handwritten digits (60,000 for training and 10,000 for testing).

## 🧠 How the Model Was Trained
1. Data Loading: The first step was to load the MNIST dataset, which contains the images of handwritten digits along with the correct labels (the number each image represents). I used scikit-learn to fetch the dataset.

2. Preprocessing: The pixel values of the images range from 0 to 255, so I normalized the values to be between 0 and 1 to make the training process easier and faster.

3. Model Selection: I used a Multi-Layer Perceptron (MLP), a type of neural network, which works well for classification tasks like this. The model is a simple, yet effective neural network that learns patterns in the data and tries to predict the correct labels.

4. Training: I trained the model on the training data, which consisted of 60,000 images, and tested it on the remaining 10,000 images to see how well it generalized to new data.

5. Evaluation: The model's performance was evaluated using accuracy. Accuracy tells us what percentage of predictions were correct.

## 📊 Results & Performance
After training the model, I evaluated its performance on both the training and test sets:

Training Set Accuracy: The model performed quite well on the training data with an accuracy of about 98%.
Test Set Accuracy: On the test set (the new data it hadn't seen before), the model achieved an accuracy of around 97%.

This means that the model correctly predicted the digit in 97 out of 100 cases on new, unseen data!

## 👁️‍🗨️ Visuals
I have also included some visual results to show how well the model is doing. In my jupyter notebook You'll find images of handwritten digits from the test set, along with the model’s predictions. If the model guessed correctly, the text is green; if it was wrong, the text is red.
