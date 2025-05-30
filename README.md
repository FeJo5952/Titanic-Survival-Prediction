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

Follow these steps to run the notebook on your local machine:

### 1. Clone the repository
Download the project to your computer using Git:

```bash
git clone https://github.com/FeJo5952/Titanic-Survival-Prediction.git
cd Titanic-Survival-Prediction
Alternatively, you can also download the ZIP from GitHub and extract it.

2. Install Python and Jupyter
Make sure Python and Jupyter are installed. You can use:

Anaconda (Recommended for beginners): Download Anaconda

Or install manually:

bash
Copy
Edit
pip install jupyter
3. Install required libraries
Inside the project folder, install all necessary Python libraries:

bash
Copy
Edit
pip install -r requirements.txt
4. Add the dataset
Download the Titanic dataset from the Kaggle Titanic Competition, and place the train.csv and test.csv files inside the data/ folder in this repo.

5. Launch the notebook
Start the Jupyter Notebook server:

bash
Copy
Edit
jupyter notebook
Then open titanic-ml-competition.ipynb in your browser and run the cells one by one.

vbnet
Copy
Edit

Let me know if you want this as a collapsible section or if you'd like it shortened fur

---

## ✍️ Author
- Felix John
