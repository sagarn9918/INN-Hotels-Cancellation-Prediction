# INN Hotels Booking Cancellation Prediction

## 📖 About
This machine learning project analyzes hotel booking data from INN Hotels to predict cancellations. The study involves **exploratory data analysis (EDA), feature engineering, and predictive modeling** using algorithms such as **Logistic Regression and Decision Trees**. The project provides actionable insights on customer behavior and suggests strategies to reduce cancellation-related losses.

---

## 🎯 Problem Statement
Hotel booking cancellations, often due to changes in plans or scheduling conflicts, pose a significant revenue challenge. INN Hotels faces losses from unsold rooms, increased marketing costs, and lower profit margins. The objective is to build a predictive model to identify bookings likely to be canceled and offer data-driven recommendations to mitigate cancellations.

---

## 📊 Dataset
The dataset includes booking details such as lead time, meal plans, market segments, room types, and customer demographics.

### Key attributes:
- `lead_time`: Days between booking and arrival
- `avg_price_per_room`: Room price per night
- `market_segment_type`: Booking channel
- `no_of_special_requests`: Customer requests
- `booking_status`: Whether the booking was canceled

For more details, refer to the data dictionary included in the project.

---

## 📈 Exploratory Data Analysis
The project explores patterns and trends through:
- Statistical summaries and distribution analysis
- Booking trends by month and segment
- Correlation between cancellation and factors like lead time, price, and requests
- Insights into customer preferences, repeat bookings, and market dynamics

---

## 🤖 Model Building
Two predictive models were implemented:

### Logistic Regression
- Used to interpret relationships between features and cancellations
- Coefficients explain how different attributes influence cancellations
- Model optimized by addressing multicollinearity and using evaluation metrics like ROC-AUC and F1 score

### Decision Tree
- Identified important features influencing cancellations
- Pruned the tree to prevent overfitting and improve generalization
- Visualized key splits like lead time and average room price

---

## 📊 Key Insights
- **Lead time and average price per room are the strongest predictors of cancellations.**
- Special requests reduce the likelihood of cancellations.
- Online bookings are more prone to cancellations than offline ones.
- Repeat customers are less likely to cancel, highlighting the importance of loyalty programs.

---

## 📌 Business Recommendations
- Implement stricter refund policies, especially for online bookings.
- Focus on customer retention through loyalty programs and personalized services.
- Automatically confirm bookings closer to the arrival date to reduce uncertainty.
- Allocate resources optimally during peak months (October, September).

---

## 🛠️ Tools & Libraries
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn
- Scikit-learn
- Statsmodels
  
---

## ▶ How to Run
1. Clone the repository:
```bash
git clone https://github.com/your-username/inn-hotels-cancellation.git
