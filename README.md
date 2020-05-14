# M5-Walmart-Predicition
Data Source
The data for this project was obtained from Kaggle.
Jupyter notebooks
Part_1
Part_2
Project Presentation
Google Slides
Problem Summary
I used the data from the Kaggle competition(M5-Forecasting Accuracy). Original competition intended to estimate unit sales of Walmart retail goods. Particullary,the metric described by organizers is Weighted Root Mean Squared Scaled Error(WRMSSE). This means that, businesswise, in order for a method to perform well, it must provide accurate forecasts across all hierarchical levels, especially for series of high importance, i.e. for series that represent significant sales, measured in US dollars. (source: M5-Competitors-Guide-Final-10-March-2020). For that reason, I decided to explore forecast methods that will perform better on the series that are more valuable (generates high revenue) for the company.
Metrics
For this project I used RMSE as a metric. It serves as good approxiamtion of WRMSSE, particulary, when applied for an each item separately.
Key Takeaways
Around 14% of the retail items generated 50% of the revenue.
Moving average of sales are date features are important.
Scaled version of the model for the whole dataset(around 50mln rows) could be compute-intensive.
Next Steps
Create better features
Apply good validation strategy
Improve model accuracy
Explore options to reduce computation time
Scale solution to the whole dataset
