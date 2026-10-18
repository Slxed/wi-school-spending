# Wisconsin Public School Spending vs. Graduation Rates (2023-24)

![Map of Wisconsin school districts comparing spending per student and graduation rate](map/wi_spending_vs_graduation.png)

My main question when creating this map was how correlated the actual per-student spending was to real outcome on graduation rate. Due to my background working for a school district, and having close family working in that same public school I thought it would be interesting to explore further.

## What I did

I used Wisconsin DPI data for the 2023-24 school year, covering 421 districts. The district boundaries came from the basemap we used in a GEOG 370 lab.

- Merged a combination of 5 excel spreadsheets into a solid list of columns that provided what I needed
- Cleaned the spending and graduation tables and joined them by district in Python and SQL
- Joined that to the district boundaries in ArcGIS Pro
- Made a bivariate choropleth so both variables show up on one map
- Used USA Contiguous Albers Equal Area Conic (central meridian -90, standard parallels 43N and 47N) so district sizes aren't distorted
- Finished the layout in Illustrator

## What I found

The average graduation rate across districts was 68.8%, and average spending was $18,865 per student. Spending more didn't guarantee a higher graduation rate. Lac du Flambeau #1 spent $39,708 per student and graduated 57%, while Merton Community spent $12,624 and graduated 94%. That pair was the most striking thing on the map for me. Overall there's a lot of variation from district to district, so the statewide averages don't tell you much on their own.

## Files

- `map/wi_spending_vs_graduation.png`: preview of the map
- `map/wi_spending_vs_graduation.pdf`: full-resolution version

Map by William Day, April 2026. [LinkedIn](https://www.linkedin.com/in/william-day-5b73112bb)
