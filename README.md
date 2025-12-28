 Heart Disease Prediction System

 
 Project Overview 
 This project predicts whether a person has heart disease using Machine Learning.
The model is trained on medical data and deployed using Streamlit for user interaction.


## 🚀 Live Demo
(https://heartdiseaseprediction-9hsqgteacmokgguyxdrrw9.streamlit.app/)
---

 Project Workflow

1. Data Collection  
   - Used heart disease dataset (`heart.csv`)
   - Data includes medical attributes like age, blood pressure, cholesterol, etc.

2. Data Preprocessing  
   - Handled missing values
   - Feature selection
   - Feature scaling using StandardScaler
   - Saved scaler as `scaler.pkl`

3. Model Training  
   - Applied K-Nearest Neighbors (KNN) algorithm
   - Trained model on processed data
   - Saved trained model as `KNN_heart.pkl`

4. Feature Storage  
   - Stored input feature names using `columns.pkl`
   - Ensures correct input order during prediction

5. Model Evaluation  
   - Evaluated accuracy on test data
   - Verified model performance using confusion matrix and metrics

6. Model Serialization  
   - Saved trained model and preprocessing objects using Pickle
   - Files used:
     - `KNN_heart.pkl`
     - `scaler.pkl`
     - `columns.pkl`

7. Web Application Development  
   - Built interactive UI using Streamlit (`app.py`)
   - User enters medical details
   - Model predicts heart disease result

8. Deployment  
   - Project hosted on GitHub
   - Deployed using Streamlit Cloud

---

 Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Streamlit
- Pickle
- GitHub

---

 How to Run the Project 
pip install -r requirements.txt
streamlit run app.py
