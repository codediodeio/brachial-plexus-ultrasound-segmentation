# Brachial Plexus Ultrasound Nerve Segmentation

Exploratory data analysis and convolutional neural network implementation for the Ultrasound Nerve Segmentation competition on Kaggle.

The Github repo only contains a small sample of the 5,635 training images. To run this notebook on the full dataset, (1) clone the repo, (2) download the train/test data at https://www.kaggle.com/c/ultrasound-nerve-segmentation/data, then (3) change the `TRAIN_DIR` and `TEST_DIR` constants to your local directory.

## Main Files

- Report.pdf - Project paper and analysis.
- notebook.ipynp - Jupyter notebook, last executed on full dataset.
- notebook.html - HTML output of notebook.

## Python Libraries

- Keras
- Theano
- OpenCV

## Neural Network Architectures

- VGG-16 https://arxiv.org/pdf/1409.1556
- U-Net https://arxiv.org/pdf/1505.04597
