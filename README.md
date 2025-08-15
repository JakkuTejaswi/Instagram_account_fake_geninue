# Instagram Account Real vs Fake Prediction

## 📌 Overview
This project uses **Machine Learning** to predict whether an Instagram account is **real** or **fake** based on various profile features such as follower count, following count, post count, privacy status, and username similarity.

The classification model is built using **Python** and **scikit-learn**, with exploratory data analysis performed using **Pandas**, **Matplotlib**, and **Seaborn**.

---

## 📊 Dataset
- **Source**: train.csv,
              test.csv
- **Features**:
  - #followers – Number of followers
  - #follows – Number of accounts followed
  - #posts – Number of posts
  - private – Whether the account is private (1 = Yes, 0 = No)
  - name==username – Whether the display name matches the username (1 = Yes, 0 = No)
  - **Target**: fake – 1 = Fake account, 0 = Real account

---



**requirements.txt**
numpy
pandas
matplotlib
seaborn
scikit-learn

---

## 🚀 Project Workflow
1. **Data Loading & Cleaning**
   - Removed duplicates
   - Checked for missing values
2. **Exploratory Data Analysis (EDA)**
   - Distribution plots for features
   - Correlation heatmap
   - Boxplots and scatter plots
3. **Feature Engineering**
   - Encoded categorical features
4. **Model Building**
   - Used RandomForestClassifier
   - Train-test split for model evaluation
5. **Model Evaluation**
   - Accuracy, precision, recall, and F1-score

---

## 📈 Results
- **Model**: RandomForestClassifier
- **Performance**: Achieved high accuracy in classifying accounts as real or fake.
- **Key Insights**:
  - Fake accounts often have unusually high following-to-follower ratios.
  - Accounts with name==username = 1 tend to be more genuine.

---

## 📷 Sample Visualizations
- Correlation heatmap of features
- Boxplots showing distribution of followers, follows, and posts
- Pie charts of account type distribution

---

## 🔮 Future Improvements
- Experiment with more models (XGBoost, Logistic Regression, etc.)
- Apply hyperparameter tuning
- Collect more diverse Instagram account data
- Deploy model as a web app

---

## 📜 License
This project is licensed under the MIT License.


