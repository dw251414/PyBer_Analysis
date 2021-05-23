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
## Resources

Data Sources:
city_data.csv
ride_data.csv

Software:
Python 3.7.4
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


Challenge Overview

Need to create an overall snapshot of the ride-sharing data. In addition to the scatter and pie charts, a summary table of key metrics of the ride-sharing data by city type and a multiple-line graph that shows the average fare for each week by each city type are required.

Challenge Summary

Summary DataFrame
The datashows that urban cities do significantly more business than suburban or rural cities based on the the 4-10x number of rides and 5-30x number of drivers in urban cities compared to rural and suburban ones. It's also interesting to note that the average fares are the lowest for drivers and ride in urban cities. This shows that trips are shorter/cost less in urban areas and that due to the high number of drivers, each employee makes less on average in urban cities compared to rural or suburban ones.

Multiple-line Graph
The graph shows a very consistent trend across the different city types. Urban cities consistently bring in the most money, followed by suburban ones, and finally rural cities. The plots vaguely mirror eachother with all three dropping their total fares in March before peaking mid-late February.

Implications
The line graph clearly shows the different brackets of each city type's total fares. There are no parts of the graph close to intersection. However, the lines do follow similar trends through time which reflects the similarities between city types despite the total fares being different magnitudes.
