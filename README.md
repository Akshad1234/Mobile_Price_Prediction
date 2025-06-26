# Mobile_Price_Prediction
📱 A machine learning project to predict mobile phone price range (low to very high) based on technical features like RAM, battery, camera, etc. 🤖 Uses classification algorithms to analyze mobile specs and determine the appropriate price category.
# 📱 Mobile Phone Price Range Prediction

This machine learning project predicts the price category of a mobile phone (Low, Medium, High, Very High) based on its hardware specifications and features. It aims to help retailers and manufacturers understand how different mobile attributes influence pricing.

## 🧠 Problem Statement
Build a classification model that categorizes mobile phones into one of four price ranges using features like battery power, RAM, camera quality, and more.

## 📂 Dataset Features
- `battery_power`: Battery capacity in mAh
- `blue`: Bluetooth support (0 or 1)
- `clock_speed`: Processor speed (GHz)
- `dual_sim`: Dual SIM support (0 or 1)
- `fc`: Front camera megapixels
- `four_g`: 4G support (0 or 1)
- `int_memory`: Internal memory (GB)
- `m_deep`: Depth of mobile (cm)
- `mobile_wt`: Weight (g)
- `n_cores`: Number of processor cores
- `pc`: Primary camera megapixels
- `px_height`, `px_width`: Pixel resolution
- `ram`: RAM (MB)
- `sc_h`, `sc_w`: Screen dimensions (cm)
- `talk_time`: Battery talk time (hours)
- `three_g`, `touch_screen`, `wifi`: Network and UI features (0 or 1)
- `price_range`: Target variable (0=Low, 1=Med, 2=High, 3=Very High)

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

## 🧪 Model Workflow
1. Data Cleaning & Preprocessing
2. Feature Correlation & Importance Analysis
3. Train-Test Split
4. Model Building (Random Forest, SVM, etc.)
5. Evaluation (Accuracy, Confusion Matrix)

## ✅ Results
Achieved high accuracy with tree-based classifiers and proper scaling & tuning.

## 📊 Use Case
Helps businesses determine the market value of a phone before launch based on specifications.

---
