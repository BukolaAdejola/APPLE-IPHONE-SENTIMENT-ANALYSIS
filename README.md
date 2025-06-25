# APPLE IPHONE SENTIMENT ANALYSIS

![Apple Iphone](https://github.com/user-attachments/assets/15cf6510-c278-4036-baad-ad7b6cd38d03)

## Table of Contents
- [Introduction](#Introduction)
- [Dataset Overview](#DatasetOverview)
- [Project Objective](#ProjectObjective)
- [Data Cleaning](#DataCleaning)
- [Insights and Analysis](#InsightsandAnalysis)
- [Dashboard](Dashboard)
- [Conclusion](Conclusion)
- [Recommendations](#Recommendations)

 ## Introduction
 The Apple iPhone XR 64GB (Black) Reviews – India dataset contains a curated collection of customer reviews for the black variant of Apple's iPhone XR (64GB),
 exclusively from Indian consumers. Each entry provides comprehensive information including the review text, rating, review title, reviewer profile, date of review,
 and engagement indicators such as helpful votes, responses, and comments. This dataset offers valuable insights into Indian consumer perceptions and satisfaction
with the device, making it ideal for applications in sentiment analysis, customer feedback modeling, and localized market research within the Indian tech sector.

-   ## Dataset Overview
    The dataset consist of  5000 rows and 12 columns:
- Field 							        Description
- Index						        Unique number to track order
- Product 					      Name/Type of Product sold
- Helpful Count					  Number of users who found the review helpful
- Total comments				  Total Comments under the review
- Url						          Product Link
- Review- Company				  Country under study
- Reviewed at: 					  Review Date
- Reviewed text:				  Full review content
- Review rating					  Numerical scores
- Product company				  Brand/Manufacturer
- Profile names					  Review names
- Review Title					  Short review headline

<img width="830" alt="iphone data" src="https://github.com/user-attachments/assets/30577910-1697-45fb-a124-b1a6373874d6" />

## Project Objective
1.	What is the name of the company associated with the product?
2.	What Country are the reviews from?
3.	What is the first product reviewed?
4.	How many total reviews were recorded?
5.	What is the average rating given by the reviewers?
6.	How did review volume change over the years?
7.	How did the number of helpful votes vary by month?
8.	What is the main focus of customer reviews – product performance or the purchasing platform?

##  Data Cleaning
1.	Duplicate Removal: Identified and removed duplicate records to maintain data integrity.
2. 	Rating Extraction: Created a new column named Responses by extracting numerical values from the Review Rating column to isolate rating information.
3. 	Sentiment Categorization: Introduced a new column called Response, which categorizes reviews as Positive, Negative, or Neutral, based on the extracted rating.
4.	Issue Classification: Developed a new column named Issue Category using text search functions to classify reviews as being related to either the Product or the Market, based on the most frequently used keywords.
5.	Data Type Validation: Ensured all columns were assigned appropriate data types to support accurate analysis and visualization.

## Insights and Analysis
1.	What is the name of the company associated with the product?
 The company name is Apple.

3.	Which country are the reviews from?
	The reviews were submitted by customers in India.
 
4.	What is the first product reviewed?
	The first product reviewed is the Apple iPhone.

6.	How many total reviews were recorded?
	A total of 44,447 reviews were collected.

8.	What is the average rating given by reviewers?
	The average customer rating is 4.0, indicating generally positive feedback.

10.	How did review volume change over the years?
	2018: Only 23 reviews
	2019: Significant increase to 3,804 reviews
	2020: Decrease to 1,173 reviews
This trend suggests a peak in review activity in 2019 followed by a decline in 2020.

12.	How did the number of helpful votes vary by month?
	January: 2,017 helpful votes
	February: 165
	March: 66
	April: 797
	May: 1,989
	June: 183
	July: 174
	August: 152
	September: 161
	October: 292
	November: 3,244
	December: 5,400 (highest monthly helpful count)
December stands out as the month with the highest engagement, possibly due to seasonal promotions or holiday shopping activity.

13.	 What was the main focus of customer reviews—product performance or the purchasing platform?
Analysis of the review text reveals that customers primarily commented on the product itself rather than the market or platform from which it was purchased.
 Most feedback centered around the performance, features, and quality of the phone, indicating that product experience was the main driver of customer sentiment,
not the buying environment or service provider.

## Dashboard
<img width="601" alt="Sentiments Dashboard" src="https://github.com/user-attachments/assets/840199f7-df94-4d96-b5a7-5bbf728bf423" />

## Conclusion

The analysis of Apple product reviews from India reveals several key insights:
-	High Engagement: A significant volume of reviews (44,447) with an average rating of 4.0 indicates strong customer engagement and general satisfaction.
-	Peak Review Activity: Review volume peaked in 2019 and declined in 2020, suggesting a potential shift in customer feedback behavior or market dynamics.
-	Seasonal Trends: The highest number of helpful votes was recorded in December, pointing to increased user interaction during the holiday season—likely linked to promotional periods.
-	Product-Centric Feedback: Reviews were heavily focused on the product itself, particularly the Apple iPhone, with minimal concern expressed about the marketplace or seller. This emphasizes the importance of the product experience over the purchase environment.

## Recommendations

1.	Leverage Peak Seasons for Promotions
Since December shows the highest engagement, Apple and its partners should focus marketing and promotional efforts during this period to maximize visibility and conversions.
2.	Monitor and Boost Year-Round Engagement
Implement strategies (e.g., post-purchase review reminders, loyalty incentives) to encourage reviews consistently throughout the year,
especially in lower-activity months like March and August.
3.	Continue to Prioritize Product Quality
Since most feedback centers on the product rather than the platform, maintaining high product standards should remain a top priority.
Investing in features and performance improvements can drive continued customer satisfaction.
4.	Utilize Review Data for Product Development
Analyze detailed product-related feedback to identify common praise and pain points. Use this data to guide feature enhancements,
 design changes, and customer support improvements.
5.	Explore Decline in Review Volume Post-2019
Investigate possible reasons for the decline in reviews in 2020 (e.g., market saturation, external factors like the pandemic, or reduced product launches)
and address any underlying issues.

