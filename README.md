# 🎬 Movie Rating Prediction using Linear Regression

This project is submitted as **Task 1** of my internship at **SystemTron** under the **Generative AI Internship Track**.  
The objective was to build a **machine learning model** to predict **IMDb movie ratings** based on metadata such as **genre, director, actors, year, and duration**.

---

## 📁 Dataset

- Source: `IMDb Movies India.csv`  
- Columns used:  
  `Year`, `Duration`, `Genre`, `Director`, `Actor 1`, `Actor 2`, `Actor 3`, `Rating`

---

## 🛠️ Tools & Libraries Used

- Python
- pandas
- scikit-learn
- numpy

---

## 🧼 Data Preprocessing

- Extracted year and duration as numeric values using regex
- Removed rows with missing data
- Encoded categorical features (`Genre`, `Director`, `Actor 1`, `Actor 2`, `Actor 3`) using `OneHotEncoder`
- Built a pipeline using `ColumnTransformer` and `LinearRegression`

---

## 🧠 Model Workflow

| Step | Description |
|------|-------------|
| 📥 Load Data | IMDb India movie dataset |
| 🧹 Clean Data | Extracted valid `Year` and `Duration`, removed `NaN` rows |
| 🎛️ Preprocess | Used OneHotEncoding for categorical features |
| 📈 Model | Trained a Linear Regression model using a pipeline |
| 📊 Evaluation | Printed Mean Squared Error and R² Score |
| 🔮 Prediction | Took user input and predicted rating for a new movie |

---

## 📊 Evaluation Results

- **Mean Squared Error**: _(varies based on data)_
- **R² Score**: _(typically between 0.6 to 0.8 on clean data)_

---

## 🎯 Predict a Movie Rating

The script accepts user input for:

- Year  
- Duration  
- Genre  
- Director  
- Actor 1, 2, and 3

...and predicts the **expected IMDb rating** using the trained model.

---

## 👩‍💻 Author

**Sangamithra D**  
B.E. Computer Science & Engineering  
KCG College of Technology  
**Intern @ SystemTron – Generative AI Internship**  
🔗 [LinkedIn]https://www.linkedin.com/in/sangamithra-d-8a4092301?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app
🔗[LinkedIn Post]https://www.linkedin.com/posts/sangamithra-d-8a4092301_ai-machinelearning-python-activity-7334230377596620800-jrv3?utm_source=share&utm_medium=member_android&rcm=ACoAAE0Te3wBDPpSmrzX8PUb8qeOgFjMumrLltk

---


## 🙏 Acknowledgements

Thanks to **SystemTron** for guiding me through this exciting journey into machine learning and real-world data application.

---

## 🏷️ Tags

`#MachineLearning` `#LinearRegression` `#IMDbDataset` `#SystemTron` `#Python` `#MovieRatings` `#InternshipProject`
