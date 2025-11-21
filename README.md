# Car Price Prediction

Auto Scout data which using for this project, scraped from the on-line car trading company (https://www.autoscout24.com) in 2019, contains many features of 9 different car models ('Audi A1', 'Audi A3' , 'Opel Astra', 'Opel Corsa', 'Opel Insignia', 'Renault Clio', 'Renault Duster', 'Renault Espace')

* This data has been passed through various data processing stages and has been made ready to be given to machine learning algorithms by making features engine.
* Various ML Algorithms (Logistic Regression, XGB, LightGBM etc.) were tried and fine tuned and the best result was obtained from the Random Forest algorithm.
* In accordance with the principle of 'Simplicity is at the core of a sophisticated product', modeling was done by selecting age, hp_kW, km, Gearing_Type, make_model features to reduce model complexity and increase performance.
* It has been turned into an app that will estimate car prices using Streamlit.
