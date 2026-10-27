# Fashion-MNIST Classification Using CNN

## About the Project

This is a beginner deep learning project where I built a Convolutional Neural Network (CNN) to classify different types of clothing images.

I used the Fashion-MNIST dataset, which contains grayscale images of clothing items like shirts, dresses, sneakers, bags, and trousers. The goal was to train a model that could identify the category of a clothing image.

## Tools and Technologies

- Python
- TensorFlow and Keras
- NumPy
- Matplotlib
- Jupyter Notebook

## Dataset

The Fashion-MNIST dataset contains 70,000 images in total.

- 60,000 training images
- 10,000 testing images
- 10 clothing categories
- Image size: 28 × 28 pixels

## How I Built It

I started by loading the dataset and displaying some sample images. Then, I normalized the pixel values to help the model train more effectively.

I built a CNN using convolutional layers to extract image features and max-pooling layers to reduce their dimensions. I also used dense layers for classification and dropout to help reduce overfitting.

After building the model, I trained it for 5 epochs and evaluated its performance on the test dataset. I plotted the training and validation accuracy and loss to understand how the model performed during training.

Finally, I tested the model on individual images and displayed multiple predictions to compare the predicted categories with the actual labels.

## Model Results

Test Accuracy: Add your actual test accuracy here.

Test Loss: Add your actual test loss here.

## How to Run the Project

Clone the repository:

```bash
git clone https://github.com/Shravani0175/fashion-mnist-cnn.git
cd fashion-mnist-cnn
```

Install the required libraries:

```bash
pip install tensorflow numpy matplotlib
```

Open the notebook in Jupyter:

```bash
jupyter notebook fashion-mnist.ipynb
```

Run the notebook cells in order. TensorFlow will download the Fashion-MNIST dataset automatically if it is not already available.

## What I Learned

Through this project, I gained practical experience with CNN architecture, image preprocessing, model training, and evaluation. I also learned how to visualize training performance and test predictions on unseen images.

## Future Improvements

- Experiment with different CNN architectures.
- Generate a confusion matrix to analyze predictions.
- Build a simple interface for testing image predictions.

## Author

Shravani Dandane
