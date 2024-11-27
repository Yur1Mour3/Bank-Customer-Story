# Project - Bank Customer Churn Story ( Descriptive  analysis with Tableau)
I recently conducted a descriptive analysis using a fictional Kaggle dataset. This exercise allowed me to apply and consolidate my knowledge in data analysis, from the initial exploration to interpreting valuable insights. During the analysis, I used Tableau to visualize trends and patterns, as well as applied data cleaning and transformation techniques
## Formulas
#### Number of Customers
```dax
COUNT([Customer Id])
```
#### Number of Churned Customers
```dax
SUM([Exited])
```
#### Churn Rate
```dax
[2 Number of Churned Customers] / [1 Number of Customers].
```
## 1. Customer Information 
- Total customers: **10,000**
- Customers who closed their accounts: 2,038
- Average customer age: 39 years
- Churn rate: **20.38%**
## 2. Profile of Customers Who Left the Bank
- Age group with the highest churn: **45 to 60 years**
  ![Captura de Tela](https://media.licdn.com/dms/image/v2/D4D12AQGlcgY5oCDPWg/article-inline_image-shrink_1500_2232/article-inline_image-shrink_1500_2232/0/1726692851047?e=1737590400&v=beta&t=J1hvqyY8Y82SU9SVek3LWnKd6BrLZK7vI0w_97EkGx4)

## 3. Location of Customers Who Left the Bank
- Country with the highest churn: **Germany (32%)**
 ![Captura de Tela](https://media.licdn.com/dms/image/v2/D4D12AQHtO6rBKsaI5Q/article-inline_image-shrink_1500_2232/article-inline_image-shrink_1500_2232/0/1726693024322?e=1737590400&v=beta&t=b6CuQ70elVCQhBa1BP4B6YS3dJJiMgSVhQXcrE8gRG8)

## 4. Types of Cards and Banking Products
- The main type of card held by departing customers: **Diamond**
- The average number of banking products held by these customers: **3 to 4**

![Captura de Tela](https://media.licdn.com/dms/image/v2/D4D12AQGEDh62IoqU8g/article-inline_image-shrink_1000_1488/article-inline_image-shrink_1000_1488/0/1726693287163?e=1737590400&v=beta&t=S9uysFF45oDksPeUPAc3Ki_-DmpCdlXFRw8fTWMGzo0)
![image](https://github.com/user-attachments/assets/c3be62be-4c64-4c31-8870-1ebef8e6dd83)

## 5. Engagement with the Loyalty Program
- Average loyalty points accumulated: **150 points**
![Captura de Tela](https://media.licdn.com/dms/image/v2/D4D12AQHJql7Za0P_dA/article-inline_image-shrink_1500_2232/article-inline_image-shrink_1500_2232/0/1726693485983?e=1737590400&v=beta&t=KoLA-w12Qxaajg6qpoU8ZyYpRDO9Bz9QaxYoQqrNFr8)

## 6. Customer Service Issues
Percentage of inactive customers who reported complaints before leaving: **99.69%**


![Captura de Tela](https://media.licdn.com/dms/image/v2/D4D12AQE5-FtH1WRrJg/article-inline_image-shrink_1500_2232/article-inline_image-shrink_1500_2232/0/1726693685139?e=1737590400&v=beta&t=tJ6yEN_3Hep2BmQak1ysGrflqlKUd-F-h9J-mQUoUo8)

## Conclusion
The fictional Bank is facing a critical customer attrition issue, especially among older clients and those from the German market. These customers maintain diverse financial relationships and accumulate points in the loyalty program, but ineffective customer service, particularly regarding complaints, is causing them to lose trust and migrate to other institutions.
## Recommendations
- Prioritize effective and prompt handling of complaints, especially for long-standing and high-value clients.
- Identify and resolve specific issues affecting customer satisfaction in Germany.
- Develop more attractive incentives and benefits for long-term customers, especially those with diverse banking products.
- Focus on retention initiatives for clients with Diamond card, strengthening relationships and loyalty.
  
[Check out the dashboard at this link.](https://public.tableau.com/views/BankCustomerChurnStory_17087902764790/CustomerChurnStory?:language=pt-BR&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
