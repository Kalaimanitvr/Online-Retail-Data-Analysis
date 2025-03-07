# Online Retail Data Analysis 📊

## 🌐 Quick Access Links
Access the key files for this project:
- 📓 **[Jupyter Notebook](./online_retails.ipynb)**: Core data analysis and machine learning workflows.
- 📑 **[Data Dictionary](./online_retailing_data_dictionary.pdf)**: Detailed column descriptions of the dataset.
- 🌐 **[Tableau Dashboard](https://public.tableau.com/views/online_retail_dashboard_17413829628300/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**.


## Project Overview 🌐

This project explores transactional data from a UK-based non-store online retailer specializing in unique, all-occasion gifts, primarily catering to wholesalers. The analysis period spans from December 2010 to December 2011, providing insights into sales trends, customer behavior, and product performance.


### Data Cleaning

- Missing values in `CustomerID` and `Description` were removed, impacting 24.93% and 0.27% of the dataset respectively.

### Outlier Management

- Outliers in `Quantity` and `UnitPrice` were managed through Winsorization, significantly reducing their distribution impact.

## Key Insights from Data Analysis 🔑

### Sales Trends
- A distinct seasonality in sales was observed, with peaks typically around the start and end of the year.
- Total sales reached a high of approximately 1.2 million in November 2011, highlighting effective promotional strategies or seasonal demand.

### Product Performance
- The top-selling product, "REGENCY CAKESTAND 3 TIER," generated 69,242.50.

### Customer Segmentation
-Conducted RFM analysis to segment customers based on transaction recency, frequency, and monetary value.
-The segmentation helped identify potential loyal customers who could be targeted for retention strategies.
## Clustering Analysis 🧑‍🤝‍🧑

- Applied K-Means clustering to segment customers into three distinct groups, helping tailor marketing efforts to specific customer behaviors.
- The optimal number of clusters, determined through silhouette scoring, was three, with a silhouette score of 0.4642, indicating moderately distinct clusters.

## Cancellation Insights 🚫

- Analyzed cancellation trends to detect patterns and potential areas for policy adjustments.
- The total cancellation rate stood at 2.19%, with cancellations peaking in late 2011.

## Conclusion 📜
- This analysis provides actionable insights into enhancing product offerings, improving customer engagement, and reducing cancellations.
