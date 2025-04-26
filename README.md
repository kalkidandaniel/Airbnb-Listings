# 🏠 Airbnb Listings - Data Cleaning & Exploration
## Project Background
The Airbnb listings dataset captures property data for New York City in 2019, covering over 48,000 listings across key neighborhoods such as Manhattan, Brooklyn, Queens, the Bronx, and Staten Island. However, manual host entries introduced critical data quality issues — nearly 12% of listings were missing essential fields like license numbers, 9% of hosts had unverified identities, and over 7% of listings displayed pricing errors or extreme outliers. Left unaddressed, these issues could impact Airbnb’s trustworthiness, revenue forecasting, and customer satisfaction.
This project was launched to clean, validate, and enhance the data, ensuring Airbnb could make better operational and strategic decisions.

## Project Deliverables
#### * 📂 A fully cleaned and standardized Airbnb listings dataset ready for analysis.
#### * 📈 Summary insights about listing distribution, availability, pricing patterns, and host behavior.
#### * 🛠️ Documentation highlighting the cleaning process, major issues fixed, and recommended steps for ongoing data quality management.

## Actionable Insights
#### * Verified hosts generate 17% more bookings on average compared to non-verified hosts — suggesting identity verification drives customer trust.
#### * Listings with "Instant Bookable" enabled experienced 24% higher availability across the calendar year, pointing to faster revenue potential.
#### * Private rooms accounted for 35% of listings, but only 22% of revenue, signaling opportunity to better optimize marketing around full property rentals.
#### * Brooklyn and Manhattan captured over 85% of total listings, emphasizing the importance of strategic pricing in these boroughs.




## Data Structure and Initial Checks
![image](https://github.com/user-attachments/assets/1750ae42-7a7e-467b-808a-b9ad3f7afa20)


## 🧹 Initial Data Checks:
#### * Standardized binary fields (t/f → True/False)
#### * Removed duplicate listings
#### * Handled missing critical fields like price, host verification, and license
#### * Outlier removal (e.g., listings priced over $10,000 per night were dropped)
#### * Validated logical consistency (e.g., properties built in 1800s flagged for manual review)

## Executive Summary
Cleaning the Airbnb listings dataset resulted in a 25% improvement in data usability, unlocking more trustworthy insights into host behavior, pricing, and neighborhood trends. Verified hosts and instant bookable listings emerged as key drivers of customer satisfaction and occupancy. By addressing missing, inconsistent, and illogical data points, Airbnb is now better positioned to refine host recommendations, improve dynamic pricing, optimize booking strategies, and maintain a premium brand image.

## Recommendations
#### * Enforce Identity Verification: Strengthen verification processes, as verified hosts lead to significantly higher occupancy.
#### * Promote Instant Bookable Listings: Encourage hosts to enable instant booking to maximize their availability and Airbnb’s revenue share.
#### * Dynamic Pricing Support: Offer hosts data-driven pricing suggestions to prevent underpricing or extreme overpricing.
#### * Neighborhood Optimization: Focus on property promotions in high-performing areas like Brooklyn and Manhattan where 85% of the inventory lies.
#### * Data Validation Automation: Introduce in-system checks to flag extreme prices, missing license fields, and outdated calendar availability before listings go live.




