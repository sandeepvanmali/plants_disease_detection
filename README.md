🌿 Plant Disease Detection Using Machine Learning.

A machine learning-based plant disease classification application that predicts plant diseases from uploaded leaf images.

🚀 Project Overview

This project uses a deep learning feature extractor combined with a Random Forest classifier to identify plant diseases from leaf images.

Users can upload an image through a Streamlit web interface and receive a predicted class along with the top 5 prediction probabilities.

🛠️ Technologies Used

* Python
* TensorFlow / Keras
* MobileNetV2
* Scikit-learn
* Random Forest Classifier
* Streamlit
* NumPy
* OpenCV

⚙️ Project Workflow

1. Upload a plant leaf image.
2. Resize the image to 224 × 224 pixels.
3. Preprocess the image using MobileNetV2 preprocessing.
4. Extract image features using the trained feature extractor.
5. Classify the extracted features using the Random Forest model.
6. Display the predicted class and top 5 predictions.

📁 Project Structure

plants_disease_detection/
│
├── app.py
├── train_knn.ipynb
├── feature_extractor_model.h5
├── feature_extractor_model.keras
├── rf_model.pkl
├── class_labels.npy
├── requirements.txt
└── README.md

💻 Installation and Usage

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

📊 Prediction Output

The application displays:

* Uploaded leaf image
* Predicted disease class
* Top 5 prediction probabilities

👨‍💻 Author

Sandeep C Vanmali

Electronics and Communication Engineering
Nitte Meenakshi Institute of Technology
