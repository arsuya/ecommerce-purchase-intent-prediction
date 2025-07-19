# E-Commerce Visitor Purchase Intent Prediction

## Repository Structure
1. **README.md** – Project overview and documentation.  
2. **app.py** – Main file for running the Streamlit app and managing page navigation.  
3. **eda.py** – Exploratory Data Analysis (EDA) visualizations.  
4. **home.py** – Dashboard home page containing project description, objectives, and model information.  
5. **prediction.py** – Page for purchase prediction input.  
6. **model_terbaik.pkl** – Pre-trained best machine learning model.  
7. **ecommerce_purchasing_intention.csv** – Main dataset.  
8. **P1M2_arvin_wibowo.ipynb** – Notebook for exploration and model training.  
9. **P1M2_arvin_wibowo_inf.ipynb** – Notebook for inference and deployment.  
10. **url.txt** – Dataset and Streamlit deployment links.  
11. **tipe_data.png** – Dataset description image.  

---

## Problem Background
One of the major challenges faced by e-commerce platforms is the low conversion rate of visitors into paying customers. While websites may receive a high number of daily visitors, the majority of these visits do not result in a purchase.  
To address this, the management team aims to develop a machine learning model to predict purchase intent. By identifying users who are likely to make a purchase, the company can implement more targeted and effective marketing strategies.

---

## Project Output
This project delivers:
- A machine learning model that predicts whether a website visitor is likely to complete a purchase.  
- An interactive Streamlit dashboard that displays EDA results and provides a real-time purchase intent prediction feature.

---

## Data
The dataset used is the **Online Shoppers Purchasing Intention Dataset** from the UCI Machine Learning Repository.  
- It consists of **10 numerical** and **8 categorical features**.  
- The dataset contains **no missing values**.

---

## Methodology
The project adopts a **supervised learning** approach for classification. Several machine learning algorithms were evaluated, including:
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- Decision Tree  
- Random Forest  
- XGBoost  

The best-performing model was selected based on the **highest recall score**, as the main goal is to correctly identify as many potential buyers as possible.

---

## Tech Stack
- **Programming Language:** Python  
- **Tools:** Jupyter Notebook, Visual Studio Code, Streamlit  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, streamlit, scipy, pillow  

---

## References
- **Dataset:** [Online Shoppers Purchasing Intention Dataset](https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset)  
- **Deployment:** [Predict Purchase Intention](https://predict-purchase-intention.streamlit.app/)
