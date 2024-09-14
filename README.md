# Marketing-Campaign-Performance
Analyze the effectiveness of Different Marketing channels and campaigns across key metrics like CTR, ROI, Conversion Rate, CAC , CLTV etc

The Marketing Campaign Performance Dataset provides valuable insights into the effectiveness of various marketing campaigns. This dataset captures the performance metrics, target audience, duration, channels used, and other essential factors that contribute to the success of marketing initiatives. With 200000 unique rows of data spanning two years, this dataset offers a comprehensive view of campaign performance across diverse companies and customer segments.

The dataset contains 200,000 entries and 16 columns related to marketing campaigns. Key fields include:
•	Campaign_ID: Unique identifier for each marketing campaign.
•	Company: The company running the campaign.
•	Campaign_Type: The type of campaign (Email, Display, Influencer, etc.).
•	Target_Audience: The specific audience segment targeted by the campaign, such as women aged 25-34, men aged 18-24, or all age groups.
•	Duration: Length of the campaign.
•	Channel_Used: The channels utilized to promote the campaign, which may include email, social media platforms, YouTube, websites, or Google Ads 
•	Conversion_Rate: The percentage of leads or impressions that converted into desired actions, indicating campaign effectiveness..
•	Acquisition_Cost: Total cost to acquire customers during the campaign.
•	ROI: Return on investment for the campaign.
•	Location: The geographical location where the campaign was conducted, encompassing major cities like New York, Los Angeles, Chicago, Houston, or Miami.
•	Language: The language used in the campaign communication, including English, Spanish, French, German, or Mandarin.
•	Clicks: Number of clicks generated.
•	Impressions: Number of times the ad was shown.
•	Engagement_Score: Engagement level of the audience (e.g., likes, comments).
•	Customer_Segment: The specific group targeted (e.g., Health & Wellness).
•	Date: Date when the campaign was launched.
 


To proceed further, I will Create additional KPIs like Customer Lifetime Value, CTR, Lead score , Website Visitors , Cost per Action/Acquisition , Cost per lead from the given dataset in separate columns. After creating these columns or metrics, Create a list of questions and provide actionable insights and recommendations

•	Calculate ARPU (approximate average revenue per user)
•	# ARPU = (Acquisition_Cost * ROI) / Clicks
•	Estimate customer lifetime based on campaign duration# Assuming each day of campaign duration is roughly equivalent to 0.1 of customer lifetime
•	Customer lifetime = Duration days*0.1
•	Estimate gross margin (assuming 70% margin based on standard practice unless specified)
•	CLTV = ARPU * Customer Lifetime * 0.7
•	Calculate Lead Score based on engagement metrics and conversion rate
•	# Lead Score = (0.4 * Engagement_Score) + (0.3 * Conversion_Rate) + (0.2 * Clicks) + (0.1 * Impressions)
•	CTR = Clicks*100/Impressions
•	Website visitors = 0.6*Impressions
•	Cost per Action = Acquisition Cost/Clicks 
•	Cost per Lead = Acquisition Cost/(Clicks * Conversion rate)

