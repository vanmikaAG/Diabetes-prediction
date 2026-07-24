## Diabetes Prediction using Machine Learning

This project predicts whether a person is diabetic or not using a Machine Learning model trained on the Pima Indians Diabetes Dataset. A simple Streamlit web application is used to take user input and display the prediction.

## Features
- Predicts diabetes based on health parameters.
- User-friendly Streamlit interface.
- Trained Machine Learning model saved using Pickle.
- Fast and easy prediction.

## Technologies Used
- Python
- Scikit-learn
- Pandas
- NumPy
- Streamlit
- Pickle

## Input Features
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

## Project Structure

├── source.py              # Streamlit application
├── diabetes.pkl           # Trained machine learning model
├── notebook.ipynb         # Model training notebook
├── README.md              # Project documentation
```

## How to Run

1. Clone the repository:
 bash
git clone https://github.com/your-username/diabetes-prediction.git


2. Install the required libraries:
bash
pip install streamlit scikit-learn pandas numpy


3. Run the Streamlit application:
 bash
streamlit run source.py


## Output
The application predicts whether the person is:
- **Diabetic**
- **Non-Diabetic**

## Future Improvements
- Improve model accuracy.
- Deploy the application on Streamlit Cloud.
- Add data visualization and prediction probability.

## Author
**Vanmika A.G.**
B.E. Computer Science Engineering
