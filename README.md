# Face Mask Detection with TensorFlow & OpenCV

This project implements a **Face Mask Detection system** using **TensorFlow/Keras** for model training and **OpenCV** for face detection and preprocessing. It provides an **interactive interface** to predict mask usage on uploaded images or predefined dataset images in Google Colab.

---

## Features

- Detects whether a person is **wearing a mask** or **not wearing a mask**.
- Crops the largest face from an image using OpenCV Haar cascades before prediction.
- Predicts using a trained **Convolutional Neural Network (CNN)**.
- Interactive mode for testing **dataset images** or **user-uploaded images**.
- Displays cropped faces along with predicted labels and confidence scores.

---

## Dataset

This project uses the [Face Mask Dataset](https://www.kaggle.com/omkargurav/face-mask-dataset) by Omkar Gurav.

- `with_mask/` — images of people wearing masks (label = 1)
- `without_mask/` — images of people not wearing masks (label = 0)

**Label Mapping:**

| Label | Meaning          |
|-------|-----------------|
| 0     | Not wearing mask |
| 1     | Wearing mask     |

---

## Open in Google Colab and Run it

1. Open your repository in Google Colab.
2. Make sure all required packages are installed
