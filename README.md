# Exploratory-Analysis-of-Music-Sales-and-Streaming


Data Overview:
The dataset consists of columns representing:

Artist: The name of the artist.
Title: The title of the song.
Year: The year the song was released.
Sales: The sales figures for the song.
Streams: The number of streams the song has received.
Downloads: The number of downloads the song has had.
Radio Plays: The number of times the song has been played on the radio.
Rating: The song's rating, which is the target variable for the model.
Analysis and Visualizations:
Top 10 Artists: A bar chart is plotted to show the top 10 artists based on the number of songs in the dataset.
Feature Selection: The dataset is reduced to the relevant numerical columns: 'Year', 'Sales', 'Streams', 'Downloads', 'Radio Plays', and 'Rating'.
Linear Regression:
A linear regression model is built to predict song ratings based on the features (sales, streams, downloads, radio plays, and year).
A train-test split is used to divide the dataset into training and testing sets.
The model is trained, and predictions are made on the test set. The Mean Squared Error (MSE) of the model is calculated to evaluate its performance.
Visualizations:
Actual vs Predicted Ratings: A scatter plot is created to show the relationship between actual and predicted ratings.
Rating Distribution: A histogram with a KDE (Kernel Density Estimation) plot shows the distribution of ratings.
Sales vs Streams: A scatter plot is shown to explore the relationship between song sales and streams, with color representing the year.
Average Ratings Over Time: A line plot shows how average song ratings have changed over the years.
Ratings by Decade: A boxplot is created to visualize the distribution of ratings by decade.
Correlation: A pairplot and a heatmap are used to visualize relationships between the numerical variables in the dataset (sales, streams, downloads, radio plays, and ratings).
Key Insights:
Linear Regression Performance: The model shows a Mean Squared Error (MSE) of 0.2536, suggesting a reasonable fit for predicting song ratings based on the features.
Distribution of Ratings: Most ratings appear to be clustered around the lower values, with a few higher ratings scattered across the dataset.
Decade Analysis: The ratings appear to vary significantly between decades, with some decades having wider distributions than others.
Feature Relationships: The pairplot and correlation matrix allow the exploration of how different features like sales, streams, and downloads relate to each other and the song's rating.
