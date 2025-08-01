## 🩸 Blood Group Detection Using Fingerprint (Biometric Health Platform)

📌 **Blood Group Detection Overview**
This project introduces an innovative system that predicts a person’s blood group using biometric data—specifically, their fingerprint. It integrates machine learning with image processing to simplify and accelerate blood group identification, which can be essential in emergency medical scenarios.

📝 **Abstract**
The goal of this project is to develop a cost-effective and contactless method to determine a person’s blood group using fingerprint analysis. By leveraging deep learning models and feature extraction, the system classifies fingerprints into respective blood groups. This helps in critical health cases where rapid and accurate blood group detection is crucial.

🚀 **Features**

* Fingerprint Acquisition via GUI
* Image Preprocessing and Feature Extraction (Minutiae detection)
* Blood Group Prediction using ML Classifier
* Graphical User Interface (Tkinter)
* User-Friendly Interface for Medical Use
* Offline Capability (no need for cloud connectivity)

🛠️ **Technologies Used**

* **Development Platform:** Python with Tkinter
* **Libraries & Tools:** OpenCV, scikit-learn, NumPy, PIL, joblib
* **Machine Learning Model:** Random Forest Classifier
* **Image Processing:** Minutiae-based fingerprint feature extraction

📝 **Installation Steps**

1. **Clone the repository:**

   ```bash
   git clone https://github.com/<your-repo>/Blood_group-detection-using-fingerprint-main.git
   ```
2. **Install dependencies:**

   ```bash
   pip install opencv-python scikit-learn numpy Pillow
   ```
3. **Run the application:**

   ```bash
   python main.py
   ```

📁 **Folder Structure**

```
Blood_group-detection-using-fingerprint-main/
├── dataset/                    # Fingerprint samples
├── features/                   # Extracted fingerprint features
├── min_gun_detect.py          # Minutiae detection script
├── main.py                    # Entry point with GUI
├── model.pkl                  # Pre-trained Random Forest model
├── train_model.py             # Model training script
├── requirements.txt
└── README.md
```

🔬 **Conclusion**
This project demonstrates a practical implementation of biometric blood group prediction using fingerprints. It combines the accuracy of machine learning with the accessibility of image processing tools to create a healthcare aid that can be crucial in emergencies or rural healthcare setups. Future expansions may include mobile integration or live fingerprint scanning support.

📢 **Thank You!**

