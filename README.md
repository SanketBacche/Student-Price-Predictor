# Student Placement Predictor 🎓

## 📌 Project Overview
Student Placement Predictor is a machine learning project that predicts whether a student will be placed based on input features such as academic performance and other student-related attributes. The project uses classification algorithms to analyze student data and make placement predictions.

## 🎯 Objectives
- Analyze student placement data using Python.
- Train machine learning classification models.
- Compare different algorithms based on accuracy.
- Predict student placement outcomes.
- Save a trained model for future predictions.

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook
- Pickle

## 📂 Dataset
The project uses a dataset named `students_placement.csv`.

- **Input features (`X`):** All columns except `placed`.
- **Target variable (`y`):** `placed`, which represents the placement outcome.

The notebook uses a train-test split with 80% of the data for training and 20% for testing.

## 🤖 Machine Learning Algorithms
The notebook explores the following classification algorithms:

1. **Logistic Regression** – Predicts placement outcomes using a linear classification approach.
2. **Random Forest Classifier** – Combines multiple decision trees to make predictions.
3. **Support Vector Classifier (SVC)** – Uses an RBF kernel to classify student data.

The notebook evaluates model performance using the accuracy score.

## ⚙️ Project Workflow
1. Import the required Python libraries.
2. Load the student placement dataset.
3. Explore the dataset.
4. Separate input features and the target variable.
5. Split the dataset into training and testing sets.
6. Standardize features for Logistic Regression.
7. Train and evaluate the classification models.
8. Save the trained SVC model using Pickle.
9. Make a sample placement prediction.

## 🚀 How to Run the Project

### 1. Clone the repository
```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd student-placement-predictor
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your actual GitHub repository URL.

### 2. Install dependencies
```bash
pip install numpy pandas scikit-learn jupyter
```

### 3. Add the dataset
Place `students_placement.csv` in the notebook's working directory.

### 4. Start Jupyter Notebook
```bash
jupyter notebook
```

Open `student-placement-predictor.ipynb` and run the cells in order.

## 📁 Project Structure
```text
student-placement-predictor/
│
├── student-placement-predictor.ipynb
├── students_placement.csv
├── model.pkl
└── README.md
```

`model.pkl` is created when the notebook's model-saving cell is executed.

## 💡 Key Features
- Student placement prediction using machine learning.
- Comparison of three classification algorithms.
- Model evaluation using accuracy.
- Saving a trained SVC model for reuse.

## 🔮 Future Improvements
- Build a web application using Streamlit or Flask.
- Add more relevant student features.
- Improve model performance through hyperparameter tuning.
- Add a user-friendly interface for entering student details.
- Evaluate the model using precision, recall, F1-score, and a confusion matrix.

## ⚠️ Disclaimer
This project is intended for educational purposes. Predictions are estimates and should not be used as the sole basis for real student placement decisions.

## 👨‍💻 Author
**Sanket Bacche**
linkedin.com/in/sanket-bacche-00320a380 - LinkedIN Link

Artificial Intelligence and Data Science Student

## ⭐ Conclusion
This project demonstrates how machine learning classification algorithms can be used to predict student placement outcomes and how a trained model can be saved for future use.
