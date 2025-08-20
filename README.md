# Retail Sales Forecasting with Prophet

A comprehensive time series forecasting project using the Prophet algorithm to predict weekly retail sales, incorporating external economic and environmental factors for enhanced accuracy.

## Project Overview

This project tackles a critical business challenge in retail: **sales forecasting**. Using historical sales data from 45 Walmart stores spanning 2010-2012, I built a machine learning model that predicts future sales while accounting for seasonal patterns, holidays, and external economic factors.

**Key Achievement**: Developed a forecasting model with **4.76% MAPE** (Mean Absolute Percentage Error), exceeding industry accuracy standards for retail forecasting.

## Dataset

- **Source**: Walmart Store Sales Data
- **Size**: 6,435 records across 45 stores
- **Time Period**: 2010-2012 (143 weeks)
- **Features**: 
  - Weekly sales figures
  - Store identifiers
  - Date information
  - Holiday flags
  - Economic indicators (unemployment rate, CPI, fuel prices)
  - Environmental data (temperature)

## Technology Stack

- **Python**
- **Prophet** - Facebook's time series forecasting tool
- **Pandas** - Data manipulation and analysis
- **Matplotlib/Seaborn** - Data visualization
- **Scikit-learn** - Model evaluation metrics
- **NumPy** - Numerical computing

## Key Features

### Advanced Forecasting Capabilities
- **Seasonal Decomposition**: Automatically detects and models yearly seasonality
- **Holiday Effects**: Incorporates special events that impact sales patterns  
- **External Regressors**: Leverages economic indicators for improved accuracy
- **Uncertainty Quantification**: Provides confidence intervals for risk assessment

### Model Performance
- **MAPE**: 4.76% (Excellent - industry benchmark is <5%)
- **Trend Capture**: Successfully models both seasonal spikes and baseline trends
- **Holiday Accuracy**: Precisely predicts 35-40% sales increases during peak seasons

## 📈 Results & Insights

### Business Impact
- **52-Week Forecast**: Generated comprehensive sales projections for strategic planning
- **Seasonal Intelligence**: Identified optimal inventory and staffing periods
- **Economic Sensitivity**: Quantified impact of external factors on sales performance
- **Risk Assessment**: Provided confidence intervals for scenario planning

### Key Findings
1. **Strong Seasonality**: Holiday periods drive 35-40% sales increases
2. **Economic Correlation**: Sales respond significantly to unemployment and fuel prices
3. **Trend Analysis**: Baseline sales show gradual decline requiring strategic intervention
4. **Forecasting Accuracy**: Model consistently outperforms simple seasonal baselines


## Sample Output

### Forecast Visualization
The model generates comprehensive forecasts with:
- Historical trend analysis
- Seasonal component decomposition  
- Future predictions with confidence intervals
- Economic factor impact assessment

### Performance Metrics
```
Model Performance Metrics:
- Mean Absolute Error: $75,248
- Root Mean Square Error: $105,294  
- Mean Absolute Percentage Error: 4.76%
```

## Business Applications

### Immediate Use Cases
- **Inventory Planning**: Optimize stock levels based on predicted demand
- **Financial Planning**: Accurate revenue projections for budgeting
- **Marketing Strategy**: Time promotional campaigns with seasonal trends

### Strategic Value
- **Investment Decisions**: Data-driven insights for store expansion
- **Risk Management**: Scenario planning with confidence intervals
- **Performance Monitoring**: Benchmark actual vs predicted performance

## Potential Enhancements

-  **Multi-store Scaling**: Extend analysis to all 45 stores
-  **Dynamic Economic Inputs**: Integrate live economic data feeds
-  **Real-time Updates**: Implement automated model retraining
-  **Regional Clustering**: Group stores by demographic similarities


## Learning Outcomes

This project demonstrates proficiency in:

**Technical Skills:**
- Time series analysis and forecasting
- Machine learning model development and evaluation
- Statistical analysis and interpretation
- Data visualization and storytelling

**Business Skills:**
- Retail analytics
- Strategic thinking and recommendation development
- Performance metrics and KPI analysis
