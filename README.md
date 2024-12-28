# PCA Image Compression and Reconstruction

This project demonstrates the process of compressing and reconstructing images using Principal Component Analysis (PCA). The goal is to manually implement PCA for both grayscale and colored images, without relying on built-in PCA functions.

In this project, I first work with a grayscale image and compress it using PCA. Then, I reconstruct the image using fewer components to see how much information is retained in the compression process. Afterward, I move on to compress a colored image, treating each color channel separately and applying the same PCA technique.

To make it even more interesting, I also apply PCA to a set of facial images from the Olivetti Faces dataset, which allows me to visualize "eigenfaces" — the principal components that represent the most important features of faces. This can be used for tasks like facial recognition or image compression.

### Requirements
- Python 3.x
- `numpy`, `PIL`, `matplotlib`, and `scikit-learn`

You can install the required dependencies with:
```pip install numpy pillow matplotlib scikit-learn```

## How to Run

1. Clone this repository.
2. Place the images you want to compress in the appropriate directories.
3. Run the provided code to compress and reconstruct the images.
4. Visualize the results with matplotlib.


## What You’ll See
The original and reconstructed images will be displayed side by side, showing how much detail is preserved in the compression.
The eigenfaces script will show the average face and the first few eigenfaces from the dataset, demonstrating how PCA captures essential facial features.
