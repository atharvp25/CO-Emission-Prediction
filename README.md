# 🚗 CO₂ Emission Prediction (Car Data)

This project uses **Simple Linear Regression** to predict the **CO₂ emissions (g/km)** of cars based on their **engine size (L)**.  
It is my first machine learning project, built to practice the fundamentals of regression.

---

## 📂 Dataset
The dataset used is: **CO₂ Emissions (Canada)**  
- Source: [CO2 Emissions_Canada.csv](./CO2%20Emissions_Canada.csv)  
- Features:  
  - `Engine Size(L)` → Independent variable (X)  
  - `CO2 Emissions(g/km)` → Target variable (y)  

---

## 🧑‍💻 Workflow
1. Import necessary libraries (`pandas`, `numpy`, `matplotlib`, `sklearn`)  
2. Load dataset and explore basic information  
3. Scatter plot visualization of Engine Size vs CO₂ Emissions  
4. Train-test split (70% train / 30% test)  
5. Fit a **Linear Regression** model  
6. Predict CO₂ emissions on test data  
7. Evaluate model performance (R² Score, MSE, RMSE)  

---

## 📊 Results
- **R² Score:** ~0.72  
- **MSE:** ~939.44  
- **RMSE:** ~30.65  

👉 This means the model explains about **72% of the variation** in CO₂ emissions using engine size alone.  

---

## 📈 Visualization
- Scatter plot of training data  
- Regression line showing predicted CO₂ emissions  

*(You can find plots inside the notebook)*  

---

