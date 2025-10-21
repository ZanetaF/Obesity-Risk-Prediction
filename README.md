# Obesity Risk Prediction and Deployment

![Python](https://skillicons.dev/icons?i=python) ![scikit-learn](https://skillicons.dev/icons?i=scikitlearn) ![fastapi](https://skillicons.dev/icons?i=fastapi) ![streamlit](https://skillicons.dev/icons?i=streamlit)

**Course:** Model Deployment
**Dataset:** ObesityDataSet  
**Year:** 2025



## About this repository
This repo demonstrates a complete workflow for obesity prediction:
- Data preprocessing and EDA
- Building and comparing two ML classifiers (Random Forest & XGBoost)
- Selecting and saving the best model with `pickle`
- Refactoring inference into a FastAPI backend
- Creating a Streamlit frontend that calls the backend for predictions


## ⚙️ Project Workflow

### Model Development and Comparison
This phase focuses on building and evaluating two machine learning algorithms:
- **Random Forest**
- **XGBoost**

**Steps:**
- Perform full preprocessing: encoding, normalization, and data splitting  
- Train both algorithms and compare results  
- Evaluate models using metrics such as accuracy, precision, recall, and F1-score  
- Save the best-performing model using `pickle`
- 
### Deployment (Inference / Prediction)
The trained model is deployed using:
- **FastAPI (Backend)** → exposes an endpoint `/predict` that accepts JSON input and returns prediction results  
- **Streamlit (Frontend)** → provides an interactive web form where users can input personal data and instantly view obesity prediction results  

## 🧠 Technologies Used
- Python
- Scikit-learn
- XGBoost
- Pandas & NumPy
- FastAPI (for backend deployment)
- Streamlit (for frontend UI)
- Pickle (for model serialization0

🔗 **Live Demo:** [Obesity Risk Prediction](https://zanetaobesitypredict.streamlit.app/)

