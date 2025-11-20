# Edge_Detection
## Aim
To implement and compare different Edge Detection Algorithms—specifically Sobel, Laplacian, and Canny—to identify significant intensity changes in an image using Python and OpenCV.

## Software Required

1. Anaconda - Python 3.x
2. OpenCV
3. Matplotlib
4. NumPy

## Features

- **Sobel Operator**: Calculates image gradients to detect edges, emphasizing horizontal ($G_x$) and vertical ($G_y$) changes.

- **Laplacian Operator**: Computes the second-order derivative to find regions of rapid intensity variation.

- **Canny Edge Detector**: A multi-stage optimal edge detection algorithm that provides clean, single-pixel-wide edges.

## Algorithm:

### Step 1: Load and Preprocess Image

Load the input image in grayscale mode. Grayscale simplifies the gradient calculations.

### Step 2: Implement Sobel Operator

Apply the Sobel operator to calculate the gradient magnitude of the image in $x$ and $y$ directions.

### Step 3: Implement Laplacian Operator

Apply the Laplacian operator to compute the second-order derivative, sharply highlighting intensity changes.

### Step 4: Implement Canny Edge Detector

Apply the Canny Edge Detector. This process involves smoothing, gradient finding, Non-Maximum Suppression, and Hysteresis Thresholding. [Image showing the steps of the Canny Edge Detection algorithm]

Step 5: Display and Compare Results

Display the original grayscale image and the results from the Sobel, Laplacian, and Canny operators for visual comparison.
