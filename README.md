# Brain Stroke Prediction System

## Project Overview
The Brain Stroke Prediction System is a machine learning project aimed at predicting the likelihood of a patient experiencing a brain stroke based on various health and demographic attributes. This system utilizes several machine learning models, including KNN, Decision Tree, Logistic Regression and Support Vector Machine (SVM), to analyze the data and make predictions. Additionally, a user-friendly Graphical User Interface (GUI) is developed to facilitate easy data entry and prediction retrieval.

## Dataset Description
The dataset used in this project includes the following attributes:
- `id`: Unique identifier
- `gender`: Gender of the patient (Male, Female, Other)
- `age`: Age of the patient
- `hypertension`: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
- `heart_disease`: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
- `ever_married`: Yes if the patient is married, No if the patient is not married
- `work_type`: Profession of the patient (children, Govt_job, Never_worked, Private, Self-employed)
- `Residence_type`: Residence category of the patient (Rural, Urban)
- `avg_glucose_level`: Average glucose level in the blood of the patient
- `bmi`: Body Mass Index of the patient
- `smoking_status`: Smoking status of the patient (formerly smoked, never smoked, smokes, Unknown)
- `stroke`: 1 if the patient had a stroke, 0 if not

## Project Steps
1. **Data Collection**: The dataset is collected and imported for analysis.
2. **Data Pre-processing**: The data is cleaned and pre-processed, including handling missing values and encoding categorical variables.
3. **Exploratory Data Analysis (EDA)**: Visualizations and statistical analyses are performed to understand the data distribution and relationships between features.
4. **Model Design**: Various machine learning models (Decision Tree, KNN, SVM, Logistic Regression) are designed and trained.
5. **Model Evaluation**: Models are evaluated based on metrics such as Accuracy, Precision, Recall, and F1 Score.
6. **Comparative Analysis**: The performance of different models is compared to identify the best-performing model.
7. **Result**: The best-performing model is selected for prediction.
8. **GUI Development**: A user-friendly GUI is developed using Tkinter to facilitate easy data entry and stroke prediction.

## Key Findings
- The SVM model demonstrated superior performance in predicting strokes compared to other models.
- Significant factors influencing stroke prediction include age, hypertension, heart disease, average glucose level, and BMI.
- The developed GUI enhances user experience by providing a simple interface for making predictions.

## How to Run the Project
### Prerequisites
- Python 3.x
- Required Python libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, tkinter

### Steps to Run
1. Clone the repository:
   ```bash
   git clone <git@github.com:Alishabhojani/Brain-Stroke-Prediction-System.git>
   cd <brainstroke>


## Install the required libraries:
pip install pandas numpy scikit-learn matplotlib seaborn tkinter

## Run the Jupyter Notebook for model training and evaluation:
jupyter notebook brain-stroke.ipynb

## Execute the GUI script to launch the interface
python gui_stroke_prediction.py

## File Descriptions
brain_stroke.csv: The dataset used for training and evaluation.
brain-stroke.ipynb: Jupyter Notebook containing data analysis, model training, evaluation and GUI.
README.md: Project documentation.

## Acknowledgment
This project was developed as part of the Machine Learning course at Salim Habib University, Karachi, Pakistan. Special thanks to Dr. Rizwan Ahmed Khan for guidance and support.

## Contact
For any inquiries or feedback, please contact Alisha Fatima at [alishafatimabhojani@gmail.com].






"# Brain-Stroke-Prediction" 
