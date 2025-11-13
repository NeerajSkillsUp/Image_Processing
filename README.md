# Image Processing Notebook 🚀

This repository contains a simple Jupyter Notebook (Image_Processing.ipynb) demonstrating basic image loading, color conversion, and display using different Python libraries.

# Description

The notebook shows how to load an image using both OpenCV and Scikit-image, corrects for color-space differences (BGR vs. RGB), and displays the results.

# Libraries Used

<b> OpenCV (cv2) </b>: Used to read the image file and perform color-space conversion.

<b> Scikit-image (skimage) </b>: Used as an alternative method for reading the image file.

<b> Matplotlib (matplotlib.pyplot) </b>: Used to display all images and subplots.

<b> Numpy </b>: Used for numerical operations on the image arrays.

<img width="2048" height="814" alt="image" src="https://github.com/user-attachments/assets/fc02b05e-8bcd-4e64-aa5f-6822347fe370" />

# What it Does??

<b> Imports Libraries </b>: Loads cv2, matplotlib.pyplot, numpy, and skimage.io.

<b> Loads with OpenCV </b>: Reads an image using cv2.imread(). By default, OpenCV loads images in BGR format.

<b> Prints Shape </b>: Outputs the dimensions of the image ((1176, 720, 3)).

<b> Displays BGR Image </b>: Shows the raw BGR image with Matplotlib (which expects RGB), causing the colors to look incorrect.

<b> Performs Color Conversion </b>: Uses cv2.cvtColor() to convert the image from BGR to RGB format.

<b> Displays RGB Image </b>: Shows the correctly converted RGB image, which now looks natural.

<b> Loads with Scikit-image </b>: Demonstrates an alternative method, reading the same image using skimage.io.imread(), which loads it directly in RGB format.

<b> Displays Channels </b>: Creates a final plot showing the full RGB image next to just its isolated red channel (displayed in grayscale).

# How to Use

1. Make sure you have the required libraries installed (opencv-python, scikit-image, matplotlib, numpy).

2. Ensure you have an image file available and update the img_path variable (e.g., /content/picture.jpg) to point to it.

3. Run the cells in the Jupyter Notebook to see the step-by-step loading and conversion process.


