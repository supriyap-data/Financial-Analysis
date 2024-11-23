# CarPro Financial Analysis  

**Brief Overview:**  
This project analyzes the financial and credit risk aspects of a hypothetical car loan company, CarPro, to optimize its Annual Percentage Rate (APR) offerings for customer loans. The goal is to balance profitability with customer conversion rates by examining key metrics and running randomized experiments.

---

## Features  

- Analysis of CarPro’s pricing strategy and its effect on profitability.  
- Evaluation of customer conversion rates based on APR offerings.  
- Insights into vehicle and finance margins for better decision-making.  
- Recommendations to optimize APR strategy considering profitability and customer behavior.  
- Additional Exploratory Data Analysis (EDA) to support findings.

---

## Table of Contents  

1. Problem Statement  
2. Data Import and Cleansing  
3. Analysis and Solutions 
    - Pricing Analysis
    - Customer Conversion Rate  
    - Margin Analysis
    - Recommendations
    - Other Considerations 
4. Conclusion and Notes
5. Additional EDA  

---

## Problem Statement  

CarPro provides financing to customers to purchase vehicles. The APR offered affects both the profitability of loans and customer conversion rates. Randomized experiments are used to assess how different APRs impact these metrics.  

**Dataset Overview:**  
The dataset contains pseudo-realistic data with columns such as:  
- **app_id**: Application ID  
- **fico**: Applicant FICO score 
- **apr_test_group**: Indicates if the applicant is in the test group  
- **apr**: Offered APR  
- **converted to sale**: Indicates if the applicant purchased a car  
- **vehicle margin**: Profit from selling the vehicle  
- **finance margin**: Profit from the loan  

---

## Installation  

### Prerequisites  
- Python 3.8+  
- Pandas, NumPy, Matplotlib, Seaborn  

### Steps  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/username/carpro-financial-analysis.git  
   ```  
2. Navigate to the project directory:  
   ```bash  
   cd carpro-financial-analysis  
   ```  
3. Install the required libraries:  
   ```bash  
   pip install -r requirements.txt  
   ```  

---

## Usage  

Run the analysis notebook:  
```bash  
jupyter notebook financial_analysis.ipynb  
```  
Follow the structured analysis to explore pricing, conversion, margins, and recommendations.

---

## Results and Insights  

The project provides actionable insights into:  
1. Optimal APR strategies for maximizing profitability.  
2. Relationships between FICO scores, APRs, and conversion rates.  
3. Vehicle and finance margin trends.  

---

## Contributing  

Contributions are welcome! Fork the repository, create a feature branch, and submit a pull request.  

---

