# EV_MARKET_SEGMENTATION

# EV Market Segmentation

This project analyzes the Indian electric vehicle (EV) market — particularly 4-wheeler EVs — using machine learning-based segmentation methods. The goal is to identify ideal customer groups and help companies decide which type of EVs to manufacture and whom to target.

---

## Problem Statement

The Indian EV market is growing rapidly due to rising fuel prices, environmental concerns, and increased awareness of clean energy. Companies need to:
1. Decide which category of EVs to manufacture (e.g., SUVs, sedans, hatchbacks).
2. Identify the most promising customer segments for targeting.

---

## Objective

To analyze customer behavior, preferences, and demographics using:
- Exploratory Data Analysis (EDA)
- Principal Component Analysis (PCA)
- K-Means Clustering
- Hierarchical Clustering

This segmentation helps in product development, marketing strategy, and targeting the right customer base.

---

## Datasets Used

- Demographic Dataset – from [Kaggle](https://www.kaggle.com/)
- EV Product Reviews Dataset – modified to include missing values such as brand names.

---

## Techniques Applied

- EDA using matplotlib, seaborn
- PCA for dimensionality reduction
- K-Means clustering (with Elbow method and k-means++)
- Hierarchical clustering (visualized using Dendrograms)
- Customer profiling based on age, salary, education, marital status, and region

---

## Key Insights

- **Segment 0**: Early majority, highly satisfied, prefer Tata Nexon
- **Segment 1**: Late adopters, unsatisfied, prefer Tata Tigor
- **Segment 2**: Early adopters, value comfort & exterior, neutral on brand

- **Most popular choice**: SUV (e.g., Nexon, Creta)
- **Price is correlated with income**, but not with dependents or loan status
- **Preferred regions for EVs**: Karnataka, Delhi, Tamil Nadu

---

## Clustering Summary

- **K-Means**: Optimal clusters selected using the Elbow method
- **Hierarchical**: Two clear customer segments identified via Dendrogram

---

## Target Customer Profiles

| Cluster | Age Group | Profession         | Marital Status | Education     | Preferred Vehicle |
|---------|------------|--------------------|----------------|---------------|-------------------|
| 0       | 20–30      | Graduate, Single    | Single         | Graduate      | Hatchback, Sedan  |
| 1       | 30–45      | Professional        | Married        | Graduate      | SUV               |
| 2       | 30+        | Businessmen         | Married        | Postgraduate  | SUV, Luxury       |
| 3       | 30–45      | Salaried Professional | Married      | Postgraduate  | SUV               |

---

## Geographic Segmentation

- **High EV adoption + infrastructure**: Karnataka, Delhi
- **Moderate EV adoption**: Maharashtra, Rajasthan, Kerala
- **Low adoption**: Bihar, Punjab, Jharkhand

---

## Future Improvements

- Explore DBSCAN or Gaussian Mixture Models for finer clustering
- Collect larger datasets via surveys or scraping
- Include additional variables like charging infrastructure and brand loyalty

---

## Files Included

- `EV_Market.ipynb`: Main notebook for analysis and clustering
- `EV Maker by Place.csv`: Regional EV preference dataset
- `Pradeep_dataset(age).csv`: Demographic data
- `EV_MARKET_SEGMENTATION.pdf`: Final report with analysis and visualizations

---

##  GitHub Repository

[EV Market Segmentation GitHub Repo](https://github.com/Pradeep123-abc/EV_MARKET_SEGMENTATION.git)

---

## Author

**Pradeep Agrahari**  
*Machine Learning Intern, Feynn Labs*

---

