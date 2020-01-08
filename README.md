Profitable App Profiles for the Google Play Market / iOS App Store

This is the repository of a kaggle project. 
Links are: 
  1) https://www.kaggle.com/namandave/profitable-app-profiles-for-the-ios-app-store
  2) https://www.kaggle.com/namandave/profitable-app-profiles-for-the-google-play-market
  

This is an advanced analysis of apps that are availale in the Google Play Store / iOS App Store and determined the profitable app profiles. Here I've used googleplaystore dataset and iOS App Store (dataset available in kaggle). The profitable app profile is determined by the features and attributes (category, genre, etc.) that attract more users to download or buy such app. The prime goal of an app to be in the Google Play Store / iOS App Store is to have more users. I have determined why such app could attracts more users, what are the categories that attract people the most, what genres give more profit to the Google Play Store / iOS App Store by attracting more users (or installers).
Report:
  1.	In the begining I've done preprocessing on the dataset to clean the data as the dataset has some problems which are mentioned below
    •	Invalid entries
    •	Duplicates & nan entries
    •	Apps that target local people or specific communities or have language other than English are invalid and can cause more confusion in analysis.
    •	Paid apps (We need only free apps because paid apps are more diverse and create more confusion because of the unique features)
  2.	After getting the cleaned dataset for the analysis, I've determined the features which are important for analysis because some features like current version, last update might not correlate with the feature like installs except for some exceptional cases. (Category & Genres)
  3.	After getting features that are important for the analysis, analysing those features more deeply and determining entries that are more acceptable for our final answer which is to determine the entry or entries that attract more users (or that have more downloads).
  4.	After getting the answers of each features, I've determined the final answer which is the app profiles that are more profitable (attract more users).

