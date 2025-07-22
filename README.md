# Olist E-Commerce Sales Analysis

## Project Background
This project analyzes Olist’s Brazilian e-commerce dataset to uncover trends in customer behavior, sales, and logistics, aiming to generate insights for strategic decision-making.

---

## Executive Summary
This analysis provides a comprehensive overview of the e-commerce platform’s performance, focusing on operational efficiency, customer satisfaction, and sales distribution.
On average, orders take 12 days to be delivered, which suggests opportunities for improving logistics and delivery processes.
The average ticket size across all transactions is R$205, reflecting a consistent purchase behavior among customers.
São Paulo stands out as the most significant regional market, representing around 42% of total sales volume.
Customer satisfaction remains positive, with an average review score of 4.1 out of 5. The platform also shows steady growth in both order volume and revenue over time, particularly during seasonal peaks, signaling a solid foundation for further expansion and retention strategies.

---

## Insights

### Product Categories
- Most sales are concentrated in a few top-performing product categories, including bed_bath_table and health_beauty.
- Higher average order values are observed in categories such as furniture and computers, suggesting premium positioning or bundling strategies.

<img width="631" height="470" alt="image" src="https://github.com/user-attachments/assets/298c5d28-fbe1-4e77-a1c6-340c132df4ef" />
<img width="991" height="490" alt="image" src="https://github.com/user-attachments/assets/d01abfa8-5f59-4afd-b56b-0dcfb70b16a6" />


### Sales & Revenue Trends
- Sales are relatively consistent with peaks in specific months (around November/December, aligned with Black Friday and Holiday Sesason).
- Average Ticket for the time period was R$205.

<img width="1189" height="490" alt="image" src="https://github.com/user-attachments/assets/13205812-f7a3-4323-879a-38939b490d40" />


### Geographic Sales Distribution
- States such as São Paulo, Rio de Janeiro, and Minas Gerais dominate in sales volume.
- São Paulo specifically represents 42% of the total sales.
- However, average ticket size varies by region, revealing potential for targeted campaigns.

<img width="989" height="490" alt="image" src="https://github.com/user-attachments/assets/3c8a78d3-d97f-4bf6-ac67-9c1e5298af63" />
<img width="989" height="490" alt="image" src="https://github.com/user-attachments/assets/065e836c-431c-404a-815b-1cc5057ba1e1" />


### Delivery Performance
- A comparison of estimated vs actual delivery times reveals recurring delays.
- Most deliveries are completed within 12 days. However, a few long-tail cases significantly impact the average delivery experience.
- This lag is more pronounced in certain states, suggesting a need to optimize logistics or communicate better delivery expectations in those regions.

<img width="989" height="490" alt="image" src="https://github.com/user-attachments/assets/79c0f7e4-94b4-4a8b-9ec2-bdf611ff9307" />


### Review Scores
- Overall score was 4.1 stars, but there is a clear relationship between delivery time and review scores.
- Faster deliveries generally correlate with higher satisfaction, reinforcing the importance of fulfillment speed in the customer experience.

<img width="989" height="490" alt="image" src="https://github.com/user-attachments/assets/b19dedf1-b00d-4d15-9291-b2380ce96f11" />


### Suggested Next Steps:
- **Delivery Optimization:** Focus on improving delivery time in high-delay regions.
- **Customer Segmentation:** Further explore customer behaviors per region or category to tailor marketing strategies.
- **Product Mix Analysis:** Deep-dive into underperforming categories with high returns or low review scores to identify improvement opportunities.
- **Forecasting Models:** Use time-series models to predict revenue and delivery patterns around key periods like Black Friday or Christmas.

---

## Dataset & References
The dataset is publicly available at [Kaggle - Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

It contains anonymized e-commerce data from multiple marketplaces in Brazil, including:
- Customer orders and purchase timestamps  
- Product category and seller information  
- Shipping costs and delivery times  
- Review scores  
- Customer location by state and city 
