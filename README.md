
# Predicting Flight Delays Using Weather and Airline Data

## **1. Project Overview**
In this project I aim to analyze factors contributing to flight delays and build a predictive model to forecast whether a flight will be delayed based on weather conditions and airline data. The study will leverage publicly available flight and weather datasets to uncover patterns affecting flight punctuality.

## **2. Motivation**
Flight delays cause significant inconvenience to passengers and financial losses to airlines. Due to my parents' work, I've been travelling a lot my whole life and have exprerienced many delays. So, I want to understand the key factors that lead to delays can help airlines optimize schedules, improve customer experience, and enhance operational efficiency. By applying data science techniques, I aim to develop a reliable model for predicting flight delays.

## **3. Data Sources**
- **Primary Data**: Publicly available flight data from sources such as:
  - FAA (Federal Aviation Administration) flight performance data
  - Bureau of Transportation Statistics (BTS) on airline on-time performance
  - OpenSky Network for real-time flight tracking
- **Enrichment Data**: Weather and airport-related data such as:
  - OpenWeatherMap API (historical and real-time weather data)
  - NOAA (National Oceanic and Atmospheric Administration) weather reports
  - Airport congestion data

## **4. Methodology**
The project will follow the data science pipeline:
1. **Data Collection**: Acquire historical flight and weather datasets.
2. **Data Cleaning & Preprocessing**:
   - Handle missing values
   - Normalize numerical features
   - Merge flight data with weather data
3. **Exploratory Data Analysis (EDA)**:
   - Visualizing trends in flight delays across different airports and times
   - Understanding correlations between weather conditions and delays
4. **Hypothesis Testing**:
   - Assessing statistical significance of factors contributing to flight delays
5. **Machine Learning Model Development**:
   - Classification models (Logistic Regression, Random Forest, Gradient Boosting)
   - Model evaluation using accuracy, precision, recall, and F1-score
6. **Presentation of Results**:
   - Visualizations (matplotlib, seaborn, Plotly)
   - Summary report on findings and recommendations

## **5. Expected Deliverables**
- A well-documented **GitHub repository** with:
  - Python code for data analysis and modeling
  - `requirements.txt` listing dependencies
  - Jupyter notebooks for EDA and ML models
- A final report or interactive dashboard to present findings

## **6. Limitations**
- **Data Availability:**
   Real-time flight delay data may not be publicly accessible for all airlines.

- **Weather Impact Complexity:**
   Weather conditions may interact with multiple other factors affecting delays, making causation difficult to determine.

- **Airport-Specific Variables:**
   Different airports may have unique operational factors affecting delays that are not captured in the dataset.

- **Model Accuracy:**
   Machine learning models may not fully capture unpredictable events such as sudden technical issues or emergencies.




## **7. Tools & Technologies**
- **Programming Language**: Python
- **Libraries**: pandas, numpy, scikit-learn, matplotlib, seaborn, XGBoost
- **Version Control**: GitHub for tracking progress

## **8. Academic Integrity**
All sources will be properly cited. Any use of AI tools will be explicitly documented.

---
### **Next Steps**
1. Set up the GitHub repository and commit this README.md.
2. Identify the best data sources and begin data collection.
3. Perform initial exploratory data analysis (EDA).
4. Keep track of updates and commit regularly to GitHub.


