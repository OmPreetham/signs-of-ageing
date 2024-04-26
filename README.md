# Project Report: Ageing Signs Localization

## Dependencies:

- Software:
  - Jupyter Notebook
  - Google Colab
- Packages and Libraries:
  - OS
  - CV2
  - Keras
  - Numpy
  - TensorFlow
  - Matplotlib
  - Argparse
  - EfficientnetB0

## Steps Involved in Project:

1. **Importing Dependencies and Dataset:**

   - Importing all the required libraries and packages.
   - Importing the dataset.

2. **Data Preparation:**

   - Splitting the dataset into target and training data.

3. **Image Preprocessing:**

   - Converting color images into black and white using the map function.

4. **Data Augmentation:**

   - Performing data augmentation to increase the diversity of the dataset.

5. **One-Hot Encoding:**

   - Using one-hot encoding to increase the number of neurons.

6. **Model Architecture:**

   - Specifying the architecture of the model using EfficientNetB0.

7. **Model Compilation:**

   - Compiling the model.

8. **Model Training:**

   - Training the model with a batch size of 30 and epochs set to 30.

9. **Testing:**
   - Testing the model to localize ageing signs with an accurate percentage.

## Steps to Run the Code:

1. Download the zip folder.
2. Extract the zip folder.
3. Open the Jupyter Notebook.
4. Run the `Om-Preetham-Bandi-AgeingSign-Batch3.ipynb` Jupyter notebook.
5. Load the respective models and their corresponding weights.
6. Change the `image_path` variable to the path of the image file that you want to test on.
7. Test on the image file.
