# Customer Churn Prediction in Telecom Using CHAID and LLMs for Insights

## Overview

In the intensely competitive telecom industry, customer churn, particularly among prepaid users, presents a significant hurdle. With yearly churn rates reaching 12% to 30%, keeping high-value customers is crucial for maintaining profitability, as bringing in new customers can be 5 to 10 times more expensive than retaining existing ones.

This project tackles churn prediction for a telecom provider. By analyzing customer-level data, we aim to identify customers at high risk of churning and reveal the factors most correlated with churn behavior. This project utilizes CHAID (Chi-squared Automatic Interaction Detector) for market segmentation and Google’s Gemini Flash LLM to generate in-depth, analyst-style insights.
![image](https://github.com/user-attachments/assets/f16bc31e-6839-403c-b71d-e1727e9a5638)

### Key Features
- **Predictive Modeling**: Build models to predict customer churn risk.
- **Segment Analysis**: Identify churn patterns across different customer segments.
- **Analytical Insights with LLMs**: Leverage Google Gemini Flash to provide detailed insights, helping business stakeholders develop targeted strategies.
  
## Understanding Customer Churn

Churn behavior differs between **postpaid** and **prepaid** customers:
- **Postpaid Customers**: Easily tracked when they decide to switch to another provider.
- **Prepaid Customers**: More difficult to track, as they may stop using services without notification. This makes churn prediction critical for prepaid models, which are more common in Indian and Southeast Asian markets.
![image](https://github.com/user-attachments/assets/d2afbc73-6fb2-411b-84f5-a0b567a7e69f)
"CHAID Tree Visualization done Using IBM's SPSS Software"


## Project Structure

This project leverages CHAID for customer segmentation and churn analysis. The following insights were generated using the model and further refined with insights from Google Gemini Flash:

### 1. Overview of Customer Segments
- **Month-to-Month Customers**: 
  - Total: **1,997** (No: 1,457, Yes: 540) 
  - Significant churn rate of **27%**, indicating higher risk.
- **One-Year Customers**: 
  - Total: **397** (No: 360, Yes: 37) 
  - Churn rate of **9.3%**, suggesting better retention than month-to-month plans.
- **Two-Year Customers**: 
  - Total: **486** (No: 471, Yes: 15) 
  - The lowest churn rate at **3.1%**, indicating high retention potential.

### 2. Churn Analysis by Customer Type
#### Month-to-Month Segment
- **DSL Customers**: Churn rate of **31%**, mainly affecting non-premium customers.
- **Fiber Optic Customers**: Churn rate of **57%**, higher among premium customers spending over 2k.

#### One-Year Segment
- **DSL Customers**: Churn rate of **9.3%**, showing good retention.

#### Two-Year Segment
- **Churn Behavior**: Only **3.1%** churned, indicating strong retention among long-term customers.

### 3. Premium vs. Non-Premium Customers
- **Premium Customers**: Higher churn in month-to-month and fiber optic segments, despite higher spending (2k to 10k).
- **Non-Premium Customers**: Higher churn tendency, especially in month-to-month plans, potentially influenced by payment method choices.

### 4. Payment Method Insights
- **Bank Transfer (Automatic)**: Associated with lower churn across segments.
- **Credit Card (Automatic)**: Higher churn rates among premium customers, potentially indicating cost-related dissatisfaction.
- **Electronic Check**: Popular among both premium and non-premium customers, though premium users show higher churn.

### 5. Recommendations
* **Focus on Month-to-month, Fiber optic, Electronic Check segment:**
    * Offer loyalty programs or incentives to encourage switching to longer contract terms.
    * Provide tailored promotions and offers to entice customers to switch to alternative payment methods.
    * Implement targeted marketing campaigns highlighting the benefits of alternative internet services or bundles.
* **Promote automatic payment methods:**
    * Offer discounts or rewards for automatic payments.
    * Provide clear communication about the benefits of automatic payment methods.
* **Enhance customer service:**
    * Improve the customer experience with Electronic check payments to address potential issues.
    * Implement proactive customer service interventions for high-risk segments. 
* **Target customers with No Internet:**
    * Offer competitive packages to attract these customers to internet services. 
* **Leverage contract commitment:**
    * Implement strategies to encourage longer contract commitments. 
    * Highlight the benefits of long-term contracts through targeted promotions.

## Conclusion
The insights from CHAID analysis and LLM-based interpretation reveal key factors in churn behavior, highlighting areas to focus on for retaining high-value customers and improving loyalty. With effective, targeted strategies based on these insights, telecom companies can better mitigate churn and foster long-term customer relationships.

## Getting Started

### Prerequisites
- Python 3.x
- Necessary libraries: `pandas`, `scikit-learn`, `CHAID`, `Google Gemini API`, `matplotlib` , spss


### Usage
1. **Data Preprocessing**: Load and preprocess telecom customer data.
2. **Model Training**: Run the CHAID-based churn prediction model.
3. **Generate Insights**: Use Google Gemini Flash to generate analyst-style insights.


