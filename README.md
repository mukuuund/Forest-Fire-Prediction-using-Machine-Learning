# Forest Fire Prediction using Machine Learning

This project predicts the occurrence of forest fires using Machine Learning techniques based on environmental and weather conditions. The system analyzes historical forest fire data and identifies patterns that indicate fire-prone situations, helping in early detection and prevention.

---

## Project Overview

Forest fires are a major environmental threat that can cause severe damage to forests, wildlife, and human life. Early prediction of forest fires using environmental parameters such as temperature, humidity, rainfall, and wind speed can help authorities take preventive measures.

This project uses Machine Learning algorithms such as Random Forest, Support Vector Machine (SVM), Logistic Regression, and XGBoost to predict whether a forest fire will occur or not.

---

## Objectives

- Analyze forest fire and environmental data
- Identify key factors influencing forest fire occurrence
- Train and evaluate machine learning models
- Predict forest fire occurrence accurately
- Support early detection and disaster prevention

---

## Dataset

The dataset contains environmental and meteorological parameters such as:

- Temperature
- Relative Humidity (RH)
- Wind Speed (Ws)
- Rainfall
- Fire Weather Index components (FFMC, DMC, DC, ISI, BUI, FWI)
- Region information
- Fire occurrence (Target variable)

Dataset files included:

forest1.csv  
forest2.csv  

---

## Technologies Used

- Python
- Jupyter Notebook
- Machine Learning

Libraries Used:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

## Machine Learning Algorithms Used

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest Classifier
- XGBoost Classifier

Random Forest and XGBoost showed the best performance in predicting forest fires.

---

## Project Workflow

1. Data Collection  
2. Data Preprocessing  
   - Handling missing values  
   - Removing duplicates  
   - Feature selection  
3. Exploratory Data Analysis  
4. Feature Engineering  
5. Model Training  
6. Model Evaluation  
7. Prediction  

---

## Results

- Machine Learning models successfully predicted forest fire occurrence.  
- Random Forest and XGBoost achieved the highest accuracy.  
- Important features influencing prediction include Temperature, Relative Humidity, Rainfall, FFMC, and Wind Speed.  
- The model effectively identifies fire-prone conditions.

---

## Future Scope

- Integration with real-time weather data  
- Use of Deep Learning models such as Artificial Neural Networks and LSTM  
- Deployment as web or mobile application  
- Integration with GIS and IoT sensors  
- Real-time forest fire monitoring system  

---

## Project Structure

Forest-Fire-Prediction-using-Machine-Learning/

Forest_Fire_Prediction_using_Machine_Learning.ipynb  
forest1.csv  
forest2.csv  
Forest_Fire_Prediction_Presentation.pdf  
README.md  
.gitignore  

---

## How to Run the Project

Clone the repository:

git clone https://github.com/mukuuund/Forest-Fire-Prediction-using-Machine-Learning.git

Open Jupyter Notebook:

jupyter notebook

Run the notebook file:

Forest_Fire_Prediction_using_Machine_Learning.ipynb

---

## References (IEEE Format)

[1] P. Cortez and A. Morais, "A Data Mining Approach to Predict Forest Fires using Meteorological Data," 2007.

[2] UCI Machine Learning Repository, Forest Fires Dataset.

[3] Scikit-learn Documentation, https://scikit-learn.org/

[4] T. Chen and C. Guestrin, "XGBoost: A Scalable Tree Boosting System," 2016.

---

## Author

Mukund Nigam  
MS Elevate AICTE Internship – January 2026  

GitHub:  
https://github.com/mukuuund  

---

## Acknowledgment

This project was completed as part of the Microsoft Elevate AICTE Internship Program.
