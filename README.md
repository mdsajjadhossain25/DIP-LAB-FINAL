# Digital Image Processing Laboratory

This repository contains implementations of various digital image processing (DIP) techniques, completed as part of the **Digital Image Processing Laboratory** coursework.

## 🔧 Requirements

- Python (>= 3.6)
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook (for interactive demos)

Install required libraries:

```bash
pip install opencv-python numpy matplotlib notebook
```


## 📚 Lab Tasks Covered

### 1. Grayscale Image Processing
- Decrease spatial resolution using bit quantization
- Reduce intensity level resolution to binary
- Generate and display grayscale image histogram
- Segment image using single threshold based on histogram

### 2. Brightness and Transformation
- Enhance brightness for specific intensity ranges
- Apply power-law transformation
- Apply inverse logarithmic transformation
- Extract Most Significant Bits (MSB) and visualize difference image

### 3. Noise Filtering
- Add Salt & Pepper noise to images
- Apply average filter (3x3, 5x5, 7x7)
- Apply median filter (3x3, 5x5, 7x7)
- Apply harmonic mean and geometric mean filters
- Compute PSNR to compare filter performance

### 4. Frequency Domain Filtering
- Add Gaussian noise to character images
- Apply Fourier Transform and visualize spectrum
- Apply Butterworth, Gaussian, and Ideal Low Pass Filters
- Understand and observe ringing effect from Ideal LPF

### 5. Image Segmentation
- Perform edge detection in spatial domain
- Compare different edge detectors
- Implement global and adaptive thresholding
- Perform gray-level segmentation

### 6. Morphological Operations
- Apply erosion and dilation
- Perform opening and closing
- Extract boundaries using morphological difference
- Fill regions using morphological region filling
