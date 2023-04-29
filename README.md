# Final-Project-Tableau

## Project/Goals
The goal of this project is to familiarize with Tableau and create visuals that explain the data in a clear, concise way for presentation to a management audience.

## Process
### (your step 1)
### (your step 2)

## Results
I opted for option 2 and used the New York Airbnb dataset.

I created a number of visualizations:

1. A zip code map of New York with information about the airbnb's there and a clustering on price, rating, and number of ratings.
2. A simple table of neighborhood and price / rating. I originally created a bar chart, but changed to a table to not distract from other visuals in my dashboard.
3. Bar charts of median price / rating for each type of location type
4. Bar charts of median price / rating for each type of room type
5. Stacked line charts of price, rating, and number of reviews for each year of host
6. Price for each level of beds (transformed to a categortical 1,2,3,4,5+ instead of numeric) with a secondary bar on top for price per bed
7. Ratings for each level of beds
8. Price for each individual airbnb with rating as a color on top
9. Line chart of price x rating (with a regression line)
10. Line chart of price x number of reviews (with a regression line)
11. Unused: Line chart of reviews x number of ratings
12. Unused: Bar chart of ratings for each location

In exploring the dataset I did find there are three groups of airbnbs: Lower price, higher price, and lower rating (the first two groups have high ratings). The median for rating across categories was about 90-95 so really not much variability there. Price did vary a bit so was easier to look at. For price:

1. Location type did make a difference in price with condos, villas and bungalows being most expensive and dorms and campers being least. 
2. Having privacy (entire home/apt) had a high premium
3. More beds did lead to a higher price, but a lower price per bed
4. The year someone started hosting didn't have much impact on price
5. Higher ratings did generally mean higher prices, but this was a weak relationship

## Challenges 
The biggest challenges with this project were that it's difficult to figure out where to start on a dataset if you have no clear goals, but this does let you get creative and force you to learn the dataset to figure out what to do. The second challenge is that Tableau can be a bit clunky when it comes to data manipulation, so sometimes its easier to just make edits in Excel or Python

## Future Goals
If I had more time, it'd be great to see if theres any historical data to track prices over time, or even to look at other cities and see how they compare. It would also be interesting to dig into some of the other datasets and give those a try.
