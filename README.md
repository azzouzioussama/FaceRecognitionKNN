## Face Recognition with K-Nearest Neighbors (K-NN)

This GitHub repository contains a Python script for face recognition using the Local Binary Pattern (LBP) transformation and the K-Nearest Neighbors (K-NN) algorithm.

### Overview

1. **Data Preparation:**
   - Directories "test" and "data" are created for organizing images.
   - Images starting with "1" are moved to the "test" directory; others are moved to the "data" directory.
   - Grayscale images are read and displayed using Matplotlib.

2. **Local Binary Pattern (LBP) Transformation:**
   - Functions for calculating Local Binary Pattern (LBP) are defined.
   - LBP transformation is applied to each image in the dataset.

3. **Histogram Calculation:**
   - Histograms are computed for the LBP-transformed images.

4. **Data Storage:**
   - Image names, paths, and LBP histograms are stored in a Pandas DataFrame.
   - The DataFrame is written to an Excel file ("database.xlsx").

5. **Reading Data:**
   - Data is read from the "database.xlsx" file.

6. **Distance Calculation:**
   - A function calculates the Euclidean distance between two histograms.

7. **K-Nearest Neighbors (K-NN) Algorithm:**
   - K-NN algorithm is implemented to classify a given image.
   - Accuracy of the classification is evaluated.

8. **Testing:**
   - A function tests a single image using K-NN.
   - K-NN algorithm is applied to multiple test images, and results are stored.

9. **Visualization:**
   - Bar plots visualize accuracy scores for different K values in the K-NN algorithm.

### Usage

To use the script, follow these steps:
1. Clone the repository.


Choose a name that reflects the main functionalities and purpose of the code.

Feel free to contribute or provide feedback!
