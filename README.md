# Sky-High Satisfaction: Exploring Factors that Influence Passenger Experience

## Introduction

In today’s interconnected world, air travel plays a critical role in global communications and connectivity. Improvements in technology have made flight essential for both business and personal travel. Service quality significantly impacts passenger satisfaction, influencing customer loyalty and airline profitability [1].

Assessing passenger satisfaction requires analyzing multiple attributes rather than relying on a single factor. Traditional models such as SERVQUAL evaluate aspects like reliability and responsiveness [4], but challenges like data biases and sampling issues complicate the process [5]. 

In this project, we aim to leverage structured airline survey data to build machine learning models capable of predicting customer satisfaction. Our goal is to help airlines identify key service quality metrics they can improve to enhance customer experience and retention.

## Dataset

We use the **Airline Passenger Satisfaction Survey Dataset** from Kaggle [6], containing feedback from over 120,000 passengers. The dataset includes demographic information, travel details, service quality ratings, and customer satisfaction labels ("Satisfied" or "Neutral/Unsatisfied").

**Key Features:**

| Column Name                          | Description |
|:-------------------------------------|:------------|
| ID                                   | Unique passenger identifier |
| Gender                               | Gender of the passenger (Female/Male) |
| Age                                  | Age of the passenger |
| Customer Type                        | First-time or returning airline customer |
| Type of Travel                       | Purpose of flight (Business/Personal) |
| Class                                | Travel class (Economy, Business, etc.) |
| Flight Distance                      | Distance of the flight in miles |
| Departure Delay                      | Delay at departure (minutes) |
| Arrival Delay                        | Delay at arrival (minutes) |
| Departure and Arrival Time Convenience | Satisfaction with departure/arrival time (1-5) |
| Ease of Online Booking               | Satisfaction with online booking process (1-5) |
| Check-in Service                     | Satisfaction with check-in service (1-5) |
| Online Boarding                      | Satisfaction with online boarding (1-5) |
| Gate Location                        | Satisfaction with gate location (1-5) |
| On-board Service                     | Satisfaction with onboard service (1-5) |
| Seat Comfort                         | Satisfaction with seat comfort (1-5) |
| Leg Room Service                     | Satisfaction with leg room (1-5) |
| Cleanliness                          | Satisfaction with cleanliness (1-5) |
| Food and Drink                       | Satisfaction with food and drinks (1-5) |
| In-flight Service                    | Satisfaction with in-flight service (1-5) |
| In-flight Wifi Service               | Satisfaction with in-flight WiFi (1-5) |
| In-flight Entertainment              | Satisfaction with in-flight entertainment (1-5) |
| Baggage Handling                     | Satisfaction with baggage handling (1-5) |
| Satisfaction                         | Overall satisfaction (Satisfied/Neutral or Unsatisfied) |

## Objective

The objective of this project is to identify the best predictive model for determining passenger satisfaction based on survey data. We will combine traditional statistical methods (correlation analysis, hypothesis testing, ANOVA) with machine learning techniques to:

- Pinpoint key drivers of satisfaction.
- Rank factors influencing the customer experience.
- Develop accurate predictive models for airline customer satisfaction.

Ultimately, the goal is to provide actionable insights for airlines to enhance service quality, customer loyalty, and competitiveness.

## Methodology

The project methodology includes:

1. **Data Wrangling**  
   - Cleaning the dataset (handling missing values, duplicates, and inconsistencies).

2. **Exploratory Data Analysis (EDA)**  
   - Identifying patterns, relationships, and variable distributions.

3. **Statistical Testing**  
   - Hypothesis testing and confidence intervals to validate relationships.

4. **Feature Engineering**  
   - Addressing multicollinearity and selecting important features.

5. **Model Building**  
   - Machine Learning Models:
     - K-Nearest Neighbors (KNN) [7]
     - Decision Trees [7]
     - Random Forests [8]

6. **Model Evaluation**  
   - Metrics: Accuracy, ROC-AUC.
   - Model comparison to select the best-performing algorithm.

7. **Interpretation and Reporting**  
   - Analyzing model results to identify actionable insights for airlines.

## References

1. Hameed, I., Chatterjee, R. S., Zainab, B., Tzhe, A. X., Yee, L. S., & Khan, K. (2024). Navigating loyalty and trust in the skies: The mediating role of customer satisfaction and image for sustainable airlines. *Sustainable Futures*, 8, 100299.
2. Batarlienė, N., & Slavinskaitė, N. (2023). Assessment of Factors Determining Airline Consumer Loyalty: Case Study in Lithuania. *Sustainability*, 15(2), 1320.
3. Bagwell, T. J., & Kellerman, P. (2023). Enhancing Customer Satisfaction in the Airline Industry through Service Quality: A Comparison between Legacy Airlines and Low-Cost Airlines. *Asian Journal of Tourism Research*, 2(1), 67-77.
4. Parasuraman, A., Zeithaml, V. A., & Berry, L. L. (1988). SERVQUAL: A multiple-item scale for measuring consumer perceptions of service quality. *Journal of Retailing*, 64(1), 12.
5. Badanik, B., Remenysegova, R., & Kazda, A. (2023). Sentimental Approach to Airline Service Quality Evaluation. *Aerospace*, 10(10), 883.
6. Airline Passenger Satisfaction. (n.d.). Retrieved from [Kaggle Dataset](https://www.kaggle.com/datasets/mysarahmadbhat/airline-passenger-satisfaction).
7. Decision tree in machine learning. GeeksforGeeks. (2024, March 15). [Decision Trees Overview](https://www.geeksforgeeks.org/decision-tree-introduction-example/)
8. IBM. (2024, December 19). What is Random Forest? [IBM Random Forest](https://www.ibm.com/think/topics/random-forest)

---

