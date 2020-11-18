# TheAndroidApp_Project

**This is the Data Camp's project in Python. It focuses on the Google Play Apps data in terms of their category, size, price, and rating as well as the sentiment polarity scores of user reviews.**

To see the whole notebook with the plotly plots use the link below:
[TheAndroidApp_notebook](https://nbviewer.jupyter.org/github/Gallawander/TheAndroidApp_Project/blob/main/TheAndroidApp_notebook.ipynb)

#### Introduction

Mobile apps are everywhere. They are easy to create and can be lucrative. Because of these two factors, more and more apps are being developed. In this project, you will do a comprehensive analysis of the Android app market by comparing over ten thousand apps in Google Play across different categories. You'll look for insights in the data to devise strategies to drive growth and retention.

The data for this project was scraped from the Google Play website. While there are many popular datasets for Apple App Store, there aren't many for Google Play apps, which is partially due to the increased difficulty in scraping the latter as compared to the former. The data files are as follows:

- `apps.csv` : contains all the details of the applications on Google Play. There are 13 features that describe a given app.
- `user_reviews.csv`: contains 100 reviews for each app, most helpful first. The text in each review has been pre-processed and attributed with three new features: Sentiment (Positive, Negative or Neutral), Sentiment Polarity and Sentiment Subjectivity.

##### Questions that we tried to answer:

- Which categories include Google Play applications?
- What is the distribution of rating for Google Play applications?
- What is the relation between the size and price of an app and its rating?
- What is the relation between the app category and price?
- What is the sentiment polarity scores of user reviews?

##### The process we had to go through to get the answers

- We loaded, cleaned, and explored apps data
- We visualized the distributions of rating for Google Play apps + the relation between their size, price and rating
- We used line box plot determine the difference between the number of downloads of paid apps vs. free apps
- We analyzed the user reviews to find out how people feel about downloaded apps

#### Conclusions

There are over 3 000 000 applications (Sep 20) in Google Play store that belong to several categories. Among them FAMILY, GAME, TOOLS, BUSINESS, MEDICAL, LIFESTYLE, and FINANCE appear to be the most numerous categories. The average rating for all applications in Google Play was determined as 4.17. Overall, free apps are more popular than the paid ones. However, the difference between the number of free downloads and paid downloads is not as big as expected. On the other hand, free applications often suffer from poor ratings and and an overall poor feeling of their functionality.
