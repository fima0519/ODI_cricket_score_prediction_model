# ODI Cricket Score Prediction Model

A machine learning project that predicts **One Day International (ODI) cricket scores** using historical match data and regression techniques. This project demonstrates data preprocessing, feature engineering, model training, evaluation, and prediction for cricket matches.

## 🛠 Technologies Used

- **Python** – Core programming language  
- **scikit‑learn / ML libraries** – Machine learning algorithms and preprocessing tools  
- **Pandas & NumPy** – Data manipulation and analysis  
- **Jupyter Notebook or Google Colab** – Code exploration and model training environment  

## 🔹 Overview

This model predicts the score a batting team is likely to achieve **after completing 50 overs**, given the current situation in the innings.  

**Features used for prediction include:**

- Batting team  
- Bowling team  
- Current over and ball  
- Total score and current score  
- Wickets fallen  
- Runs scored in the last 5 overs  
- Balls bowled  
- Current run rate  

**Note:** The first five overs are excluded from prediction because the total for the first five overs can only be summed after they are completed.

---

## 📥 Dataset

- Historical ODI match data from **2006 to 2019** was collected from sources such as **Kaggle**.  
- The dataset enables the model to **accurately predict scores for 2018**, and predictions for 2023 generally differ from actual scores by **10–20 runs**.
👉 **Dataset link:**  
https://drive.google.com/file/d/1mdZ5pFsARVbR1Q6bCKksV4jnmsBPhZit/view?usp=drive_link :contentReference[oaicite:1]{index=1}

Once downloaded, place the dataset file in the project folder before executing the code.


---

## 🧹 Data Cleaning and Processing

1. **Missing data handling** – Removed irrelevant or incomplete values.  
2. **Feature selection & reduction** – Eliminated redundant or dependent columns.  
3. **Feature engineering** – Calculated:  
   - Runs scored in the last 5 overs  
   - Current run rate  
   - Total wickets and balls bowled  
4. **Train-test split** – Dataset split into training and testing sets for model evaluation.  

---

## 🛠 Methodology / Model Training

The model was trained using multiple machine learning algorithms:

1. **Random Forest Regression**  
2. **Linear Regression**  
3. **Decision Tree Regression**  
4. **Polynomial Regression**  

The trained models predict the **final score** based on the current match situation.

---


## 🚀 Getting Started

1. **Clone the repository:**
   git clone https://github.com/fima0519/ODI_cricket_score_prediction_model.git
   
2. Install dependencies:
   pip install -r requirements.txt
(if you have a requirements.txt. If not, install common libs like scikit‑learn, pandas, numpy, jupyter)

3. Open the Jupyter Notebook:

jupyter notebook ODI_Cricket_Score_Prediction.ipynb
or,
you can run in google colab.

4.Run each cell to preprocess data, train the model, and test predictions.

