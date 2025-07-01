# 🐝 Honey Bee Farm Yield Prediction | Kaggle Submission 2

Welcome to my second Kaggle competition submission!  
This project focuses on building a machine learning model to **predict the yield of honey** from bee farms using real-world features such as location, climate, and farm data.

---

## 📌 Problem Statement

The goal is to estimate the amount of honey that a bee farm will produce based on various input factors.  
This is a **regression problem**, and submissions were evaluated based on **Mean Absolute Error (MAE)**.

---

## 📊 Model Performance

| Metric | Value |
|--------|-------|
| ✅ Model Accuracy | **93%** |
| 📉 MAE (My Model) | **254** |
| 🥇 Lowest MAE on Leaderboard | **249** |

Despite missing the top MAE by just **5 units**, the model performed robustly across different states and conditions.

---

## 🧠 ML Approach

- 📊 **Exploratory Data Analysis** for trends, missing values, and outliers
- ⚙️ **Feature Engineering** for farm and climate attributes
- 🧪 Model: **LightGBM Regressor**
- 🔍 **Hyperparameter Tuning** using GridSearchCV
- 🧹 Scaling + Encoding handled using `Pipeline` from `scikit-learn`

---


## ⚠️ Note About Invalid Notebooks

If this notebook shows up as **"invalid" on Kaggle**, you can still view and run it using Google Colab:

### 🔄 View on Google Colab

1. Download `honey_yield_model.ipynb`
2. Go to [Google Colab](https://colab.research.google.com/)
3. Click `File → Upload Notebook`
4. Select the downloaded file
5. Run it and explore the code, output, and results!

---

## 🧾 Key Takeaways

- LightGBM outperformed Linear Regression and Decision Tree models on validation MAE.
- Feature importance revealed that **farm size** and **temperature** were critical predictors.
- The model generalized well with minimal overfitting due to cross-validation and regularization.

---

## 🔗 Connect With Me

- 🧠 Kaggle Profile → [Click Here](https://www.kaggle.com/akshat9105)
- 💼 LinkedIn Profile → [Click Here](https://www.linkedin.com/in/akshat-gupta-6a27a331a/)
- 💻 GitHub Repo → [Click Here](https://github.com/akshat09105)

---

## 🙌 Thank You!

Thanks for checking out my submission!  
Feel free to explore the notebook, suggest improvements, or fork it for your own experiments.

**Happy Learning!**  
— *Akshat Gupta*
