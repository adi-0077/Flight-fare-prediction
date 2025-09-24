# Flight Fare Prediction ✈️💰  

## 📌 Overview  
This project focuses on predicting airline ticket prices using **machine learning regression models**. By analyzing features such as airline, source, destination, departure/arrival times, stops, and duration, the model provides accurate fare predictions. This can help airlines with pricing strategies and assist travelers in estimating costs.  

---

## 📊 Dataset  
- **Features:** Airline, Date of Journey, Source, Destination, Route, Departure & Arrival times, Duration, Total Stops, Additional Info.  
- **Target:** Ticket Price.  
- Dataset includes thousands of domestic flight records, cleaned and preprocessed for modeling.  

---

## ⚙️ Approach  
1. **Data Preprocessing:**  
   - Handled missing values.  
   - Converted categorical data (Airline, Source, Destination) using encoding techniques.  
   - Extracted time-based features (Day, Month, Hour).  
   - Transformed duration and stops into numerical values.  

2. **Exploratory Data Analysis (EDA):**  
   - Price distribution by airlines and routes.  
   - Relationship between stops/duration and price.  
   - Feature correlations visualized using heatmaps.  

3. **Model Building:**  
   - Linear Regression  
   - Random Forest Regressor  
   - Gradient Boosting Regressor  
   - Hyperparameter tuning with GridSearchCV  

4. **Evaluation Metrics:**  
   - Root Mean Squared Error (RMSE)  
   - R² Score  

---

## 🏆 Results  
- **Best Model:** Random Forest Regressor  
- **Performance:**  
  - R² Score (Test): ~0.87  
  - RMSE: ~2000 INR (approx.)  
- **Insights:**  
  - Airline type and number of stops are the most significant predictors.  
  - Non-stop flights are priced significantly higher than flights with layovers.  

---

## 🛠️ Technologies Used  
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 📂 Repository Structure  
