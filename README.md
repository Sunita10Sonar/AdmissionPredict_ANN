# 🎓 Admission Prediction using ANN (Regression Model)

## ⭐ Situation
Graduate school admission is highly competitive, and students often want to estimate their **chance of admission** before applying.  
Traditional statistical methods can struggle to capture the nonlinear relationships between factors such as GRE, TOEFL, CGPA, university rating, SOP, LOR, and research experience.

---

## 🎯 Task
The objective of this project is to **predict the probability of admission** based on a student’s profile by:  
- Preprocessing academic data.  
- Building and training an **Artificial Neural Network (ANN)** regression model.  
- Evaluating prediction accuracy with proper metrics.  

---

## 🔧 Action
Steps taken to achieve the task:  
1. **Data Exploration & Preprocessing**  
   - Cleaned and normalized the dataset.  
   - Performed exploratory data analysis (EDA) to understand correlations.  

2. **Feature Engineering**  
   - Selected key features (GRE, TOEFL, CGPA, etc.).  
   - Split the dataset into training and test sets.  

3. **Model Development**  
   - Built an ANN regression model using **TensorFlow/Keras**.  
   - Tuned hyperparameters (hidden layers, activation functions, optimizer).  

4. **Model Evaluation**  
   - Assessed accuracy using **Mean Squared Error (MSE)** and **R² score**.  
   - Visualized actual vs. predicted admission probabilities.  

---

## 📊 Result
- Successfully built an ANN regression model to predict **chance of admission** (0–1 scale).  
- Found that **CGPA, GRE, and Research experience** are the most influential factors.  
- Model provides a data-driven way for students to **assess admission likelihood** before applying.  

