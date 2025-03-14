# Dynamic Pricing Analysis: Feature Selection using EDA  

## Project Overview  
This project focuses on **Exploratory Data Analysis (EDA) for Feature Selection** to determine the most important factors influencing the **Historical Cost of Ride**. The dataset contains multiple features related to ride-sharing services, such as the number of riders, time of booking, and customer ratings. By applying **EDA techniques**, we aim to identify the most significant variables that impact ride pricing.  

---

## Dataset Overview  
The dataset consists of various features that may impact the cost of rides, such as:  

- **Number_of_Riders**: Total number of riders per ride.  
- **Number_of_Drivers**: Number of available drivers at the time of booking.  
- **Number_of_Past_Rides**: Historical data on the user's past rides.  
- **Average_Ratings**: Customer ratings for previous rides.  
- **Expected_Ride_Duration**: Estimated duration of the ride.  
- **Location_Category**: Categorical variable describing the location type (e.g., Urban, Suburban).  
- **Customer_Loyalty_Status**: Loyalty status of the customer.  
- **Time_of_Booking**: Categorical feature representing the time the ride was booked.  
- **Vehicle_Type**: Type of vehicle chosen for the ride (e.g., Economy, Premium).  
- **Historical_Cost_of_Ride**: The target variable representing the historical cost of the ride.  

---

## Key Objectives  
- Perform **Exploratory Data Analysis (EDA)** to understand dataset patterns.  
- Identify **correlations** and relationships between features.  
- Use **statistical and visualization techniques** to determine **feature importance**.  
- Prepare the data for potential **predictive modeling** by selecting the most relevant features.  

---

## Exploratory Data Analysis (EDA) Steps  
1. **Data Cleaning**: Handling missing values, duplicates, and inconsistencies.  
2. **Descriptive Statistics**: Summary statistics and data distribution analysis.  
3. **Data Visualization**: Using plots like histograms, box plots, and heatmaps to explore feature relationships.  
4. **Feature Correlation Analysis**: Identifying highly correlated variables using a correlation matrix.  
5. **Feature Importance Analysis**: Using statistical tests and feature selection techniques.  

---

## Tech Stack  
- **Python**  
- **Pandas**   
- **NumPy**   
- **Matplotlib & Seaborn** 
- **Scikit-learn** (for feature selection techniques)  

---

## Results & Insights  
- Found key features that have a **strong impact** on ride pricing.  
- Discovered correlations between **customer ratings, location category, and vehicle type** with the historical cost.  
- Identified outliers and trends in **customer behavior** affecting pricing.  
- Created a **cleaned and optimized dataset** for further predictive modeling.  

---

## 🏁 How to Run the Project  
1. Clone this repository:  
   ```bash
   git clone (https://github.com/ShalakaKharade/Dynamic_Pricing_Analysis)
   
2. Navigate to the project directory:
   cd dynamic-pricing-analysis

3. Install dependencies:
   pip install -r requirements.txt
   
4. Run the Jupyter Notebook or Python script for EDA.

   










