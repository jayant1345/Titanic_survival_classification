# Titanic Survival Prediction Using Random Forest

This project is part of the **Fingertips Machine Learning Projects** series. It aims to predict the survival of passengers aboard the Titanic using a Random Forest Classifier. The dataset used is the famous [Titanic dataset](https://www.kaggle.com/c/titanic) from Kaggle.

## 📊 Project Objective

The objective is to build a predictive model that can accurately determine whether a passenger survived the Titanic disaster, using various features such as age, gender, class, fare, and family relations.

## 🛠️ Technologies Used

- Python 🐍
- Jupyter Notebook 📓
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Random Forest Classifier

## 📁 Project Structure

```bash
fingertips_project6_titanic_survival/
├── fingertips_project6_titanic_survival.ipynb
├── README.md
└── dataset/
    └── train.csv

```

🔍 Workflow
Data Loading – Load Titanic dataset

Data Exploration – Summary stats and visualizations

Data Cleaning – Handle missing values and convert categorical variables

Feature Engineering – Create new features, drop irrelevant ones

Model Building – Random Forest Classifier

Evaluation – Accuracy, confusion matrix, classification report

📈 Model Accuracy
The Random Forest model achieved good performance in classifying survival outcomes using default parameters. You may tune hyperparameters for better results.

📊 Sample Visualizations
Survival rates by class and gender

Correlation heatmap

Distribution plots (age, fare)

Feature importance plot from the model

🧠 Future Improvements
GridSearchCV for hyperparameter tuning

Ensemble learning methods

Cross-validation

💡 Conclusion
This notebook demonstrates the complete ML pipeline for classification tasks. Titanic dataset is ideal for beginners learning preprocessing, model training, and evaluation.

📎 License
This project is licensed under the MIT License.

🙋‍♂️ Author
Developed by Jayant Jayswal https://github.com/jayant1345
as part of the Fingertips ML Projects.

---
