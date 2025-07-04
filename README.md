# 🎓 Placement Package Prediction using Linear Regression

This project demonstrates a simple yet effective use of **Linear Regression** to predict the placement package of students based on their CGPA using Python and scikit-learn.

## 📊 Dataset
The dataset contains:
- `cgpa`: Student's academic CGPA
- `package`: Placement package in LPA (Lakhs per Annum)

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- scikit-learn

## 🚀 Steps Performed
1. Loaded and cleaned the dataset
2. Visualized data using a scatter plot
3. Applied train-test split
4. Trained a Linear Regression model
5. Plotted predictions vs original data
6. Predicted package for any given CGPA

## 📈 Result
The model learns a line of best fit to predict a student’s placement package from CGPA. Here's the plot:

![Prediction Line](placement_prediction_clean.png)

## 🧠 What I Learned
- How to apply Linear Regression using scikit-learn
- The importance of reshaping data for model prediction
- Visualizing trends using matplotlib and seaborn

## 🔍 Example Prediction
Predicting for CGPA = 8.1:
```python
lr.predict([[8.1]])
