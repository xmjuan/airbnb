# airbnb

Project Introduction: 
This is the first project in Udacity Data Scientist Nanodegree Program.

Motivation: 
This project is an exploratory data analysis based on dataset about Seattle Airbnb from kaggle, aiming to answer questions below:
- Which neighborhood has the best reivew rating (on average)?
- Is there a linear relationship between price and review rating?
- In which season most reviews are left?
- What features turn to drive a good review of a listing?
- What are the keywords in top 10 percent review rating?

To answer the last 2 questions, random forest regressor and wordcloud created in order to extract important features and visualize key words in good ratings.

File description:
Dataset:
- listings: all listings and features of a listing - main dataset of this analysis
- calendar: irrelevant to review - not used
- reviews: descriptive reviews with time series - less used
Analysis:
Airbnb_EDA.ipynb

Key process and results:
Process: 
- Data quality is assessed, null values in dataset have been dropped or imputed in preparation for model.
- Feature engineering: some new features are created in this part.
- Distribution of target: assess spread of review scores rating.
- Answer business questions mentioned above.
- Assess categorical and numerical features, perform feature selection and measure feature importance.
- Visualize keywords in review.

Results:
- 

