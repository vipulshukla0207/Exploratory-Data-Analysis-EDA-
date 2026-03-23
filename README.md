Project performs Exploratory Data Analysis (EDA) on the Google Play Store dataset.

The goal is to understand:
1-How app updates vary across time (year, month, weekday)

2-Trends in app ratings

3-Category-wise update behavior

4-Relationship between app size and ratings

Dataset Source: Google Play Store dataset

Features include:

-App Name

-Category

-Rating

-Reviews

-Size

-Installs

-Type (Free/Paid)

-Price

-Last Updated

-Genres

Data Preprocessing:-

-Handled missing values

-Converted Last Updated column to datetime format

Extracted:

-Year

-Month

-Day

-Weekday

-Treated outliers in Rating using IQR method

Key Visualizations & Insights

1-Apps Updated per Year
Slow growth from 2010–2014

Rapid increase after 2015

Peak updates in 2018

Insight: Growth of Android ecosystem accelerated significantly after 2015.

2-Apps Updated per Month

Highest updates in July

Lowest activity in early and late months

Insight: Mid-year releases/updates are more frequent.

3-Apps Updated by Weekday

Highest updates from Monday to Thursday

Lowest on weekends

Insight: Developers prefer weekdays for releases and updates.

4-Average Rating Over Time

Ratings dropped around 2012 (~3.8)

Gradual improvement after 2013

Highest ratings in 2018 (>4.2)

Insight: Better development practices improved app quality, Frequent updates positively impact ratings

5- Top App Categories by Updates

Tools category leads significantly

Followed by:

Entertainment

Education

Insight:  Utility apps require frequent updates and maintenance.

6-Size vs Rating

No strong correlation between app size and rating

Insight: App quality matters more than size.

7-App Type Distribution

Majority apps are Free

Very few are Paid

Insight: Freemium model dominates the Play Store ecosystem.

Technologies Used
Python 

Pandas

NumPy

Matplotlib

Seaborn

Google Colab

Author:

Vipul Kumar Shukla
Aspiring Data Scientist
Background: M.Sc. Chemistry
Passionate about Data Analysis & Visualization
