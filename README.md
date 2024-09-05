# PADIM-algorithm
# Data Processing Codes

I have uploaded all the codes related to data processing to the `finally.ipynb` file. All the codes do not require additional libraries and can be run directly.

I have uploaded all the codes related to data processing to the `finally.ipynb` file. All the codes do not require additional libraries and can be run directly in Jupyter.

## Installation of Libraries

If there are any libraries that are not installed, you can use the following pip command to install them:

```bash
pip install <library_name>
## Overview of the Codes

We have a total of 6 codes, namely:

1. **Adjust all images to (1200x1200)**: This code resizes all images to a uniform dimension of 1200x1200 pixels.
2. **Unify the center radius of diamonds**: This code standardizes the center radius of diamond images for consistency.
3. **Cut a small part of the center (256x256) for PADIM**: This code extracts a 256x256 pixel section from the center of the images for PADIM processing.
4. **Perform histogram equalization on the image**: This code applies histogram equalization to enhance the contrast of the images.
5. **Use PCA and k-means to classify the training set**: This code implements PCA for dimensionality reduction and uses k-means clustering for classification of the training set.
6. **Use IOU for data evaluation**: The sixth example uses Intersection over Union (IoU) for evaluating the quality of the data. This example evaluates a single image. If you want to evaluate multiple images at the same time, you can use a for loop to traverse the entire folder.

Feel free to explore the code and apply it to your data processing needs!
