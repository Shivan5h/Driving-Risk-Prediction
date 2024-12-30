# Driving Risk Prediction  

## Overview  
The **Driving Risk Prediction** project uses supervised machine learning algorithms to predict the driving risk score based on multiple factors such as driver's age, experience, weather conditions, road quality, time of day, and traffic. This system is designed to assist drivers in making informed decisions by evaluating the safety of their driving conditions in real time.  

The project includes:  
- An Android app interface for users.  
- A Flask backend for risk score predictions.  

## Features  
- **Risk Score Evaluation**: Provides a safety score to indicate driving difficulty.  
- **Personalized Predictions**: Takes into account individual factors like age and driving experience.  
- **Real-Time Inputs**: (Future Scope) Integrates live data feeds from weather and traffic APIs.  
- **User-Friendly Interface**: An intuitive Android app interface for risk analysis and results display.  

---

## Technology Stack  
- **Frontend**: Kotlin (Android app development)  
- **Backend**: Flask (Python-based API)  
- **Machine Learning**: Supervised algorithms for prediction  
- **Future APIs**:  
  - Weather API for real-time weather conditions  
  - Maps API for real-time traffic and geolocation  

---

## Dataset  
- **Data Used**: Includes historical data on driver characteristics (age, experience), environmental factors (weather, road quality, traffic), and driving conditions.  
- **Data Processing**: Preprocessing included handling missing values, normalization, and feature engineering to extract meaningful inputs for ML models.  

---

## Installation  

### Prerequisites  
1. **Python 3.8+**  
2. **Android Studio** (for app deployment)  
3. **Flask** (backend framework)  

### Steps  
1. **Backend Setup**  
   - Clone the repository:  
     ```bash  
     git clone https://github.com/Shivan5h/driving-risk-prediction.git  
     cd driving-risk-prediction/backend  
     ```  
   - Install dependencies:  
     ```bash  
     pip install -r requirements.txt  
     ```  
   - Run the Flask server:  
     ```bash  
     python app.py  
     ```  

2. **Android App**  
   - Open the Android project in Android Studio.  
   - Configure the backend API URL in the app settings.  
   - Build and deploy the app to your device/emulator.  

---

## Usage  
1. Open the Android app and log in.  
2. Input required data:  
   - Driver's age  
   - Driving experience  
   - Weather condition  
   - Time of day  
   - Road quality and traffic  
3. View the risk score and decision on whether it's safe to drive.  

---

## Future Scope  
- **Real-Time Data Integration**: Use traffic and weather APIs to provide live risk predictions.  
- **Enhanced Models**: Train the system with larger datasets for improved accuracy.  
- **Google Maps Plugin**: Develop a plugin to provide in-app driving risk predictions.  
- **Profile Management**: Leverage driving license data to calculate experience and verify user profiles.  

---

## Contributors  
- **Shivansh Shukla** (Machine Learning)  
- **Anchit Dixit** (Android App)  

---

## License  
This project is licensed under the MIT License. See the LICENSE file for details.  

---  
