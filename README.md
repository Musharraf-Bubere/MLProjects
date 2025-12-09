# 🧠 End-to-End Machine Learning Project 🚀

A **production-ready machine learning project** built using Python that demonstrates the **complete ML lifecycle** — from data ingestion to live prediction using a **Flask web application**.

---

## 📌 Project Highlights

✅ Modular ML Pipeline Architecture  
✅ Data Ingestion, Transformation & Model Training  
✅ Multiple Regression Models Compared  
✅ Best Model Selection & Serialization  
✅ Custom Logging & Exception Handling  
✅ Flask Web App for Real-Time Predictions  
✅ Jupyter Notebook for EDA  
✅ Clean Industry-Level Project Structure  

---

## 🎯 Project Workflow

```text
Raw Data → Data Ingestion → Data Transformation → Model Training → Model Evaluation → Best Model Selection → Flask Deployment
```

---

## 🗂️ Project Structure

```bash
MLProjects/
│
├── app.py                  # 🌐 Flask application
├── requirements.txt        # 📦 Project dependencies
├── setup.py                # ⚙️ Package setup
├── README.md
│
├── notebook/               # 📊 EDA & Experiments
│
├── artifacts/              # 💾 Saved datasets & trained models
│
├── templates/              # 🖼️ HTML files
│   └── index.html
│
└── src/
    ├── components/
    │   ├── data_ingestion.py        # 📥 Data loading & splitting
    │   ├── data_transformation.py  # 🔄 Feature engineering
    │   └── model_trainer.py        # 🤖 Model training & evaluation
    │
    ├── pipeline/
    │   ├── train_pipeline.py       # 🏋️ Training pipeline
    │   └── predict_pipeline.py     # 🔮 Prediction pipeline
    │
    ├── logger.py                   # 📝 Logging setup
    ├── exception.py                # 🚨 Custom exception handler
    └── utils.py                    # 🛠️ Helper functions
```

---

## 🧰 Tech Stack Used

🔥 **Programming Language**
- Python  

📊 **Data & Machine Learning**
- NumPy  
- Pandas  
- Scikit-learn  
- XGBoost  
- CatBoost  

🌐 **Web Framework**
- Flask  

📒 **Other Tools**
- Logging  
- Pickle  
- Jupyter Notebook  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Musharraf-Bubere/MLProjects.git
cd MLProjects
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

### 3️⃣ Activate Virtual Environment

**Windows**
```bash
venv\Scripts\activate
```

**Mac/Linux**
```bash
source venv/bin/activate
```

### 4️⃣ Install Requirements

```bash
pip install -r requirements.txt
```

---

## 🏋️ Model Training

Run the following command to train the model:

```bash
python -m src.pipeline.train_pipeline
```

✅ This will:
- Load dataset  
- Split train & test data  
- Apply transformations  
- Train multiple ML models  
- Select the best performing model  
- Save model inside `artifacts/`  

---

## 🤖 Models Used

- ✅ Random Forest Regressor  
- ✅ Decision Tree Regressor  
- ✅ Gradient Boosting Regressor  
- ✅ Linear Regression  
- ✅ K Nearest Neighbors Regressor  
- ✅ XGBoost Regressor  
- ✅ CatBoost Regressor  
- ✅ AdaBoost Regressor  

---

## 🌐 Run Flask Web App

After successful training:

```bash
python app.py
```

Now open:

```
http://127.0.0.1:5000/
```

Enter feature values in the form and get **live ML predictions** ✅

---

## 📊 Model Evaluation

The project evaluates models using:

- ✅ R² Score  
- ✅ Mean Squared Error (MSE)  
- ✅ Root Mean Squared Error (RMSE)  

The **best model is automatically selected and saved**.

---

## 📝 Logging & Exception Handling

- 📂 All logs are stored inside the `logs/` folder  
- 🚨 CustomException provides advanced error tracking  
- ✅ Production-level debugging support  

---

## 🌟 Future Enhancements

🚀 Docker Integration  
☁️ Cloud Deployment (AWS / Render / Heroku)  
🧪 Adding Unit Testing  
📊 Model Explainability (SHAP / LIME)  
🔁 CI/CD with GitHub Actions  

---

## 👨‍💻 Author

**Musharraf Bubare**

🔗 GitHub: https://github.com/Musharraf-Bubere  
🔗 LinkedIn: https://www.linkedin.com/in/musharraf-bubere007 

---

⭐ If you like this project, don’t forget to **star the repository!**
