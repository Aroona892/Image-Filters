# 🧼 Image Filtering with OpenCV: Manual vs Built-In Box Filter

This project demonstrates how to apply **box filtering (mean filtering)** manually using NumPy and compare the results with OpenCV’s built-in `cv2.blur()` function. It visually highlights the correctness and effects of different kernel sizes.

---

## 🔍 Features

- ✅ Load and preprocess `.tiff` image
- 📦 Define 3x3, 5x5, and 7x7 **box filter kernels**
- ✋ Apply manual filtering using NumPy convolution logic
- ⚙️ Apply OpenCV’s `cv2.blur()` for the same kernels
- 📊 Visualize and compare manual vs OpenCV results using Matplotlib

---

## 🛠 Tools Used

- Python
- OpenCV
- NumPy
- Matplotlib

---

## 🚀 How to Run

1. Install dependencies:
```bash
pip install opencv-python numpy matplotlib
