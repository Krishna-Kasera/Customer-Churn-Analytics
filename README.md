# End to End Customer Churn Analysis & Prediction 🔄
This project focuses on analyzing and predicting customer churn patterns using machine learning technique. By using the Light Gradient Boosting Machine (LGBM) classifier, identifying potential churners and providing actionable insights to improve customer retention. The project includes an interactive dashboard for real-time monitoring and analysis of churn patterns. 📈

## Project Highlights 🔦
- 📊 Performed comprehensive Exploratory Data Analysis (EDA) revealing a 27% customer churn rate
- 🧹 Implemented thorough data cleaning and preprocessing techniques
- 🤖 Developed a machine learning model achieving 81% accuracy in churn prediction
- 📈 Enhanced model performance through hyperparameter tuning, improving recall by 10%
- 💡 Generated actionable insights based on feature importance analysis
- 🎯 Created a system to identify high-risk customers among new joiners
- 📱 Built an interactive dashboard for churn analysis and monitoring
- 📑 Developed comprehensive reports for insights and recommendations

## Repository Structure 📂
```
📁 Customer-Churn-Analysis/
├─ 📄 README.md
├─ 📄 requirements.txt
├─ 📁 Notebook/
│  └─ 📄 Churn_Analysis.ipynb        # Jupyter notebook with analysis and model training process
├─ 📁 Datasets/
│  ├─ 📄 Customer_Data.csv           # Original dataset
│  └─ 📄 Predicted_Data.csv          # New joiners predictions
├─ 📁 Model/
│  └─ 📄 Churn_Classifier.joblib     # Saved LGBM model
├─ 📁 Analysis/
│  ├─ 📄 Churn_Analysis_Report.md    # Detailed analysis findings and recomendations
├─ 📁 Dashboard/
│  ├─ 📄 Churn_Dashboard.pbix        # Power BI dashboard file
│  └─ 📄 measures.txt                # DAX measures for dashboard
```

## Interactive Dashboard Features 📲
1. **Overview Page**
   - Real-time churn rate monitoring
   - Key performance indicators (KPIs)
   - Demographic breakdown of churned customers
   - Trend analysis over time

2. **Prediction Analysis**
   - High-risk customer identification
   - Churn probability distribution
   - Risk factors analysis
   - Geographic heat maps

3. **Deep Dive Analysis**
   - Contract type analysis
   - Revenue impact assessment
   - Service usage patterns
   - Customer satisfaction metrics

## Key Findings 🔍
- 🔴 Main churn reasons: competitor offerings and customer dissatisfaction
- 👥 Demographic patterns show higher churn rates among specific customer segments
- 📝 Contract type significantly impacts churn: month-to-month contracts show 47% churn vs 3% for two-year contracts
- 💰 Price sensitivity observed: higher-paying customers (₹50-100) show 33% churn vs 12% for lower-paying customers
- 📍 Geographic clustering of churn in specific regions
- 📈 Service quality correlation with churn probability

## Usage 🖥️
1. 🔗 **Clone Repository**: Clone this repository to your local system.
2. 📦 **Install Dependencies**: Install required Python libraries using:
   ```bash
   pip install -r requirements.txt
   ```
3. 📊 **Data Preparation**: Make sure that dataset files are present in relevant folders.
4. 🤖 **Run Prediction**: Use the saved model to predict churn probability for new customers.
5. 📈 **Analyze Results**: Review the comprehensive analysis in churn-analysis-report.md.
6. 📱 **Dashboard Setup**: 
   - Open churn_dashboard.pbix in Power BI Desktop
   - Refresh data connections if needed
7. 📊 [**Live Dashboard Link**](https://app.powerbi.com/groups/me/reports/9ddf2ca2-9492-4fb2-a217-95fb42c23e97/965f3cd2621b7c1b3105?experience=power-bi)

## Model Performance 📊
- **Accuracy**: 81%
- **Recall**: 75% (after tuning)
- **Key Features**: Contract type, payment amount, and service usage patterns

## Reports and Documentation 📑
1. **Analysis Report**
   - Detailed examination of churn patterns
   - Customer behavior analysis
   - Risk factor identification
   - Trend analysis and forecasting
   - Strategic initiatives for retention
   - Action plans by customer segment
   - Service improvement suggestions
   - Implementation roadmap

## Recommendations 💭
1. 🎯 Develop targeted retention strategies for month-to-month customers
2. 🌟 Implement service quality improvements based on customer feedback
3. 📍 Address regional service disparities in identified high-churn areas
4. 💰 Review pricing strategy for high-paying customer segments
5. 🤝 Enhance customer service training and support systems

## Contact ✉️
For questions or feedback about this project, please reach out through GitHub issues or discuss in the repository's Discussions section or mail me at kkasera025@gmail.com.

