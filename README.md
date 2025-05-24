# 🧠 Image Processing Pipeline in Google Colab

This project provides an interactive image processing pipeline using *OpenCV* in *Google Colab*.  
You can upload any image and apply a set of common filters and techniques, including:

- ✅ Brightness & Contrast Adjustment
- ✅ Gaussian Blur
- ✅ Noise Reduction (Denoising)
- ✅ Edge Detection using Canny
- ✅ SIFT Feature Extraction

---

## 🚀 How It Works

### 📥 1. Upload Image
You’ll be prompted to upload an image (.jpg, .png, etc.) using:

python
image = upload_image()


### ⚙️ 2. Processing Steps

The pipeline includes the following steps:

| Step                         | Function                           | Output                        |
|------------------------------|------------------------------------|-------------------------------|
| Brightness & Contrast        | adjust_brightness_contrast()     | Enhanced image                |
| Gaussian Blur                | apply_gaussian_blur()            | Smoothed image                |
| Noise Reduction              | apply_denoising()                | Cleaned image                 |
| Canny Edge Detection         | apply_canny_edge()               | Grayscale edges               |
| SIFT Feature Extraction      | extract_features()               | Keypoints and descriptors     |

Each step displays the result using matplotlib.

---

## 🖼️ Example Output

| Original Image | Brightness/Contrast | Gaussian Blur |
|----------------|---------------------|----------------|
| ![](preview1.png) | ![](preview2.png) | ![](preview3.png) |

> These images are displayed inline when running in Colab.

---

## 🧪 Tech Stack

- Python 3.9+
- OpenCV (opencv-python-headless)
- NumPy
- Matplotlib
- Google Colab
- PIL (Pillow)

---

## 📦 Setup Instructions

> Run this inside a Colab notebook:

python
!pip install opencv-python-headless


Then copy and run the full script from the notebook.

---

## 💾 Save Final Result

You can optionally save the final processed image using:

python
save_image(denoised, "final_result.jpg")


---

## 📊 Feature Extraction with SIFT

The number of features detected via SIFT is printed at the end:

bash
🔍 عدد الميزات المستخرجة: 215


---

## 📌 Notes

- SIFT is available in OpenCV 4+ without extra packages.
- GUI is not used; all outputs are shown inline via matplotlib.

---

## 🧑‍💻 Author

*Mohammed* – Image & AI Enthusiast  
Feel free to modify or expand the code to include more filters or export formats!

---

## 📝 License

MIT License – use freely, modify respectfully.
