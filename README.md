# PyBer_Analysis
Analyze and visualize ride-sharing data using the power of Python, Pandas, and Matplotlib

## Project Overview

Analyzing company profits and customer demographics for a ride sharing app:

1) A bubble chart that showcases the average fare versus the total number of rides with bubble size based on the total number of drivers for each city type
2) The mean, median, and mode for the following:
    - The total number of rides for each city type.
    - The average fares for each city type.
    - The total number of drivers for each city type.
3) Box-and-whisker plots that visualize each of the following to determine if there are any outliers:
    - The number of rides for each city type.
    - The fares for each city type.
    - The number of drivers for each city type.
4) A pie chart that visualizes each of the following data for each city type:
    - The percent of total fares.
    - The percent of total rides.
    - The percent of total drivers.
--- 
## Resources

Data Sources:
city_data.csv
ride_data.csv

Software:
Python 3.7.1
Pandas 0.25.2
Matplotlib 3.1.1

## Summary
![RideSharingData](https://user-images.githubusercontent.com/82069038/119250098-c2430900-bb6b-11eb-8752-42ae6c593219.png)
![Fig2](https://user-images.githubusercontent.com/82069038/119248887-2cef4700-bb62-11eb-981a-7205ec4cc15d.png)
![RideFareData](https://user-images.githubusercontent.com/82069038/119249859-151bc100-bb6a-11eb-9344-d8e37371f550.png)
![DriverCountData](https://user-images.githubusercontent.com/82069038/119249822-c837ea80-bb69-11eb-91a7-bd7d67d992bd.png)
![Fig5](https://user-images.githubusercontent.com/82069038/119248888-2cef4700-bb62-11eb-8763-5c2c2cb9f7b5.png)
![Fig6](https://user-images.githubusercontent.com/82069038/119248889-2d87dd80-bb62-11eb-9f53-bfb5ff363f32.png)
![Fig7](https://user-images.githubusercontent.com/82069038/119248890-2d87dd80-bb62-11eb-8aad-21fa74bfacd9.png)
         
         See PyBer.ipynb for summary statistics

--- 
## Challenge Overview

Providing a summary table of key metrics. Including, ride-sharing data / city type, and a multi-line graph indicating average fare / week / city type.

## Challenge Summary

### Summary DataFrame
Findings show great amounts of business conducted in urban cities, in comparison to suburban or rural (4-10x number of rides, & 5-30x number of drivers). 
Furthermore, the average fares are the lowest for drivers and rides in urban cities (indicating shorter duration, & cheaper trips in urban areas -  as well as the high volume of drivers, & less earned $ on average in comparison to rural and/or suburban data).

### Multiple-line Graph
Showing trends across city types: Urban, outrighly accounting for the most expensive fares, followed by suburban, and lastly rural. 
The city types do appear to mirror eachother with perhaps a passive relationship (rising and plateauing in similar fashion Jan - Apr).

### Implications
Indicates a solid visual represenation of what may be socioeconomic bracketing / city type. 
While there are no intersectional point between the difference city types, their trend lines move in unison through time - giving us a vague interpretation, but an insight nonetheless (that we could absolutely look further into if prompted), to macro-economic conditions & factors which may play a role in market volatility (fare$). 
