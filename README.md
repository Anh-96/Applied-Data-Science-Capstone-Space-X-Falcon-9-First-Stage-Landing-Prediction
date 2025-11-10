# Applied-Data-Science-Capstone-Space-X-Falcon-9-First-Stage-Landing-Prediction

🛰️ SpaceX Falcon 9 Launch Analysis
Capstone Project – IBM Data Science Professional Certificate

Date: October 2025

📖 Overview

  This project explores SpaceX Falcon 9 launch data to analyze factors influencing launch success and booster reusability.
  By integrating SpaceX APIs, web scraping, and machine learning models, the project aims to identify operational trends and predict successful landings — supporting cost-effective space mission planning.
  

🎯 Objectives

  * Understand the patterns behind successful and failed Falcon 9 launches
  
  * Explore the relationship between payload mass, orbit type, and launch site
  
  * Build predictive models to classify landing outcomes
  
  * Create interactive visualizations and dashboards for analysis
  

🧩 Methodology
  1. Data Collection
  
    API Integration: Fetched structured launch data from the SpaceX REST API
    Web Scraping: Extracted historical Falcon 9 launch records from Wikipedia using BeautifulSoup.
    
    Data Validation: Checked for missing values, inconsistencies, and duplicates.
  
  2. Data Wrangling
  
    Filtered data by BoosterVersion
    
    Imputed missing values (e.g., PayloadMass mean substitution)
    
    Created landing outcome labels and standardized formats
  
  3. Exploratory Data Analysis (EDA)
    
    Visualized launch success by site, year, and orbit type
    
    Built interactive geographic maps using Folium
    
    Created dashboards using Plotly Dash
  
  4. Predictive Modeling
  
    Implemented Logistic Regression, SVM, KNN, and Decision Tree Classifier
    
    Evaluated models on test data with accuracy, confusion matrix, and precision metrics
    
    Best performer: Decision Tree (94.4% accuracy)
    

📊 Key Findings

  Launch success rates have grown steadily since 2013, surpassing 80% by 2020
  
  KSC LC-39A is the most reliable launch site with ~77% success rate
  
  Missions with payloads <5,000 kg and to ES-L1 / GEO / SSO orbits have higher landing success
  
  The Decision Tree model accurately predicts landing outcomes and supports mission risk assessment
  
  
🧠 Technologies Used
| Category             | Tools & Libraries                      |
| -------------------- | -------------------------------------- |
| **Programming**      | Python, Jupyter Notebook               |
| **Data Handling**    | Pandas, NumPy, Requests, BeautifulSoup |
| **Visualization**    | Matplotlib, Seaborn, Plotly, Folium    |
| **Machine Learning** | Scikit-learn                           |
| **Dashboarding**     | Plotly Dash                            |
| **Data Source**      | SpaceX REST API, Wikipedia             |


🚀 Results Summary

  Total Launch Sites: 4
  
  Overall Success Rate: >80%
  
  Best Launch Site: KSC LC-39A
  
  Max Payload: 15,600 kg
  
  Best Predictive Model: Decision Tree (94.4% accuracy)

💡 Conclusion

  This project demonstrates how data analytics and machine learning can transform aerospace data into actionable insights.
  By leveraging open data and Python tools, we can enhance mission planning, risk management, and booster reuse efficiency, contributing to the broader vision of affordable and sustainable space exploration.
  
🪐 Author
  📧 anhbnt96@gmail.com
