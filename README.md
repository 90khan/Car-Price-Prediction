# 🚗 Car Price Prediction

This project predicts car prices using data scraped from [AutoScout24](https://www.autoscout24.com) in 2019.  
The dataset contains multiple features of 9 different car models:

* Audi A1  
* Audi A3  
* Opel Astra  
* Opel Corsa  
* Opel Insignia  
* Renault Clio  
* Renault Duster  
* Renault Espace  

---

## 🧹 Data Processing

The raw data has been cleaned and processed to be ready for machine learning algorithms. Feature engineering was applied to create informative features for the models.

---

## 🤖 Modeling

Several machine learning algorithms were tried and fine-tuned, including:  

* Logistic Regression  
* XGBoost (XGB)  
* LightGBM  

The best performance was achieved using **Random Forest**.  

To reduce model complexity and improve performance, only the following features were selected:

* `age`  
* `hp_kW`  
* `km`  
* `Gearing_Type`  
* `make_model`  

> Principle: *"Simplicity is at the core of a sophisticated product."*

---

## 🖥️ App

The model has been deployed as a **Streamlit** app, allowing users to estimate car prices interactively.  

---

## 📚 Quick Start (Local)

1. Create a virtual environment:
```bash
python3 -m venv venv
source venv/bin/activate
````

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the app:

```bash
streamlit run app.py
```

Open your browser at [http://localhost:8501](http://localhost:8501)

---

## ⚙️ Tech Stack

* Python 3.8+
* pandas / numpy
* scikit-learn
* XGBoost / LightGBM
* Streamlit

---

## 🤝 Contributing

Contributions are welcome!
Please open an issue or submit a pull request for improvements or bug fixes.

---

## 📜 License

This project is licensed under the **MIT License**.
See the [LICENSE](./LICENSE) file for details.
