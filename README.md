# Hotel Reservation Cancellation Prediction

## Project Conclusion
In this project, I developed a machine learning model that predicts the probability of a hotel reservation being canceled. By accurately estimating cancellation risk at the time of booking, this model enables hotel leadership and revenue management teams to make more informed decisions around inventory control, pricing strategy, and operational planning. 

## Project Overview
Hotel reservation cancellations negatively impact both revenue and operational planning, particularly when cancellations occur close to arrival.  
This project develops a machine learning model to **predict the probability that a hotel reservation will cancel**, allowing revenue management teams to make data-driven overselling and pricing decisions.

## Business Problem
Hotels often rely on historical averages to estimate cancellations, which can lead to:
- Under-selling rooms and lost revenue
- Over-selling rooms and operational disruptions

**Goal:**  
Predict cancellation risk at the reservation level so hotels can:
- Improve cancellation forecasts
- Optimize overselling strategies
- Increase revenue while managing risk

---

## Notebooks and code
- [Data Wrangling](https://github.com/histopix175/Springboard-Capstone-Project-2/blob/main/Notebooks/CH-Capstone2-DataWrangling.ipynb)
- [Preprocessing](https://github.com/histopix175/Springboard-Capstone-Project-2/blob/main/Notebooks/CH-Capstone2-Preprocessing.ipynb)
- [Exploratory Data Analysis](https://github.com/histopix175/Springboard-Capstone-Project-2/blob/main/Notebooks/CH-Capstone2-EDA.ipynb)
- [Modeling](https://github.com/histopix175/Springboard-Capstone-Project-2/blob/main/Notebooks/CH%20Capstone2%20Modeling.ipynb)

## Data Sources
- **Hotel Booking Demand Dataset (Kaggle)**  
  https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand
- **Open-Meteo Weather API**  
  https://open-meteo.com/

The final dataset contains booking, customer, pricing, and weather forecast information.

---

## Project Structure
Springboard-Capstone-Project-2/
├── Data/
│ ├── raw/
│ └── processed/
├── Notebooks/
│ ├── 01_Data_Wrangling.ipynb
│ ├── 02_EDA.ipynb
│ ├── 03_Preprocessing.ipynb
│ └── 04_Modeling.ipynb
├── figures/
├── Model_Metrics.csv
└── README.md

## Key Recommendation
Apply the trained Random Forest model to **new incoming reservations** to generate a **cancellation probability**.

This probability can be used to:
- Improve daily cancellation forecasts
- Support dynamic overselling strategies
- Increase total rooms sold while minimizing risk

---

## Future Enhancements
- Oversell recommendation model using predicted cancellation probabilities
- Dynamic cancellation policy assignment based on risk
- Model retraining with real-time booking behavior

---

## Author
Cameron Hicks  
Springboard Data Science Capstone Project
