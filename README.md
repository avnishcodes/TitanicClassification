# TitanicClassification
Decision Tree classification on the Titanic dataset with hyperparameter tuning

# Titanic Decision Tree Classification 🚢🌳

This project implements an end-to-end classification pipeline on the classic Titanic dataset. It uses a Decision Tree classifier to predict passenger survival based on features like age, ticket class, siblings/spouses, parents/children aboard, and fare.

## ✅ Project Features

- 📥 **Data loading**  
  Loads the Titanic dataset from a GitHub-hosted CSV.

- 🛠️ **Model training**  
  Trains a Decision Tree classifier on selected features.

- 📊 **Evaluation metrics**  
  Calculates accuracy, precision, recall, specificity, and displays a confusion matrix.

- 🔎 **Hyperparameter tuning**  
  Uses GridSearchCV to find the best max depth and criterion.

- 🌳 **Tree visualization**  
  Plots a visual representation of the trained decision tree.

- 📈 **Feature importance analysis**  
  Ranks features based on their importance to the model’s decisions.

## 🚀 Usage

1. Clone this repository:
    ```bash
    git clone https://github.com/avnishcodes/TitanicClassification.git
    cd TitanicClassification
    ```

2. Open [Google Colab](https://colab.research.google.com) and load the notebook:
    - Use the raw link to `Titanic_Classification.ipynb` or upload it manually.

3. Run the notebook cells step by step.

## 📁 Files

- `train.csv` – The Titanic dataset.
- `Titanic_Classification.ipynb` – The analysis notebook.

## 📌 Requirements

This project runs in Google Colab and requires:
- pandas
- scikit-learn
- matplotlib
- seaborn

All of these are pre-installed in Colab.

## 📷 Outputs

- Model evaluation metrics printed directly.
- Decision tree plot.
- Feature importance bar chart.

---

Feel free to fork, modify, or expand this project! 😊
