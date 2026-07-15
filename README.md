# Student Placement Prediction using Naive Bayes

This project predicts whether a student is likely to be placed based on academic performance and skill-related attributes using the Naive Bayes classification algorithm.

The project demonstrates the complete Machine Learning workflow, including data preprocessing, feature scaling, model training, evaluation, visualization, and placement prediction.

---

## Features

- Student Placement Prediction
- Naive Bayes Classification
- Feature Scaling using StandardScaler
- Model Evaluation
- Classification Report
- Confusion Matrix
- Accuracy Comparison
- Data Visualization
- Probability-Based Prediction
- User Input Validation

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib

---

## Project Structure

```
student-placement-prediction-using-naive-bayes/
│
├── students_placement_10000.csv
├── placement_model.pkl
├── naive_bayes.py
└── README.md
```

---

## Dataset Features

The model uses the following input features:

- CGPA
- Aptitude Score
- Communication Skills
- Number of Projects
- Internship Status
- Certifications Count

### Target Variable

- Placement (Yes / No)

---

## Machine Learning Workflow

1. Load the dataset
2. Preprocess and clean the data
3. Apply feature scaling using StandardScaler
4. Split the dataset into training and testing sets
5. Train the Naive Bayes classifier
6. Evaluate model performance
7. Predict student placement
8. Save the trained model using Joblib

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/student-placement-prediction-using-naive-bayes.git
```

Navigate to the project folder:

```bash
cd student-placement-prediction-using-naive-bayes
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn joblib
```

Run the project:

```bash
python naive_bayes.py
```

---

## Model Evaluation

The model is evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

The project also provides visualizations for understanding model performance.

---

## Sample Input

```
CGPA: 8.5
Aptitude Score: 84
Communication Skills: 88
Projects: 4
Internship: Yes
Certifications: 5
```

### Sample Output

```
Prediction: Placed

Probability of Placement: 93.45%
```

---

## Learning Outcomes

- Data Preprocessing
- Feature Scaling
- Naive Bayes Classification
- Machine Learning Workflow
- Model Evaluation
- Data Visualization
- Model Serialization using Joblib

---

## Future Improvements

- Compare with Random Forest, SVM, KNN, and XGBoost
- Perform Hyperparameter Tuning
- Develop a Streamlit Web Application
- Deploy using Flask or FastAPI
- Integrate Explainable AI techniques (SHAP/LIME)

---

## Author

Developed as a Machine Learning project to explore the Naive Bayes classification algorithm for student placement prediction using Python and Scikit-learn.

## License

This project is intended for educational and learning purposes.
