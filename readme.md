# 🆔 Pancard Tampering Detection System

A web-based application that detects potential tampering in PAN card images using image processing and machine learning techniques.

---

## 🚀 Overview

This project is designed to identify whether a PAN card image has been tampered with by analyzing structural inconsistencies between original and modified images. It demonstrates practical applications of **computer vision, image similarity metrics, and web deployment**.

The system allows users to upload PAN card images and returns a similarity score along with a tampering prediction.

---

## 🎯 Key Features

* Upload and analyze PAN card images
* Detect tampering using image comparison techniques
* Generate similarity score for validation
* Lightweight and fast processing
* Simple web interface for easy interaction

---

## 🧠 Tech Stack

**Programming Language:** Python
**Libraries & Frameworks:**

* OpenCV – Image processing
* scikit-image – Structural similarity (SSIM)
* NumPy – Numerical computations
* Flask – Web application framework

---

## 🏗️ Project Structure

```
Pancard-Tampering/
│
├── app/                 # Core application logic
├── sample_data/         # Sample PAN card images for testing
├── app.py               # Main application entry point
├── config.py            # Configuration settings
├── requirements.txt     # Dependencies
└── README.md            # Project documentation
```

---

## ⚙️ How It Works

1. User uploads a PAN card image
2. The system preprocesses the image (resize, grayscale conversion)
3. Structural Similarity Index (SSIM) is computed
4. Differences are highlighted to detect tampering
5. A similarity score and visual output are generated

---

## 📊 Methodology

* Image preprocessing (grayscale conversion, resizing)
* Structural similarity comparison using SSIM
* Threshold-based classification for tampering detection
* Visualization of differences using contour detection

---

## 🛠️ Installation & Setup

### Step 1: Clone the repository

```
git clone https://github.com/your-username/Pancard-Tampering.git
cd Pancard-Tampering
```

### Step 2: Create virtual environment

```
conda create -n pancard_env python=3.9
conda activate pancard_env
```

### Step 3: Install dependencies

```
pip install -r requirements.txt
```

### Step 4: Run the application

```
python app.py
```

### Step 5: Access the app

Open your browser and go to:

```
http://127.0.0.1:5000/
```

---

## 🧪 Sample Data

Use the images inside the `sample_data/` folder to test the application.

---

## 📈 Results

* Successfully detects structural inconsistencies in tampered images
* Provides similarity score for validation
* Highlights modified regions visually

---

## 🔍 Use Cases

* Identity verification systems
* Fraud detection in financial services
* Document validation pipelines

---

## 🚧 Future Improvements

* Integrate deep learning models (CNN-based detection)
* Improve robustness for real-world variations
* Deploy on cloud (AWS / GCP)
* Add API support for integration with other systems

---

## 🤝 Contributing

Contributions are welcome. Feel free to fork the repository and submit a pull request.

---

## 📬 Contact

**Uttam Kumar**
📧 [uttamott@gmail.com](mailto:uttamott@gmail.com)
🔗 LinkedIn: https://linkedin.com/in/uttam-kumar-25579594


