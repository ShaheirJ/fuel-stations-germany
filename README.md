# Fueling Up in Germany: A Look at Petrol Station Brands &amp; Prices

This analysis explores trends and variations in petrol station prices across Germany from 2014 to 2023. By analyzing data on fuel types like diesel, E5, and E10, we aim to uncover insights into:

- How do national average prices for different fuel types change over time?
- What petrol station brands are the most dominant in the market?
- Are there significant price differences between states or cities?
- How do the average prices of diesel, E5, and E10 compare to each other?

## Data Source
[German petrol station data](https://www.kaggle.com/datasets/oles04/petrol-station-germany)

## Tableau Storyboard

[German Petrol Station Analysis](https://public.tableau.com/views/FuelingUpinGermanyALookatPetrolStationBrandsPrices/PetrolStoryboard?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)

## Approach

- The datasets are split into year for the diesel, E5 and E10 prices for every month from 2014 to 2023. Another dataset has the details of every petrol station (address, opening hours, brand, etc).
- However, the state column was missing and I added the state column by merging the postcode with a json file containing all German cities and their postcodes.
- These datasets were cleaned and wrangled using Python.
- Some machine learning methods (linear regression & clustering) were also made (in the Scripts folder).
- However, these machine learning processes were not included in the [Tableau Storyboard](https://public.tableau.com/views/FuelingUpinGermanyALookatPetrolStationBrandsPrices/PetrolStoryboard?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link) as the storyboard was made for a more narrative approach.
