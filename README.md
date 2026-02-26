# Image Compression using K-Means (From Scratch)

## Project Overview

This project implements the K-Means clustering algorithm from scratch in Python and applies it to image compression using color quantization.

Instead of using pre-built machine learning models, the clustering logic was manually implemented to understand the internal working of unsupervised learning algorithms.

The objective is to reduce the number of unique colors in an image by grouping similar RGB values into *k* clusters, thereby compressing the image while maintaining visual structure.

---

## How It Works

An image consists of pixels, and each pixel contains three values: Red, Green, and Blue.
Each pixel can be treated as a point in three-dimensional space.

The algorithm performs the following steps:

1. Randomly initialize *k* centroids
2. Compute Euclidean distance between each pixel and centroids
3. Assign each pixel to the nearest centroid
4. Update centroid positions based on assigned pixels
5. Repeat until convergence

After convergence, each pixel is replaced with its corresponding centroid color, reducing the overall color space of the image.

---

## Key Features

* Complete K-Means implementation from scratch
* No use of sklearn or pre-built clustering libraries
* Vectorized computations using NumPy for performance optimization
* Adjustable *k* value to control compression level
* Visualization of original and compressed images

---

## Applications

* Image compression
* Color quantization
* Web image optimization
* Reducing storage and transmission cost
* Understanding clustering in real-world scenarios

---

## Learning Outcomes

* Deep understanding of unsupervised learning fundamentals
* Practical implementation of clustering algorithms
* Performance improvement using vectorization
* Application of machine learning concepts to image processing


