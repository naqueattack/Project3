# Final-Project-Tableau

## Project/Goals
The goal of this project is to familiarize with Tableau and create visuals that explain the data in a clear, concise way for presentation to a management audience.

## Process
### My first step was to figure out what dataset to use. I took a brief look at a few and then landed on the airbnb dataset as it seemed the most intuitive
### My second step was to take a look at the data in Tableau after importing it and get a feel for the variables. This included looking at data types, range of answers, distribution, etc. 
### Next, I checked the dataset for cleanliness (nulls, outliers, etc.) and make some updates:
1. 3 places missing date, imputed date of host id preceding and following.
2. 3 places missing property type, imputed type based on name (2 apartments, 1 house)
3. Imputed 1 bed for missing bed rows
4. Removed rows with 0 beds
5. Removed number of records column
6. Removed a few outliers at the high end of price (with names like "no longer booking reservations" or "fake listing")
7. Changed the type of any type with less than 5 entries to "Other"
8. Did not remove 'duplicates' as it is definitely possible someone has multiple properties and is lazy enough to just leave the listing the exact same (e.g. "Cozy Apt #1" vs. "Cozy Apt #2")

### I then started creating some basic visuals to better understand how the data looks / trends. This was the second portion of my EDA. I created crosstab charts & graphs and line charts where possible to see how things trended or where I might find relationships. In doing this I discovered that price might be interesting, but reviews were pretty flat across the board (90's).
### After creating about 5-8 charts I got a better idea for what I wanted to do and started pulling together a dashboard. As I was doing that I had ideas for other visuals and iterated between making new charts and updating my dashboard
### As a final step, I refined my visuals to make my dashboards more intuitive and easy to read, and put the finishing touches on everything


    
### Then I started creating basic visuals to see how everything came together

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

In exploring the dataset I did find there are three groups of airbnbs: Lower price, higher price, and lower rating (the first two groups have high ratings). The median for rating across categories was about 90-95 so really not much variability there. Price did vary a bit so was easier to look at. 

I opted to answer, what attributes affect ratings & price and what do the properties of this area look like (how expensive are they and where, how highly rated and where)

For price:
1. Location type did make a difference in price with condos, villas and bungalows being most expensive and dorms and campers being least. 
2. Having privacy (entire home/apt) had a high premium
3. More beds did lead to a higher price, but a lower price per bed
4. The year someone started hosting didn't have much impact on price
5. Higher ratings did generally mean higher prices, but this was a weak relationship

## Challenges 
The biggest challenges with this project were that it's difficult to figure out where to start on a dataset if you have no clear goals, but this does let you get creative and force you to learn the dataset to figure out what to do. The second challenge is that Tableau can be a bit clunky when it comes to data manipulation, so sometimes its easier to just make edits in Excel or Python

## Future Goals
If I had more time, it'd be great to see if theres any historical data to track prices over time, or even to look at other cities and see how they compare. It would also be interesting to dig into some of the other datasets and give those a try.
