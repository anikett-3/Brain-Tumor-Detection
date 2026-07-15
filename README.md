# 🧠 Brain Tumor Detection using MobileNetV2 Transfer Learning

A Deep Learning web application that detects and classifies brain tumors from MRI images using **MobileNetV2 Transfer Learning**, **TensorFlow/Keras**, and **Streamlit**.

---

## 📌 Project Overview

This project classifies brain MRI images into one of the following four categories:

- 🧠 Glioma Tumor
- 🧠 Meningioma Tumor
- 🧠 Pituitary Tumor
- ✅ No Tumor

The application allows users to upload an MRI image and receive:

- Predicted Tumor Type
- Confidence Score
- Class-wise Probabilities
- Short Description of the Tumor
- Medical Disclaimer

---

# 🚀Live Demo 🔗 

👉 https://brain-tumor-detection-aniket.streamlit.app/

---

### 🧪 Try the Application

You can test the application using:

- 📁 Sample MRI images available in the `test_images/` folder of this repository.
- 🧠 Your own **brain MRI image** (JPG, JPEG, or PNG).
- 🔍 Publicly available **brain MRI images** for demonstration purposes.

The application will display:

- ✅ Predicted Tumor Type
- 📊 Class-wise Probability Chart
- 🎯 Confidence Score
- ℹ️ Basic Information about the Predicted Class

---

# 🛠 Tech Stack

- Python
- TensorFlow
- Keras
- MobileNetV2 (Transfer Learning)
- NumPy
- Pillow (PIL)
- Streamlit
- Jupyter Notebook

---

# 🧠 Deep Learning Model

Model Used:

**MobileNetV2 (Transfer Learning)**

Why MobileNetV2?

- Lightweight architecture
- Fast inference
- High accuracy
- Suitable for deployment
- Pretrained on ImageNet

---

# 📂 Dataset

The dataset contains MRI brain images of four classes:

- Glioma
- Meningioma
- Pituitary
- No Tumor

Images are preprocessed using:

- Resize to 224×224
- RGB Conversion
- MobileNetV2 preprocess_input()

---

# ⚙️ Project Workflow

MRI Image

↓

Preprocessing

↓

MobileNetV2 Feature Extraction

↓

Dense Layer

↓

Softmax Classification

↓

Prediction

↓

Display Result using Streamlit

---

# 📊 Model Performance

| Metric | Value |
|----------|---------|
| Validation Accuracy | **93.39%** |
| Test Accuracy | **85.19%** |

---

# 📁 Project Structure

```
Brain-Tumor-Detection/
│
├── app.py
├── project.ipynb
├── final_brain_tumor_model.keras
├── requirements.txt
├── README.md
├── test_images/
└── screenshots/
```

---

# ▶️ Installation

Clone the repository

```bash
git clone https://github.com/anikett-3/Brain-Tumor-Detection.git
```

Go inside the folder

```bash
cd Brain-Tumor-Detection
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

---

# 📷 Screenshots

(Add screenshots after deployment)

---

# 🔮 Future Improvements

- Grad-CAM Visualization
- Doctor Dashboard
- PDF Medical Report
- Multi-language Support
- Cloud Deployment
- Better Accuracy with Larger Dataset

---

# ⚠️ Disclaimer

This project is developed for educational and research purposes only.

It should not be considered a substitute for professional medical diagnosis.

---

# 👨‍💻 Author

**Aniket Kumar**

B.Tech (Artificial Intelligence & Machine Learning)

IES College of Technology

---

⭐ If you like this project, consider giving it a star.