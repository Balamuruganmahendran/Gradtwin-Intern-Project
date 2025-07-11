# 📦 Amazon Sales Amount Predictor using MLP Regressor

A **Streamlit-based web application** that predicts the expected **sales amount** for Amazon orders using a **Multilayer Perceptron (MLP)** regression model. The model is trained on historical e-commerce transaction data and incorporates categorical and numerical features such as category, fulfillment method, shipping details, and currency.

---

## ✅ Key Features

- 🔍 User-driven input form for key product/shipping parameters  
- 🧠 Trained `MLPRegressor` neural network for continuous prediction  
- ⚙️ Feature encoding (Label + One-Hot) and scaling pipeline  
- 📈 Model training and automatic persistence (`joblib`)  
- 🌐 Streamlit UI for browser-based prediction  
- 🧼 Preprocessed dataset (`cleaned_amazon_sales.csv`) with outliers removed  

---

## 🧠 Tech Stack

- **Frontend**: Streamlit  
- **Backend/ML**: Python, scikit-learn  
- **Model**: MLPRegressor (Multilayer Perceptron)  
- **Encoding**: OneHotEncoder + LabelEncoder  
- **Scaling**: StandardScaler  
- **Persistence**: Joblib  

---

## 🚀 Getting Started

### 🔧 Installation

```bash
git clone https://github.com/your-username/amazon-mlp-sales-predictor.git
cd amazon-mlp-sales-predictor
pip install -r requirements.txt
```

### ▶️ Run the App

```bash
streamlit run mlp_sales_app.py
```

---

## 📂 Project Structure

```
mlp_sales_app.py           # Unified training + prediction Streamlit app
cleaned_amazon_sales.csv   # Preprocessed input dataset
mlp_model.pkl              # Saved MLPRegressor model
scaler.pkl                 # Saved StandardScaler
encoder.pkl                # Saved OneHotEncoder
requirements.txt           # Project dependencies
README.md                  # Project overview
```

---

## 📸 Output Screenshot

![Sales Predictor Output](<img width="1920" height="970" alt="output scr shot" src="https://github.com/user-attachments/assets/5f63524e-7803-4825-a906-2c720fca18e4" />)

> 📝 Replace `screenshot.png` with your actual image filename after uploading to your GitHub repository.

---

## 📊 Sample Use Case

> Predict the likely sales amount (₹) for a new Amazon product based on selected features:
>
> - Product category  
> - Fulfillment type  
> - Shipping location  
> - Sales channel  
> - Currency  

---

## 🤝 Contributing

Pull requests are welcome. For major changes, open an issue first to discuss what you'd like to change.

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 📬 Contact

**Authors**: [Balamurugan & Vijay Kumar]  
**GitHub**: [@Balamuruganmahendran](https://github.com/Balamuruganmahendran)
