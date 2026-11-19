# E-Commerce Customer Reviews | Sentiment Analysis

Python data cleaning + VADER sentiment analysis + interactive Tableau dashboard exploring customer satisfaction, product ratings, recommendations, and sentiment across women's clothing departments.

## Dashboard

### 🛍️ E-Commerce Sentiment Dashboard

📊 [View E-Commerce Sentiment Dashboard on Tableau Public](https://public.tableau.com/app/profile/teodora.maksimovic/viz/E-CommerceCustomerReviewsSentimentAnalysis/E-CommerceSentimentDashboar)

![E-Commerce Sentiment Dashboard](<images/E-Commerce Sentiment Dashboar.png>)

> The screenshot is static. Open the Tableau Public link to explore the interactive dashboard and filters.

## What I did

- **Python (pandas):** explored and cleaned customer review data, handled missing values, removed reviews without text, created a review length feature, and exported the processed dataset.
- **VADER Sentiment Analysis:** analyzed customer review text, calculated positive, negative, neutral, and compound sentiment scores, and classified reviews as Positive, Neutral or Negative.
- **Tableau:** built an interactive dashboard with KPI cards and visualizations comparing sentiment across customer ratings, product recommendations, and clothing departments.

## Key Insights

- Analyzed **22 641 customer reviews**, with an average product rating of **4.18 out of 5**.
  
- **92.9%** of reviews were classified as positive, while **5.9%** were negative and **1.2%** were neutral.
  
- **81.9%** of reviews indicated that customers recommended the product.
  
- Positive sentiment becomes more common as customer ratings increase.
  
- **74.62% of reviews marked as "Not Recommended" were still classified as positive** by VADER, highlighting the difference between positive language and actual product satisfaction.
  
- **Negative product experiences are not always expressed through negative language.** Among reviews marked as "Not Recommended," 74.62% were classified as positive. Businesses should analyze ratings and recommendation decisions alongside review sentiment rather than relying on sentiment scores alone.
  
- **Low-rated reviews deserve additional attention even when their sentiment is positive.** Some reviews with ratings of 1 or 2 were classified as positive, indicating that automated sentiment classification may miss dissatisfaction expressed through mixed or context-dependent language.

- **Customer feedback analysis can help prioritize product improvements.** Departments with higher proportions of negative reviews may be useful starting points for investigating product quality.

- Ratings, recommendations, and sentiment scores capture different aspects of the customer experience and are more informative when analyzed together.

## Original Data Source

[Kaggle: Women's Clothing E-Commerce Reviews](https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews)

## Tools

Python · VADER Sentiment Analysis · Tableau Public · Jupyter Notebook

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-VADER-4B8BBE?style=for-the-badge)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
