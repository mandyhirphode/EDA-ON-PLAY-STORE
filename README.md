<h1 align="center"> Play Store App Review Analysis</h1>
<h3 align="center"> AlmaBetter Verified Project - <a href="https://www.almabetter.com/"> AlmaBetter </a> </h3>

<p align="center"> 
<img src="GIF/google play.gif" alt="Animated gif" height="282px">
</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 📂 Input Files:
- **Play Store Data.csv**: Contains essential details about each app, such as reviews, ratings, and installs.
- **User Reviews.csv**: Contains user reviews and sentiment scores for corresponding apps.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 📖 Project Overview:
This project explores data on **10,841 Play Store apps** and **64,295 user reviews**. The goal is to identify the factors that influence app popularity, pricing, size, and user sentiment. The dataset spans diverse categories, including Family, Communication, Entertainment, Tools, Music, and Camera. By analyzing this data, we can uncover key insights into what drives user engagement and app success. Our approach includes filtering the data and creating visualizations through Exploratory Data Analysis (EDA) to inform app developers and marketers on strategies for maintaining a competitive edge in the mobile app market.

## 📝 Dataset Summary:

**Play Store Data**: Consists of 10,841 records and 13 columns, covering various attributes like name, category, size, rating, reviews, installs, type, price, content rating, genre, last update, current version, and required Android version.

**User Reviews**: Contains 64,295 records and 5 columns, providing user reviews and sentiment analysis for each app.

### The contents of Play Store Data are:
- **App**: Name of the app, sometimes with a short description.
- **Category**: App's category, with 33 unique categories.
- **Size**: Disk space required for the app.
- **Rating**: Average rating from users (1-5).
- **Reviews**: Number of user reviews.
- **Installs**: Approximate number of installs.
- **Type**: Indicates whether the app is Free or Paid.
- **Price**: Price for installing the app; free apps show as zero.
- **Content Rating**: Suitable age group for the app.
- **Genres**: App's genres.
- **Last Updated**: Date of the last app update.
- **Current Ver**: Current version of the app.
- **Android Ver**: Required Android version for the app.

### The contents of User Reviews are:
- **App**: Name and optional short description of the app.
- **Translated_Review**: English translation of user reviews.
- **Sentiment**: Emotion of the review (Positive, Negative, Neutral).
- **Sentiment_Polarity**: Score from -1 to 1, indicating review positivity or negativity.
- **Sentiment_Subjectivity**: Range [0,1], indicating how opinion-based a review is (0 = factual, 1 = highly opinionated).

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 📋 Key Insights and Conclusions:
From our analysis, we derived several key insights and recommendations:
- **Focus on Free Apps**: Approximately **92%** of apps are free, suggesting a preference among users for free options. Developers aiming for broad reach should consider releasing free apps.
- **Underexplored Categories**: Categories like Events, Beauty, and Parenting show high user engagement with relatively lower competition, making them prime areas for growth.
- **Regular Updates**: Apps should be updated frequently to retain users.
- **Size and Price Recommendations**: For paid apps, keeping size under 20 MB and price reasonable maximizes reach. Heavier apps (>90 MB) tend to be more popular, especially in categories like Games and Family.
- **Content Accessibility**: **82%** of apps are suitable for all age groups, emphasizing the importance of making content universally accessible.
  
### Additional Highlights:
- **Most Competitive Category**: Family.
- **Highest Number of Installs**: Games.
- **Category with the Highest Average Installs**: Communication.
- **Highly Rated Apps**: Approximately **80%** of apps have high ratings.
- **Top Free Apps**: 20 free apps have surpassed one billion installs.
- **Top Revenue Generator**: Minecraft, the only paid app with over 10M installs, leads in revenue from installation fees.
- **Category with the Highest Average Install Fee**: Finance.
- **Most Popular App by Reviews**: Facebook.
- **Median App Size**: 12 MB.
- **App Size Variation**: Apps with a size that varies by device have the highest average installs.
- **Popularity by Size**: Larger apps (>90 MB) generally attract more reviews.
- **Top Positive and Negative Reviews**: Helix Jump has the most positive reviews, while Angry Birds Classic leads in negative reviews.

By conducting this exploratory data analysis, we aim to mitigate risks in app development and inspire data-driven decisions for better engagement and market success.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
