# Detection_of_pcod_usingML
Repo for detection of pcod
PCOD Prediction Model
The PCOD Prediction Model is a machine learning application that predicts the likelihood of a person having Polycystic Ovary Syndrome (PCOD) based on several health parameters and lifestyle factors. PCOD is a common hormonal disorder that affects women of reproductive age. This model uses various features such as age, weight, BMI, cycle length, and symptoms like hair loss, pimples, and others to provide a prediction.

How It Works
Data Collection: The model is trained on a dataset that includes multiple features relevant to PCOD detection. These features range from physical characteristics like age, weight, and BMI, to lifestyle factors such as diet (e.g., fast food consumption) and common symptoms associated with PCOD like hair growth, pimples, and skin darkening.

User Input: The application asks the user to input values for these features. This data may include:

Age: The age of the individual.
Weight: The individual's weight.
BMI (Body Mass Index): A measure of body fat based on height and weight.
Cycle Length: The length of the individual’s menstrual cycle.
AMH (Anti-Müllerian Hormone): A hormone involved in regulating the menstrual cycle.
Symptoms such as weight gain, hair growth, skin darkening, hair loss, pimples, and lifestyle factors like fast food consumption.
Model Prediction: After the user submits the data, the model processes the information and predicts whether the person has PCOD or not. The model provides a result indicating whether PCOD is detected or PCOD is not detected based on the combination of input features.

Machine Learning Model: The prediction is powered by a machine learning model trained on historical data. A Random Forest Classifier or another suitable algorithm is used to predict the likelihood of PCOD based on the input features. The trained model uses patterns and relationships in the data to make an informed prediction.

User Interface: The frontend is built using React to provide an interactive user experience. The user enters their data in a simple form, and upon clicking the "Predict" button, the application displays the result.

Features
Simple User Interface: Easy-to-use form where users can input relevant health details.
Real-time Prediction: The model predicts PCOD based on user inputs in real-time.
Machine Learning Powered: Uses a trained machine learning model to make accurate predictions based on provided data.
Symptom-based Assessment: Includes common symptoms like hair loss, pimples, and others in the prediction criteria.
Technologies Used
Flask: The backend is built using Flask, which handles the API for prediction and serves the machine learning model.
React: The frontend is developed using React for building the user interface.
Machine Learning: The core of the application is based on machine learning, where a Random Forest Classifier or similar algorithm is used to make predictions about PCOD.
Joblib: Used for saving and loading the trained machine learning model.
Installation and Setup
The project requires both backend (Flask) and frontend (React) setups:

The backend handles the prediction logic and model loading.
The frontend is a web application that allows users to input their data and receive predictions.
Conclusion
This project aims to help individuals understand their risk of having PCOD based on personal health information. By leveraging machine learning, the application can provide insights into the likelihood of PCOD, helping users make informed decisions and seek further medical consultation.
