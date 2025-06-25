# LandSlideX
🧠 AI-powered eyes on the Earth 🌍 Detecting landslides before they strike using machine learning data.
# Project overview/Introduction
LandSlideX is a machine learning-based system designed to detect landslide-prone areas using geospatial and satellite image data. 
It combines data preprocessing, feature extraction, and classification to analyze terrain risks with the help of AI.
This project is built in Google Colab for easy reproducibility and learning.
# Features
- 🌐 Works on satellite/geospatial datasets
- 🧠 Machine learning model for terrain classification
- 🖼️ Image processing and feature extraction
- 📊 Data visualization and evaluation
- 💡 Beginner-friendly Google Colab code blocks
# Dataaet
- Source: [Kaggle - Landslide Dataset](https://www.kaggle.com/datasets/sreeragunandha/landslide-prediction-dataset)
- Features -Temperature (°C) ,Humidity (%) ,Precipitation (mm),Soil Moisture (%),Elevation (m),Landslide Risk
# Project link for reference
 Demonstration Video- (https://drive.google.com/file/d/1IEIZGJ9rRCk4qP0kAVBbqbRrcmFmLp8J/view?usp=drive_link)
 Screenshots - Confusion Matrix (https://drive.google.com/file/d/19YS4QVFMfW36e_JxtZZn11mH6oJW8sh5/view?usp=sharing)
 - Correlation (https://drive.google.com/file/d/1bBDMU6DJeWXDOx4e0DMl1Sp0iQMFZ6e0/view?usp=sharing)
 - ROC Curve (https://drive.google.com/file/d/1MFec4NPkvXxTJEQeqd4dWRtdolWzmTL8/view?usp=sharing)
 - Learning Curve (https://drive.google.com/file/d/1weSMsymnyY1l3A5HwGY0CnmFPUEB7jOA/view?usp=sharing)
# Results
Accuracy Score: 0.9976

Classification Report:
               precision    recall  f1-score   support

          High      1.00      0.95      0.97        19
          Low       1.00      1.00      1.00      1128
     Moderate       0.99      0.98      0.99       102
    Very High       1.00      1.00      1.00         1

    accuracy                            1.00      1250
    macro avg       1.00      0.98      0.99      1250
    weighted avg   1.00      1.00      1.00      1250
