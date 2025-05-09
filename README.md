# Image Processing Toolkit

A comprehensive Streamlit application for image processing and computer vision tasks, featuring 9 practical modules with interactive visualizations.

## Overview

This application provides a complete pipeline for image analysis and manipulation with the following capabilities:

### Core Functionalities

1. **Histogram Analysis** (TP1)
   - Color space conversions (RGB, HSV, LAB)
   - Histogram calculations (raw, normalized, cumulative)

2. **Histogram Transformations** (TP2)
   - Translation, inversion, dynamic expansion
   - Histogram equalization

3. **Color Quantization** (TP3)
   - K-means based color reduction
   - Quantized histogram visualization

4. **Convolution Filters** (TP4)
   - 15+ filters including Gaussian, median, Sobel
   - Edge detection and enhancement

5. **Edge Detection** (TP5)
   - Sobel and Laplacian operators
   - Gradient magnitude/direction visualization

6. **Image Segmentation** (TP6)
   - Thresholding (simple/Otsu/adaptive)
   - K-means clustering segmentation

7. **Connected Components** (TP7)
   - Custom labeling implementation
   - Region identification and coloring

8. **Region Analysis** (TP8)
   - Property calculations (area, centroid, etc.)
   - Compactness and eccentricity metrics

9. **Video Processing** (TP9)
   - Frame-by-frame navigation
   - Playback controls

### Technical Features
- Interactive Streamlit web interface
- OpenCV and NumPy backend
- Matplotlib visualizations
- Support for both images and videos
- Responsive parameter controls

## Usage

1. Install requirements: `pip install streamlit opencv-python numpy matplotlib pillow pandas`
2. Run the app: `streamlit run app.py`
3. Upload an image/video and explore the modules

*Note: The code is organized by TP (Travaux Pratiques) modules, each focusing on specific image processing concepts.*
