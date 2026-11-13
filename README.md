🌿 Plant Disease Detection Using Machine Learning

A machine learning application that identifies plant diseases from leaf images using deep learning-based feature extraction and a Random Forest classifier.

🚀 Project Overview

This project combines MobileNetV2 and Random Forest to classify plant leaf images into different disease and healthy categories.

The application provides a simple Streamlit interface where users can upload an image and receive a predicted class with the top 5 prediction probabilities.

✨ Features

* Plant disease classification across 53 classes.
* MobileNetV2-based image feature extraction.
* Random Forest classification.
* Top 5 prediction probabilities.
* Interactive Streamlit web interface.
* Image upload support (JPG, JPEG, PNG).

🛠️ Technologies Used

* Python
* TensorFlow / Keras
* MobileNetV2
* Scikit-learn
* Random Forest
* Streamlit
* NumPy
* OpenCV
* Joblib

⚙️ Model Workflow

1. Upload a plant leaf image.
2. Resize the image to 224 × 224 pixels.
3. Preprocess the image using MobileNetV2 preprocessing.
4. Extract image features using the trained MobileNetV2 model.
5. Classify the extracted features using Random Forest.
6. Display the predicted class and top 5 predictions.

📊 Model Performance

Metric	Result
Test Accuracy	86%
Number of Classes	53
Test Samples	7,651
Classifier	Random Forest
Feature Extractor	MobileNetV2

Results are from the evaluation recorded in the training notebook.

📁 Project Structure

plants_disease_detection/
├── app.py
├── train_knn.ipynb
├── feature_extractor_model.h5
├── feature_extractor_model.keras
├── rf_model.pkl
├── class_labels.npy
├── rf_confusion_matrix.png
├── requirements.txt
└── README.md

💻 Installation and Setup

1. Clone the repository

git clone https://github.com/sandeepvanmali/plants_disease_detection.git
cd plants_disease_detection

2. Create a virtual environment

python -m venv venv

Activate it:

macOS / Linux

source venv/bin/activate

Windows

venv\Scripts\activate

3. Install dependencies

pip install -r requirements.txt

4. Run the application

streamlit run app.py

Open the local URL displayed in your terminal.

📷 Application Output

Upload a plant leaf image to view the predicted class and its top 5 prediction probabilities.

👨‍💻 Author

Sandeep C Vanmali

Electronics and Communication Engineering
Nitte Meenakshi Institute of Technology
