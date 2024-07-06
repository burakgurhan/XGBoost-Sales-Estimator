# XGBoost-Sales-Estimator
 
Problem:

Amazon sellers often lack insights into the individual sales volume of their products. This information is crucial for business planning, inventory management, and understanding product popularity.

Solution:

This project presents a machine learning model using the XGBoost algorithm to predict product sales on Amazon. The model's performance is evaluated using the RMSE metric.

Data:

The training dataset for the model was compiled from two sources:

Helium10 Blackbox: A tool that provides valuable data for Amazon sellers.
Keepa ProductFinder: A feature that offers product data and insights.
The dataset includes approximately 4500 products from the electronics category and various attributes about each product. The data is from the previous year and does not reflect current information.

Model:

The XGBoost algorithm was chosen for its effectiveness in handling structured data and its ability to capture complex relationships within the dataset. The model was trained using various hyperparameter tuning techniques to optimize its performance.

Evaluation:

The Root Mean Squared Error (RMSE) metric was used to evaluate the model's predictive accuracy. The model achieved an RMSE of 12.5, indicating a reasonable fit to the data.

Implications:

This model can be used by Amazon sellers to:

Forecast monthly product sales to aid in planning and inventory management
Gain insights into product popularity and identify potential bestsellers
Make data-driven decisions to optimize their business strategies
Future Directions:

Explore the use of more recent data to improve model performance
Incorporate additional features and data sources to enhance predictive capabilities
Investigate the application of the model to other product categories
Additional Notes:

You can find my exploratory data analysis project for the same dataset in my other repositories.
The model is provided "as is" and may require further refinement based on specific product categories and sales patterns.
Feel free to reach out with any questions or feedback.