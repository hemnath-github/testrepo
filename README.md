# Google Playstore Project Documentation.

Google Playstore data analytics - python.

There are two csv data files:

(i) Apps.csv , 
(ii) User_reviews csv.

Data Cleaning Process :

(*) Removing nan values from both datasets,

(*) Converting Last Updated column into proper date format column,

(*) Merging the both datasets into one csv file data as App_UserReviews.csv,

(*) Clean the "Installs" column: remove commas and '+' then convert to integer,

(*) Formatting Price column from string into float,

(*) Checking null values and Rating, Current Ver, Android Ver, Translated_Review, Sentiment, Sentiment_Polarity, Sentiment_Subjectivity columns are null values occured by natures.

Data Analysis Process: 

(*) Comparing the average rating and total review count for the top 10 app categories by number of installs through the grouped bar chart.

(*) Visualize the choropleth map using Plotly to global installs by Category and Apply filters to show data for only the top 5 app categories .

(*) Comparing the dual-axis chart to shown the average installs and revenue for free vs. paid apps within the top 3 app categories.

(*) Plot a time series line chart to show the trend of total installs over time, segmented by app category.

(*) Plot a bubble chart to analyze the relationship between app size and average rating, with the bubble size representing the number of installs.


Hint :  Each chart has time restriction to show output for particular time frame that would also be mentioned in the code.

There are five tasks and their results had been attached in the google collab notebook.
