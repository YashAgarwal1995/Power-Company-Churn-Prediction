
# Random-Forest-Churn-Prediction 

A power company wants to know if price sensitivity is making customer churn. The projects aims to build a classification model that predicts if a customer will churn or not. 

![customer_churn](https://github.com/user-attachments/assets/38cab977-ae87-4b24-b5da-d4e50ba7efe5)
## Project Overview

PowerCo, a leading gas and electricity utility, is facing challenges with customer retention as consumers are increasingly opting for better deals from competitors. This project leverages customer consumption and historical price data to predict churn using a Random Forest Classifier.

The objective is to determine if price sensitivity significantly contributes to customer churn. The dataset includes detailed consumption and price information for each customer, with approximately 10% of consumers classified as churners. 


## Dataset

| Feature Name                 | Description                                                             | Data Type       |
|------------------------------|-------------------------------------------------------------------------|-----------------|
| `id`                         | Client company identifier                                              | object  |
| `activity_new`               | Category of the company’s activity                                     | object          |
| `channel_sales`              | Code of the sales channel                                              | object          |
| `cons_12m`                   | Electricity consumption of the past 12 months                         | Integer           |
| `cons_gas_12m`               | Gas consumption of the past 12 months                                 | Integer           |
| `cons_last_month`            | Electricity consumption of the last month                             | Integer           |
| `date_activ`                 | Date of activation of the contract                                    | object            |
| `date_end`                   | Registered date of the end of the contract                            | object            |
| `date_modif_prod`            | Date of the last modification of the product                          | object            |
| `date_renewal`               | Date of the next contract renewal                                     | object            |
| `forecast_cons_12m`          | Forecasted electricity consumption for the next 12 months             | Float           |
| `forecast_cons_year`         | Forecasted electricity consumption for the next calendar year         | Float           |
| `forecast_discount_energy`   | Forecasted value of current discount                                  | Float           |
| `forecast_meter_rent_12m`    | Forecasted bill of meter rental for the next 2 months                 | Float           |
| `forecast_price_energy_off_peak` | Forecasted energy price for 1st period (off peak)                 | Float           |
| `forecast_price_energy_peak` | Forecasted energy price for 2nd period (peak)                        | Float           |
| `forecast_price_pow_off_peak`| Forecasted power price for 1st period (off peak)                      | Float           |
| `has_gas`                    | Indicates if the client is also a gas client                          | Boolean         |
| `imp_cons`                   | Current paid consumption                                               | Float           |
| `margin_gross_pow_ele`       | Gross margin on power subscription                                    | Float           |
| `margin_net_pow_ele`         | Net margin on power subscription                                      | Float           |
| `nb_prod_act`                | Number of active products and services                               | Integer         |
| `net_margin`                 | Total net margin                                                      | Float           |
| `num_years_antig`            | Antiquity of the client (in number of years)                         | Integer         |
| `origin_up`                  | Code of the electricity campaign the customer first subscribed to     | String          |
| `pow_max`                    | Subscribed power                                                      | Float           |
| `churn`                      | Has the client churned over the next 3 months                        | Boolean         |

## Project Steps

*  Develop the hypothesis and frame the objective.
* Descriptive statistics and data visualization to gain a holistic understanding of data.
* Feature Engineering to create new columns that will help predict churn.
* Correlation analysis to reduce multicollinearity.
* Model Training and Evaluation. 
* Feature Importance
* Answering our hypothesis and analystical questions.
* Conclusion and executive summary. 
## Model Performance : Confusion Matrix:

![alt text](https://github.com/user-attachments/assets/ad1753f2-9f11-4205-89c7-9662d82e86e0)




## Conclusion

* So overall, we're able to very accurately identify clients that do not churn, but we are not able to predict cases where clients do churn! What we are seeing is that a high % of clients are being identified as not churning when they should be identified as churning.  
> Is churn driven by the customers' price sensitivity?

Based on the output of the feature importances, it is not a main driver but it is a weak contributor. However, to arrive at a conclusive result, more experimentation is needed. 

## Connect with Me :handshake:

<a href="https://www.linkedin.com/in/yash-agarwal-806222127/">
  <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="Yash Agarwal | LinkedIn"/>
</a>


Feel free to star ⭐ this repository if you find it helpful!