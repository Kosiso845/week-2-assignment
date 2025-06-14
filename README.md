# 🧠 Mental Health Treatment Predictor  
*AI for Sustainable Development – SDG 3: Good Health and Well-being*

## 📌 Overview

This project aims to address **UN Sustainable Development Goal 3 (SDG 3)**, which focuses on ensuring healthy lives and promoting well-being for all. Our AI-driven solution predicts whether an individual is likely to seek mental health treatment based on behavioral and workplace-related features. Early prediction enables better awareness campaigns and intervention planning.

---

## 📂 Project Structure

- `mental_health_predictor.ipynb` – Main model training notebook  
- `app.py` – Streamlit deployment file for the web app  
- `mental_health.csv` – Dataset used for training  
- `requirements.txt` – Python dependencies  
- `screenshots/` – Images showing model and app UI  
- `README.md` – This file
## ⚙️ ML Approach

- **Type:** Supervised Machine Learning  
- **Algorithm:** Logistic Regression  
- **Target:** Likelihood of seeking mental health treatment  
- **Tools:** Python, Pandas, Scikit-learn, Streamlit

**Key Steps:**
1. Data cleaning and preprocessing  
2. Feature engineering and selection  
3. Model training and evaluation (accuracy ~78%)  
4. Streamlit app deployment for public use



## 📊 Results

- **Accuracy:** 78%  
- **F1 Score:** 0.75  
- **Most Important Features:**  
  - Family history  
  - Age  
  - Workplace mental health support  
  - Awareness of mental health resources


## 🌍 Impact

This model helps:
- Employers and HR teams detect at-risk employees
- Promote early mental health awareness
- Contribute to **SDG 3.4: Reduce mental illness and promote well-being**


## ⚖️ Ethical Considerations

- Data anonymized to preserve privacy  
- Acknowledgement of potential dataset bias (focused on tech employees)  
- Promotes fairness and accessibility  
- Designed for low-cost, scalable impact

## 🚀 Demo

Launch the interactive web app using Streamlit:

```bash
streamlit run app.py
# week-2-assignment
