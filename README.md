# churn_prediction_chaid

### 1. Overview of Customer Segments
![image](https://github.com/user-attachments/assets/d9a3e842-1eda-4a55-be7b-83845a557277)

- **Month-to-Month Customers**: 
  - Total: **1,997** (No: 1,457, Yes: 540)
  - This segment shows significant churn potential, with 27% of these customers leaving.

- **One-Year Customers**: 
  - Total: **397** (No: 360, Yes: 37)
  - A smaller segment with only **9.3%** showing churn.

- **Two-Year Customers**: 
  - Total: **486** (No: 471, Yes: 15)
  - This segment exhibits the lowest churn rate at **3.1%**.

### 2. Churn Analysis by Customer Type
#### Month-to-Month Segment
- **DSL Customers**: 
  - Total: **348** (No: 240, Yes: 108)
  - Churn rate: **31%** (108/348). The premium customer subgroup shows significant churn, primarily among non-premium customers.

- **Fiber Optic Customers**: 
  - Total: **619** (No: 266, Yes: 353)
  - Churn rate: **57%** (353/619). This indicates that fiber optic users have a high tendency to churn, particularly among premium customers who spend more than 2k.

#### One-Year Segment
- **DSL Customers**: 
  - Total: **397** (No: 360, Yes: 37)
  - Churn rate: **9.3%**. This is a relatively low churn rate, indicating better retention among one-year customers.

#### Two-Year Segment
- **Churn Behavior**: 
  - Only **15 customers** from this segment churn, resulting in a 3.1% rate. This suggests that customers who stay for two years have a strong likelihood of remaining long-term.

### 3. Premium vs. Non-Premium Customers
- **Premium Customers**: 
  - Higher churn is observed in both month-to-month and fiber optic segments, despite their increased spend (2k to 10k).
  - They tend to respond to payment options differently, with a notable preference for electronic checks.

- **Non-Premium Customers**: 
  - Show a significant tendency to churn across all segments, particularly under month-to-month plans.
  - Their payment method choices may be contributing factors to higher churn rates.

### 4. Payment Method Insights
- **Bank Transfer (Automatic)**:
  - Generally associated with lower churn across all segments. 
  - Premium customers using this method tend to show higher retention rates compared to those using credit cards or electronic checks.

- **Credit Card (Automatic)**:
  - Higher churn rates when used by premium customers, suggesting dissatisfaction or cost-related concerns.

- **Electronic Check**:
  - Notably favored among both premium and non-premium customers, with varying churn rates. Premium customers using this method exhibit a tendency towards higher churn.

### 5. Recommendations
- **Retention Strategies**:
  - Focus on retaining month-to-month and fiber optic customers through tailored offers and loyalty programs, particularly for premium customers.
  - Implement feedback mechanisms to understand dissatisfaction causes among premium users, especially regarding payment methods.
  
- **Marketing Approaches**:
  - Emphasize the advantages of long-term commitments (e.g., one-year or two-year plans) to attract month-to-month customers.
  - Highlight the benefits of electronic checks and bank transfers to premium customers to reduce churn.

### Conclusion
The decision tree analysis indicates that while premium customers contribute significantly to revenue, they also present notable churn challenges, particularly in month-to-month and fiber optic segments. Effective retention strategies focused on payment preferences and customer satisfaction can help mitigate churn and improve long-term customer loyalty.
