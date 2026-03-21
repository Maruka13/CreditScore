# 🏦 Credit Score Prediction | Machine Learning Project

<p align="center">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange?style=for-the-badge" />
</p>

---

## 📌 About the Project

This project was developed as a **Credit Risk Analysis solution** for a banking scenario.

The objective is to build a **Machine Learning model** capable of automatically predicting a customer's credit score based on their financial and behavioral data.

The model classifies clients into three categories:

- 🟢 **Good** → Low credit risk  
- 🟡 **Standard** → Medium credit risk  
- 🔴 **Poor** → High credit risk  

---

## 🎯 Business Problem

Banks need to evaluate thousands of clients efficiently. Manual analysis is:

- ❌ Slow  
- ❌ Error-prone  
- ❌ Not scalable  

This project solves the problem by:

✔ Automating credit score classification  
✔ Reducing risk in lending decisions  
✔ Improving scalability using AI  

---

## 🧠 Machine Learning Approach

The project follows a complete ML pipeline:

### 1. Data Collection
- Dataset with **100,000 client records**
- 25 features including financial data, credit behavior, and loan history

### 2. Data Preprocessing

- Conversion of categorical variables using **Label Encoding**:
  - `profissao`
  - `mix_credito`
  - `comportamento_pagamento`

- Removal of irrelevant columns:
  - `id_cliente`

---

## 📊 Features Used

- `idade`
- `salario_anual`
- `num_contas`
- `num_cartoes`
- `juros_emprestimo`
- `dias_atraso`
- `divida_total`
- `taxa_uso_credito`
- `comportamento_pagamento`
- `saldo_final_mes`

---

## ⚙️ Model Training

### Models tested:

- 🌳 Random Forest Classifier  
- 📍 K-Nearest Neighbors (KNN)  

### Train/Test Split:

- 70% Training  
- 30% Testing  

---

## 📈 Model Performance

| Model            | Accuracy |
|------------------|--------|
| Random Forest 🌳 | **82.28%** |
| KNN 📍           | 73.68% |

✅ Selected Model: Random Forest

---

## 🔮 Predictions

The trained model is capable of predicting the credit score of new clients.

Example output:

| Cliente | Previsão |
|--------|--------|
| 1      | Poor   |
| 2      | Poor   |
| 3      | Standard |

---

## 🧪 How to Run the Project

### 1. Clone the repository

`git clone https://github.com/Maruka13/CreditScore.git`  
`cd CreditScore`

### 2. Install dependencies

`pip install pandas scikit-learn`

### 3. Run the notebook

`jupyter notebook inicial.ipynb`

---

## 📦 Technologies Used

- Python  
- Pandas  
- Scikit-learn  
- Jupyter Notebook  

---

## 📌 Project Structure

```
CreditScore/
│
├── inicial.ipynb
├── clientes.csv
├── novos_clientes.csv
└── README.md
```

---

## 🚀 Possible Improvements

- Hyperparameter tuning (GridSearchCV)  
- Feature engineering  
- Handling class imbalance  
- More evaluation metrics (Precision, Recall, F1-score)  
- API deployment (Flask / FastAPI)  
- Cloud deployment (AWS / Azure)  

---

## 💡 Key Learnings

- End-to-end Machine Learning pipeline  
- Data preprocessing and encoding  
- Model comparison and evaluation  
- Real-world business problem solving  

---

## 👩‍💻 Author

Developed by **Emanuelle Gomes**  
Aspiring Software Engineer | Machine Learning Enthusiast  

---

## 📜 License

This project is for educational purposes and portfolio demonstration.
