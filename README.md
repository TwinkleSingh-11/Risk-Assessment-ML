

🚨 Machine Learning Framework for Risk Assessment of Gender-Based Crime (India)

> A data-driven approach to move from reactive policing to proactive public safety for women.




---

📌 Overview

Gender-based crime, especially crimes against women, remains one of the most critical social challenges in India. Traditional crime prevention systems are largely reactive, acting only after incidents occur.

This project leverages Machine Learning to predict and quantify crime risk at the district level, enabling early intervention, smarter resource allocation, and data-driven policymaking.

📊 By integrating crime statistics, economic indicators, and demographic data, this framework provides a continuous risk score instead of simple crime classification — offering deeper insights into regional crime vulnerability.


---

🎯 Project Objectives

🔍 Develop a machine learning-based risk assessment model for gender-based crimes

📈 Predict Total Crime Against Women using multi-source data

🧠 Identify key crime indicators contributing to high-risk regions

🛡️ Enable proactive decision-making for law enforcement & policymakers



---

🧠 Key Highlights

✨ Multi-Dimensional Dataset

Crime data (NCRB – 2022)

Economic data (GSDP)

Demographic data (Census 2011)


✨ Advanced Feature Engineering

Crime Rate per 100,000 population

Female-to-Male Ratio

Literacy Rate (%)


✨ Strong Insights

Cruelty by Husband or Relatives shows 0.86 correlation with total crime

Domestic violence acts as a major risk indicator, not an isolated issue


✨ Best Performing Model

🏆 Gradient Boosting Regressor

📊 R² Score: 0.874

📉 RMSE: 244



---

🛠️ Tech Stack

Programming Language: Python

Libraries & Tools:

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn


Environment: Jupyter Notebook / Google Colab



---

🤖 Machine Learning Models Used

Model	Purpose

Linear Regression	Baseline comparison
Random Forest Regressor	Non-linear pattern learning
Gradient Boosting Regressor	High-accuracy ensemble model


> ⚠️ Linear Regression showed near-perfect accuracy due to data leakage, hence ensemble models were preferred for reliability.




---

📊 Model Evaluation Metrics

R-squared (R²)

Root Mean Squared Error (RMSE)

Mean Squared Error (MSE)



---

🧩 Project Workflow

1. 📚 Literature Review


2. 📥 Data Collection (NCRB, MOSPI, Census)


3. 🧹 Data Cleaning & Preprocessing


4. 🧠 Feature Engineering


5. 🤖 Model Training & Comparison


6. 📊 Result Analysis & Visualization


7. 📝 Research Paper & Documentation




---

📌 Results Snapshot

Model	R² Score	RMSE

Linear Regression	0.999*	0.011
Random Forest	0.810	299.07
Gradient Boosting	0.874	244.00


*Linear Regression result affected by data leakage


---

🌍 Real-World Impact

This framework can be used to:

🚔 Identify high-risk districts

📍 Support targeted interventions

📊 Assist policymakers in evidence-based decisions

🛡️ Strengthen women safety strategies



---

⚠️ Limitations

Demographic data is from Census 2011

Crime data relies on reported cases only

Economic data available at state level, not district



---

🔮 Future Scope

📅 Use updated demographic & economic datasets

🧠 Explore deep learning & time-series models

📊 Build an interactive crime-risk dashboard

➕ Add variables like unemployment & education levels



---

👩‍💻 Contributors

Twinkle Singh
B.Tech CSE, IGDTUW

---

📄 Research & Internship Context

This project was developed as part of a Six-Weeks Summer Internship organized by
IGDTUW Anveshan Foundation.


---

⭐ If you found this project meaningful, don’t forget to star the repository!
Together, tech can drive social change 💙


---

