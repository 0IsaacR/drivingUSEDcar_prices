# drivingUSEDcar_prices
Regression: Data Analysis, Data Cleaning and Model Performance

From vehicle purchase data, determine which features are most important in buying a used vehicle.

This dataset contains many features about a vehicle, such as paint color, transmission, model, make, fuel type, etc.. but many of these features were not useful.

There were many instances where about half of the data was missing in a certain column. Some columns were about 80% intact. A decision was made to completely remove columns that were "too" incomplete. As for the other columns, i decided to remove the affected rows.


After removing problematic entries, I encode object data into numerical data.

After this I normalize the dataset and prepare it for to feed it into my models.

I used PCA but that will be a work in progress.

I also tried to impute some missing values but it is still a work in progress.

Finally i used Lasso, Ridge, and ElasticNet to model this dataset. All three models gave me the same result but Ridge regression came out on top with slightly less loss.

The verdict was that price of a used vehicle is positively influenced by the year and model of the vehicle, while it is negatively influenced by the odometer miliage and transmission type.
