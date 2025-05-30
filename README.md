# Titanic Survival Prediction 🚢

This project aims to predict which passengers survived the Titanic disaster using machine learning. It is based on the Kaggle competition ["Titanic: Machine Learning from Disaster"](https://www.kaggle.com/competitions/titanic).

This is my first ML project which I ever made, so be a bit lenient in judging me. But feel free to provide your suggestions.

---

## 🧠 Model
- **Algorithm Used:** Random Forest Classifier
- **Initial Score:** ~0.70 accuracy on Kaggle public leaderboard

---

## 📊 Features Used
- Pclass
- Sex (one-hot encoded)
- SibSp
- Parch
- Fare (filled 1 missing value in test_data with mode)

---

## 🔧 Future Improvements
- Add missing `Age` values using imputation (Age is obviously important)
- Try other models like XGBoost or Logistic Regression
- Hyperparameter tuning

---

## 📁 Files
- `titanic-ml-competition.ipynb`: Code and model
- `requirements.txt`: Python dependencies

---

## 🚀 How to Run the Project
Follow these simple steps to run this project on your computer using Visual Studio Code (VS Code): 

### 1. Download the project
- Click the green **"Code"** button on this GitHub page.
- Select **"Download ZIP"**.
- Extract the ZIP file to any location on your computer.
### 2. Install Visual Studio Code
If you don't already have it, download and install **VS Code** from [https://code.visualstudio.com](https://code.visualstudio.com).
### 3. Install Python and Jupyter in VS Code
- Open VS Code.
- Install the **Python and Jupyter extension** if it's not already installed.
### 4. Open the Project
- In VS Code, go to **File > Open Folder**.
- Select the folder you extracted in Step 1.
### 5. Run the Notebook
- Open the file `titanic-ml-competition.ipynb`.
- The notebook will open inside VS Code.
- Click on **“Run All”** or run the cells one by one.

That's it! ✅ No need to install any extra libraries — this project only uses `pandas` and `numpy`, which usually come pre-installed with the Python extension in VS Code.

---

## ✍️ Author
- Felix John
