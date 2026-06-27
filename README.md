# Image Filtering and Enhancement using OpenCV

## Project Overview

This project focuses on **image filtering and enhancement** using **Python** and **OpenCV**. It applies multiple image processing techniques to reduce noise, improve image quality, enhance contrast, and detect image edges. The project also evaluates the performance of enhancement methods using standard image quality metrics.

---

## Objectives

* Apply different image filtering techniques to reduce noise.
* Enhance image quality using contrast enhancement methods.
* Perform edge detection for feature extraction.
* Compare enhancement techniques using quantitative evaluation metrics.
* Visualize the results for analysis and comparison.

---

## Features

* Image denoising using multiple filtering techniques.
* Contrast enhancement using CLAHE.
* Histogram Equalization for brightness improvement.
* Sobel edge detection.
* Side-by-side visualization of original and processed images.
* Performance evaluation using image quality metrics.
* Comparative analysis of different enhancement techniques.

---

## Technologies Used

* Python
* OpenCV
* NumPy
* Matplotlib
* scikit-image

---

## Project Structure

```text
Image-Filtering-Enhancement/
│
├── Image_Filtering_and_Enhancement.ipynb
└── README.md
```

---

## Implemented Techniques

### Image Filtering

The project applies the following filters to reduce image noise:

* Median Filter
* Gaussian Filter
* Bilateral Filter

---

### Image Enhancement

The following enhancement techniques are implemented:

* Contrast Limited Adaptive Histogram Equalization (CLAHE)
* Histogram Equalization

---

### Edge Detection

The project performs edge detection using:

* Sobel Operator

---

## Image Quality Evaluation

The enhancement methods are evaluated using:

* Peak Signal-to-Noise Ratio (PSNR)
* Structural Similarity Index (SSIM)
* Shannon Entropy

These metrics provide quantitative comparisons between the original and enhanced images.

---

## Libraries Used

* OpenCV (`cv2`)
* NumPy
* Matplotlib
* scikit-image

---

## Workflow

1. Load the input image.
2. Apply image filtering techniques.
3. Enhance image contrast.
4. Detect edges using the Sobel operator.
5. Display the processed images.
6. Evaluate image quality using PSNR, SSIM, and Shannon Entropy.
7. Compare the performance of different enhancement methods.

---

## How to Run

### Requirements

Install the required libraries:

```bash
pip install opencv-python numpy matplotlib scikit-image
```

### Run the Project

Open the Jupyter Notebook and execute all cells sequentially.

```bash
jupyter notebook
```

---

## Learning Outcomes

This project demonstrates practical knowledge of:

* Digital Image Processing
* Noise Reduction Techniques
* Image Enhancement
* Edge Detection
* Image Quality Assessment
* Computer Vision Fundamentals
* OpenCV Image Processing

---

## Author

**Salma Essam**
Bachelor of Computer Science and Information Systems
Major: Artificial Intelligence

---

## License

This project was developed for educational purposes as part of an Image Processing course.
