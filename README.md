Detection of Bioterrorism and PM2.5 Prediction Using Random Forest and SARIMA


Project Overview
This project focuses on predicting PM2.5 air pollution levels and detecting anomalies that could indicate bioterrorism threats. Using satellite data, weather information, and machine learning techniques, this system provides an early warning mechanism for public health and security interventions.

The model integrates:
- LightGBM for spatial predictions
- SARIMA (Seasonal ARIMA) for time-series forecasting
- Hybrid Model (SARIMA + LightGBM) to enhance predictive accuracy

Features
Air Pollution Forecasting: Predicts PM2.5 concentrations based on satellite and weather data.
Hybrid Model: Combines statistical and machine learning models for improved accuracy.
Anomaly Detection: Identifies unusual patterns in PM2.5 that could signal bioterrorism risks.


 Installation & Setup
 Clone the Repository
bash
https://github.com/olayidecodes/detection-of-bioterrorism.git
cd your-repo


 Set Up Virtual Environment (Optional but Recommended)
bash
python -m venv venv
source venv/bin/activate    For Linux/macOS
venv\Scripts\activate       For Windows


Install Dependencies
bash
pip install -r requirements.txt


Run the Project
bash
python main.py


---
Model Training & Evaluation
 Train the Model
bash
python scripts/train_model.py



---
 📌 Usage
- For Researchers: Analyze PM2.5 trends and anomaly detection.
- For Government Agencies: Use the model for real-time air quality monitoring and public health planning.
- For Security Analysts: Assess air pollution anomalies for potential bioterrorism threats.

---
 Future Improvements
🔹 Integrate deep learning models (LSTMs, CNNs) for enhanced time-series forecasting.
🔹 Deploy the model as a real-time web application using FastAPI or Flask.
🔹 Optimize computational performance for large-scale real-time predictions.

---
 Contributors
- Matthews Victoria Olayide - Researcher
- Dr. B.I. Ayinla - Project Supervisor
- Dr. Taiwo (Department of Urban & Regional Planning)


For questions or collaborations, reach out via:
📧 Email: olayidecodes@gmail.com
🔗 GitHub: (https://github.com/olayidecodes/)

