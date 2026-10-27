# Google_Play_Store-Power_BI_Project
This project was called App Insights Unlocked, where I analyzed Google Play Store data using Microsoft Power BI.

The main objective was to understand app performance, user preferences, and the factors associated with app ratings and popularity.

I worked with two datasets. The first contained app-level information such as category, rating, installs, price, and size. The second contained user reviews and sentiment classifications.

I used Power Query for data preparation, Power BI for data modeling and visualization, and DAX for calculating analytical measures. The analysis focused on app ratings, category performance, free-versus-paid applications, reported installs, and customer sentiment.

One of the main challenges was handling missing values, duplicate app records, and inconsistent data types. I also learned that the app dataset and review dataset have different levels of detail, so the data model must avoid duplicating app-level metrics.

One important finding was that the average app rating was approximately 4.19 out of 5 after excluding missing and invalid ratings. I also found that Game and Communication had the largest summed reported install thresholds in the supplied dataset.

Another finding was that approximately 64% of classified review records had positive sentiment. However, I calculated this percentage using only reviews with available sentiment labels.

Based on the analysis, I would recommend investigating negative review themes, comparing app categories using multiple performance metrics, evaluating free and paid apps within similar categories, and developing an interactive dashboard for ongoing monitoring.

Overall, this project improved my Power BI, data-cleaning, data-modeling, and analytical skills. It also helped me understand how to convert raw data into useful information for product and marketing decisions.
