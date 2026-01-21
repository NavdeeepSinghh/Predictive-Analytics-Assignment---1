# 📊✨ Statistical Analysis of NO₂ Data (Predictive Analytics)

## 🚀 Overview
This project performs a **statistical analysis** on **NO₂ (Nitrogen Dioxide)** concentration data using a **controlled nonlinear transformation**.  
The goal is to preprocess the data 🧹, apply a transformation 🔧, and compute key statistical parameters 📐.

### 🔍 What this project does:
- ✅ Cleans and validates raw data  
- 🔁 Applies a nonlinear transformation  
- 📊 Computes statistical parameters (μ, σ², λ, c)  

---

## 🧾📁 Input Details

- 📄 **Input File:** `data.csv`  
- 🧪 **Column Used:** `no2`  
- 🔤 **Encoding:** `latin1`  

---

## ⚙️🛠 Libraries Used

- 🧮 **NumPy** – numerical computations  
- 🐼 **Pandas** – data loading & preprocessing  
- 📐 **Math** – mathematical operations  

---

## 🧹🔄 Data Preprocessing

Before analysis, the data goes through the following steps:

1️⃣ Load the CSV file using Pandas  
2️⃣ Clean column names (remove extra spaces)  
3️⃣ Convert NO₂ values to numeric format  
4️⃣ Remove invalid, missing, or negative values ❌  
5️⃣ Store clean data as a NumPy array ✅  

---

## 🔧📈 Data Transformation

The cleaned NO₂ values are transformed using the following function:

