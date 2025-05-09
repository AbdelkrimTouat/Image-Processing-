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
   - K-means-based color reduction
   - Quantized histogram visualization

4. **Convolution Filters** (TP4)
   - 15+ filters including Gaussian, median, and Sobel
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

## ⚙️ Technologies

**Core Stack:**
- ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) Python 3.7+
- ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=Streamlit&logoColor=white) Streamlit (Web Interface)
- ![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=flat&logo=OpenCV&logoColor=white) OpenCV (Image Processing)
- ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white) NumPy (Array Operations)

**Visualization:**
- ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=Python&logoColor=white) Matplotlib (Plots/Charts)
- ![Pillow](https://img.shields.io/badge/Pillow-3776AB?style=flat&logo=Python&logoColor=white) Pillow (Image Handling)

## 📜 License

MIT License

Copyright (c) 2025 Abdelkrim Touat

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS ARE LIABLE FOR ANY CLAIM, DAMAGE, OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
