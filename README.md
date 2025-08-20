# Bike Rental Demand Prediction – Assignment 1

This project applies **machine learning techniques** to predict bike rental demand in Seoul, using the **SeoulBikeData** dataset. It was developed as part of *Using Machine Learning Tools (UMLT) – Assignment 1*.  

The notebook demonstrates end-to-end data analysis, feature engineering, visualisation, and model building using Python and common data science libraries.

---

## Project Overview
- **Goal**: Predict the hourly rental count of bikes based on weather, time, and seasonal data.  
- **Dataset**: [SeoulBikeData.csv](https://archive.ics.uci.edu/ml/datasets/Seoul+Bike+Sharing+Demand) (2017–2018 hourly records of bike rentals).  
- **Key Tasks**:
  1. Load and explore the dataset  
  2. Clean and preprocess features  
  3. Perform exploratory data analysis (EDA)  
  4. Apply machine learning algorithms for prediction  
  5. Evaluate and compare model performance  

---

## Features in Dataset
- **Date, Hour, Temperature, Humidity, Wind speed, Visibility, Dew point temperature, Solar radiation, Rainfall, Snowfall, Seasons, Holiday, Functioning Day**  
- **Target variable**: *Rented Bike Count*

---

## Tools & Libraries Used
- **Python ≥ 3.5**
- [pandas](https://pandas.pydata.org/) – data manipulation  
- [numpy](https://numpy.org/) – numerical operations  
- [matplotlib](https://matplotlib.org/) – data visualisation  
- [scikit-learn](https://scikit-learn.org/) – machine learning models and evaluation  

---

## Notebook Structure
1. **Loading and validating the dataset**  
2. **Data cleaning and transformation**  
   - Removing closed business days  
   - One-hot encoding categorical variables  
   - Creating weekday/weekend feature  
3. **Exploratory data analysis**  
   - Visualising distributions and correlations  
4. **Model development**  
   - Training and testing ML models  
   - Evaluating prediction accuracy  

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   cd <your-repo>

2. Install the dependencies:
```bash
pip install -r requirements.txt

3. Open the notebook:

jupyter notebook predicting-bike-rental-demand.ipynb


4. Run all cells to reproduce the workflow.
