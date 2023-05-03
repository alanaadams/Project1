# Project1-Group1-HousingHotshots
Alana Adams, Lincoln Martin, Sharada Muthusubramanian

NY Housing Prices

Problem Statement: Analyze data for New York housing prices in regards to different features focusing on number of bedrooms in the house.

Data Source: https://www.kaggle.com/datasets/yasserh/housing-prices-dataset

Null (H0) hypothesis - As number of bedrooms increases the price of the house will not change.  

Alternative Hypothesis (H1) - as the number of bedrooms increase the price of the house will have the tendency to increase.

Results: The null hypothesis is FALSE.

With regard to housing data, the following questions were asked:
1. Does area of house or number of bedrooms matter more to homebuyers?
2. Is a furnished home more preferred than an unfurnished home?
3. Does the main road status matter to homebuyers?
4. Does number of parking spaces have any correlation to housing price?
5. Do New Yorkers prefer houses with basements over guestrooms?
6. Can we predict housing price based on area of the house?
7. Do the number of bathrooms correlate with the number of bedrooms?
8. Do we see a relationship between price and number of stories in a house?
9. Does the total number of rooms (bathroom, bedroom, guestroom, basement) increase home price more than total area?

Answers:
1. Does area of house or number of bedrooms matter more to homebuyers? 

Output suggests that area matters more than number of bedrooms.  Area of the house has upward trend with the increase in area of the house the price increases.  Where as, with the increase in the number of bedrooms the price drops after a certain point. 

2. Is a furnished home more preferred than an unfurnished home?

New Yorkers are willing to pay more for the furnished homes as opposed to semi or unfurnished home. The median price of furnished homes comparing to unfurnished home is 37.8% higher. The median price of furnished homes comparing to semi-furnished home is 10.8% higher. 

3. Does the main road status matter to homebuyers?

Based on the data gathered, home prices are less similar when close to a main road, as opposed to not being near a main road.  This can be determined when observing the standard deviation of home prices that are located near a main road or not. The standard deviation of prices for homes near a main road is higher than homes not near a main road.   This means that the prices are less similar in overall value as opposed to prices of homes not near a main road.

4. Does number of parking spaces have any correlation to housing price?

Generally, the number of parking spaces of a home produces a more saturated cluster of consolidated data.  When observing the data, as parking spaces for homes increase, the price of homes increases.  Based on the scatterplot data, an observable trend is that if a home has more than two parking spaces, there is less observable data, but price still has a gradual increase as parking spaces increase.

5. Do New Yorkers prefer houses with basements over guestrooms?

It is inconclusive whether New Yorkers prefer houses with basements over bedrooms.  Guest rooms are valued more highly by NY homebuyers as reflected by price, however basements are more frequently purchased by NY homebuyers.  New Yorkers show an increased preference towards, guest room, having both a guest room and basement, and having basements over not having either feature (in that order, as demonstrated by housing price as an indicator of feature value).  However, this correlation is tenuous.  New Yorkers much more frequently inhabit homes with neither basement nor guest room features than either or both features. Homes with basements are 3.4 times more frequently inhabited than homes with guest rooms.

6. Can we predict housing price based on area of the house? 

No, housing price cannot be predicted based on area of the house, nor can area of the house be predicted based on area of the house.  The correlation between housing price and area of the house is too slight. r-value of 0.29.  A sample housing price predicted an area  30% off from the actual area.  A sample housing area predicted an area 10% off from the actual price.  Although, slightly positively correlated, the margin of error is too large.  

7. Do the number of bathrooms correlate with the number of bedrooms?

The correlation coefficient between Bedrooms and Price is 0.37. This indicates a very weak correlation between Bedrooms and Price such that as the number of bedrooms in a house increases, the price is likely to increase.  The correlation coefficient between Bathrooms and Price is 0.52. This indicates a moderate correlation between Bedrooms and Price such that as the number of bathrooms in a house increases, the price is likely to increase.  The correlation coefficient between Bedrooms and Bathrooms is 0.37. This indicates a very weak correlation between Bedrooms and Price such that as the number of bedrooms in a house increases, the number of bathrooms. is likely to increase.  This data indicates that the number of bathrooms in a house is more favorable to homebuyers than the number of bedrooms, because the correlation coefficients indicate a stronger positive relationship between number of bathrooms and price than number of bedrooms and price. This refutes the claim that bedrooms are the most important feature to homebuyers.

8. Do we see a relationship between price and number of stories in a house?

YES.  As the number of stories increase the price of the home increases.  We also performed ANOVA test to understand the statistical significance.  With p_value of 2.6832459713031025 × 10-24 there price by stories is  not  statistically significant.

9. Does the total number of rooms (bathroom, bedroom, guestroom, basement) increase home price more than total area?

No! Measured the price per sqft and price per number of rooms we could not compare the two metrics.
There is no statistical significance between number of rooms and total area with regards to price increase.

BONUS: Per capita income of NY in 2022 and NY condo price comparison between March of 2022 and 2023.

The NY condo prices stayed steady in 2022 and 2023.

