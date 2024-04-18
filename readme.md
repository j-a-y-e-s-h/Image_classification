# Image Classification 🐶🐱

Welcome to the Image Classification project! This project aims to classify images into either dogs or cats using Convolutional Neural Networks (CNNs) with TensorFlow and Keras.

## Getting Started

### Prerequisites

- Python 3.x
- TensorFlow
- Keras
- Matplotlib
- OpenCV

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/j-a-y-e-s-h/Image_classification.git
   cd Image_classification

   ```
2. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```
3. Generate `kaggle.json` file from Kaggle. Make sure to place it in the root directory.

## Usage

### Google Colab GPU

For faster processing, utilize Google Colab's GPU resources. Follow the steps below:

1. Upload the project to Google Colab.
2. Run the code cells in `image_classification.ipynb`.

### Manual Data Download

If the Kaggle data file isn't downloaded automatically, follow these steps:

1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/salader/dogs-vs-cats).
2. Extract the contents manually into the project directory.

### Training the Model

Execute the code in `image_classification.ipynb` to train the model on the provided dataset.

### Testing with Your Images

You can test the model with your images. Follow the steps below:

1. Prepare your image.
2. Use the `model.predict()` function to classify your image.

## Example Prediction

![dog](https://github.com/j-a-y-e-s-h/Image_classification/assets/75063311/155db9f0-1a52-43ac-97fd-a08b99e34916)


Based on the prediction, the model identified the image as a:

- 🐶 Dog



Make sure to replace `dog.jpg` with the actual path to your test image in the GitHub repository. Also, create a `plots` directory in your repository to store the accuracy and loss plots generated during training.

