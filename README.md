# Semantic-Image-Data-Clustering-using-VGG-19

This Python notebook demonstrates how to use the VGG-19 model for unsupervised image data clustering and analysis. The VGG-19 model is a powerful deep learning architecture commonly used for image classification. However, in this notebook, we will use it for feature extraction and then apply clustering techniques to group similar images together.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Introduction

Image clustering is a technique that allows us to group similar images together based on their content. This can be useful for various applications, such as organizing large image datasets, discovering patterns in data, or even for recommendation systems.

In this notebook, we will:

1. Flatten the Image and apply PCA to reduce the dimentionality of the image vector.
2. Use the VGG-19 model pre-trained on ImageNet to extract feature vectors from a dataset of image vectors.
3. Apply a clustering algorithm K-means to cluster the feature vectors.
4. Visualize the results to understand the image clusters.

## Requirements

To run this notebook, you will need the following Python libraries:

- `numpy`: for numerical operations
- `tensorflow`: for using the VGG-19 model
- `scikit-learn`: for clustering
- `matplotlib`: for visualization

You can install these dependencies using `pip`:

```bash
pip install numpy tensorflow scikit-learn matplotlib
```

## Results

Visualising the clutered images allows you to understand multiple aspects of you dataset. For instance the type of classes the images fall into visually.

![Insects](images/cluster2.png)
