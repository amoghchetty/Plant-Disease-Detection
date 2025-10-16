🌿 Plant Disease Detection using EfficientNetB4

This project is an AI-powered web application that automatically detects plant leaf diseases using a deep learning model built with EfficientNetB4. The system analyzes uploaded leaf images, identifies the type of disease, shows a confidence score, and provides recommended treatments.

By leveraging computer vision and transfer learning, this tool helps farmers, researchers, and agricultural professionals quickly diagnose common plant diseases and take preventive measures.

🧠 Key Features

🖼️ Upload a leaf image through an interactive web app

🔍 Real-time disease prediction using EfficientNetB4

📊 Displays prediction confidence score

💡 Provides treatment recommendations

🌱 Supports multiple plant species (Apple, Tomato, Potato, etc.)

🧩 Tech Stack

Python 3

TensorFlow / Keras

Streamlit

Pillow (PIL)

NumPy

🏗️ Model Overview

The model is built using EfficientNetB4 as the base network, trained on the PlantVillage dataset with transfer learning.
The architecture includes:

Global Average Pooling

Dropout (0.2)

Dense output layer with Softmax activation

🚀 How to Run Locally

1️⃣ Clone the repository:

```git clone https://github.com/<your-username>/Plant-Disease-Detection.git
cd Plant-Disease-Detection```

2️⃣ Install dependencies:

```pip install -r requirements.txt```

3️⃣ Download the trained model:

Since the model file is too large for GitHub, download it manually from Google Drive:

📥 Download plant_disease_recog_model_pwp.keras

After downloading, place it inside your project folder, for example:

Plant-Disease-Detection/

 ├── plant_disease_detection.py
 
 ├── class_indices.json
 
 ├── plant_disease_recog_model_pwp.keras(Google Drive Link):https://drive.google.com/file/d/19G_ljHJah0WpssFRYwF2UFn8iFiZbwbB/view?usp=drive_link
 
 ├── requirements.txt
 
 ├── Plant_Disease_Detection.ipynb

4️⃣ Run the Streamlit app:
```streamlit run plant_disease_detection.py```
