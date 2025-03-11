# 🖥️ Harmful-Brain-Activity-Classification-with-KerasCV-and-Keras

## 📄 Project Overview
This project leverages **deep learning** techniques to analyze medical images and predict health conditions. It utilizes **Keras and TensorFlow** with pre-trained models to enhance accuracy and efficiency. The goal is to develop a robust and scalable AI-based medical diagnostic tool.

## 📊 Dataset & Model Information
- **Dataset:** Contains labeled medical images for training and evaluation.
- **Model:** Deep learning model trained using **KerasCV**.
- **Metadata:**
  - **Keras version:** 3.0.3
  - **KerasCV version:** 0.7.0
  - **Parameter count:** 8,769,374
  - **Date saved:** 2023-12-29

## 📚 Approach
### 1. Data Preprocessing
- Performed **image normalization** and augmentation.
- Resized images to match model input dimensions.
- Split dataset into **train (80%) and test (20%)** sets.

### 2. Model Training
- Used **Transfer Learning** with KerasCV models.
- Fine-tuned model for medical image classification.
- **Optimizer:** Adam with learning rate scheduling.
- **Loss Function:** Categorical Crossentropy.

## 🔮 Performance Evaluation
- **Accuracy:** Achieved high validation accuracy.
- **Loss Metrics:** Monitored to prevent overfitting.
- **Confusion Matrix:** Used for error analysis.

## 🚀 How to Run the Project
### 1. Clone the Repository
```bash
git clone https://github.com/your-username/harmful-brain-activity-classification.git
cd harmful-brain-activity-classification
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Train the Model
```bash
python train.py
```

### 4. Make Predictions
```bash
python predict.py --input "sample_image.jpg"
```

### 5. (Optional) Run Web Interface
```bash
streamlit run app.py
```

## 🔄 Future Improvements
- Integrate **real-time image processing**.
- Improve **model explainability** using Grad-CAM.
- Deploy the model as a **cloud-based API**.

## 🏥 Conclusion
Deep learning has the potential to **revolutionize medical diagnostics** by providing fast and accurate predictions. This project demonstrates the feasibility of AI-powered medical image analysis for **early disease detection and better patient care**.

