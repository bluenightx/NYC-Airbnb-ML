# NYC Airbnb Price Prediction | Machine Learning Project

A data science and machine learning project that analyzes **New York City Airbnb listings** and builds a **pricing prediction model** to support real-world business and expansion decisions for a hospitality management context.

This project demonstrates an **end-to-end ML workflow**, from exploratory data analysis to model evaluation, with a strong focus on **interpretability and business value**.

---

## 🔎 Business Context

New York City is one of the most competitive short-term rental markets in the world, with:

- 60M+ annual visitors  
- Strong demand for alternative accommodations  
- Increasing importance of **professional pricing strategies**

The goal of this project is to **identify pricing drivers** and build a model that can suggest **competitive market entry prices** rather than exact price certainty.

---

## 🎯 Project Objectives

- Analyze Airbnb market distribution across NYC boroughs  
- Identify key factors influencing listing prices  
- Build and compare multiple regression models  
- Balance predictive performance with interpretability  
- Deliver actionable insights for pricing strategy  

---

## 🧠 Key Insights

### Market Structure
- **Manhattan and Brooklyn dominate the market**, each representing ~42% of listings
- **Shared rooms are the least popular** room type across all boroughs
- Manhattan and Brooklyn have a higher concentration of **entire homes/apartments**
- Queens, Bronx, and Staten Island rely more heavily on **private rooms**

### Pricing Patterns
- **Manhattan is the most expensive borough**
- **Entire homes/apartments** are the most expensive room type overall
- Bronx and Staten Island are consistently the **lowest-priced areas**

### Safety & Demand
- **Manhattan is the only borough where listing density exceeds crime rate**, indicating stronger perceived safety relative to market activity

---

## 📁 Dataset & Features

The dataset includes:

- Price  
- Borough and neighborhood  
- Room type  
- Availability  
- Number of reviews  
- Geographic coordinates (latitude, longitude)  
- Safety-related indicators  

The final cleaned dataset used for modeling is:

clean_airbnb_crime - Final.csv


---

## ⚙️ Machine Learning Approach

### Models Evaluated
- K-Nearest Neighbors  
- Linear Regression  
- Decision Tree  
- Random Forest  
- **Lasso Regression**  
- XGBoost Regression  

### Model Evaluation
- Train/test split
- Performance measured using regression scores (R²)
- Focus on **generalization**, not just training accuracy

### Final Model Choice
- **Lasso Regression (~67% accuracy)**  
- Chosen for:
  - Interpretability  
  - Stability  
  - Business usability  

While more complex models showed potential, Lasso provided the **best balance between performance and explainability**.

---

## 📈 Results Summary

- Best model accuracy: **~67%**
- Model is **useful but not perfect**
- Provides strong **directional pricing guidance**
- Suitable for **competitive market entry decisions**

This model is intended to **support decision-making**, not replace human judgment.

---

## 🛠 Tech Stack

- Python  
- Jupyter Notebook  
- pandas, numpy  
- scikit-learn  
- matplotlib, seaborn  

---

## 📂 Repository Structure

```text
NYC-Airbnb-ML/
├── clean_airbnb_crime - Final.csv   # Final cleaned and enriched dataset used for modeling
├── EDA.ipynb                        # Exploratory Data Analysis and market insights
├── Data Cleaning -Final.ipynb       # Data preprocessing and feature engineering
├── Test-Final.ipynb                 # Model training and evaluation
├── Test-Final - Target eco.ipynb    # Alternative target modeling and comparison
├── Tuning.ipynb                     # Hyperparameter tuning and optimization
└── README.md                        # Project documentation
```



---

## 🚀 Future Improvements

- Add amenities and text-based features
- Incorporate seasonality effects
- Apply cross-validation pipelines
- Improve accuracy beyond the 67% benchmark
- Deploy model as a pricing decision support tool


---
## 🔗 Sources & References

- [NYC Aibnb data 2024](https://www.kaggle.com/datasets/vrindakallu/new-york-dataset)
- [📊 Final Presentation ](https://www.canva.com/design/DAGzysq-lm4/KefSm9MJj-55x8RIL7Qu9Q/edit?utm_content=DAGzysq-lm4&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton): Overall project and key findings.

---
## 👨‍💻 Author

**Anaísa Sena**   
GitHub: [AnaisaSena](https://github.com/bluenightx)

**Madhuridevi Dharmaraj**   
GitHub: [MadhurideviDharmaraj](https://github.com/MadhurideviD)

---

## 📜 License

This project is intended for educational and demonstration purposes. You are free to use and adapt it with credit.
