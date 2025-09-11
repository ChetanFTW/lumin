
#  lumin

Welcome to **lumin**, a collection of modular image processing projects using Python. This repository includes multiple projects exploring classical image processing, creative image-based applications, and experimental features — all under one roof.

---

## 📁 Projects Overview

| Project | Description | Demo |
|---------|-------------|------|
| [Lumin Toolkit](https://github.com/ChetanFTW/lumin/blob/master/lumin.ipynb) | Classical image processing using OpenCV and Matplotlib. | [ link ](https://colab.research.google.com/drive/17omKshuqCpPXawRfmqdeHI9rQGOU4GxI?usp=sharing) |
| [Meme Generator](#project-2-image-based-) | Upload an image and generate a meme with custom or auto-generated text. | _N/A_ |
| [Project 3 (Coming Soon)](#project-3-other-image) | A work-in-progress image-related project. More details to be added soon. | _Coming soon_ |


---

## 🧠 Project 1: Lumin Image Processing Toolkit

### ➢ Summary

This project focuses on building a modular image processing toolkit called **Lumin** using classical techniques. It includes:

- Image loading and pixel value analysis
- Comparing image loading with `matplotlib` vs `cv2`
- Image sharpening using filters
- Color-based image classification (e.g., water, trees, houses, soil)

### ➢ Tech Stack

- `numpy`
- `pandas`
- `opencv-python (cv2)`
- `matplotlib`
- `glob`

### ➢ Key Features

- ✅ Load and view multiple images
- ✅ Analyze pixel value distributions
- ✅ Compare reading methods: `cv2.imread()` vs `plt.imread()`
- ✅ Sharpen images using convolution kernels
- ✅ Classify images by HSV color masks
- ✅ Visualize classified outputs

### ➢ Tasks Accomplished

- Loaded and displayed multiple images using `cv2` and `matplotlib`
- Compared channel order: BGR vs RGB
- Applied sharpening kernel with `cv2.filter2D`
- Classified images by HSV ranges for water, trees, houses, and soil
- Created binary masks and recolored pixels based on category

### ➢ Potential Extensions

- Improve classification accuracy with refined HSV thresholds
- Add edge detection, blurring, or noise reduction
- Introduce ML-based image classification
- Calculate area metrics for classified regions

---

## 🎭 Project 2: Image-Based Meme Generator

### 📘 Summary

This is a simple meme generation app. Upload an image and either provide your own caption or use an automatically generated one. The system adds the text on top/bottom of the image to create a meme.

### 🛠️ Technologies Used

- `Pillow` or `opencv-python`
- `Flask` or similar (for web UI)
- Optional: random quote generator or ML model for auto captions

### 🎯 Features

- 🖼️ Upload any image
- ✍️ Enter or generate meme captions
- 🎨 Render captioned meme
- 💾 Download the final result


