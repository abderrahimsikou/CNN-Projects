# Gender Classification (CNN Project)

This project aims to use deep learning [CNN] to classify gender (Male,Female).
The project was developed using Google Colab, and data toke  from the kaggle platform.

## Technologies Used

- Python
- Keras & TensorFlow
- NumPy

## Dataset

The data was taken from kaggle by connecting kaggle to google colab,without download it.
==> DataSet Link : https://www.kaggle.com/datasets/ashishjangra27/gender-detection-20k-images-celeba

## Connect Kaggle to Google Colab

To upload data from Kaggle to Google Colab, follow these steps:

1. **Download API file from Kaggle**:
   - Go to your Kaggle account.
   - From your account settings, find the “API” section and click “Create a new API token.”
   - The file "kaggle.json" will be downloaded.
After that, copy the username and key.

## Folder Structure

Gender_classification.ipynb: Contains Training the model and prediction part.
model.h5                   : The Model Trained
test_image                 : Image to test prediction