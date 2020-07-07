# PyBer_analysis
## Background and Results

Analysis of totals for PyBer ride sharing. Specifically analyzed are:

    Total rides
    Total Drivers
    Total fares
    Average per fare
    Average fare per driver
    
Through analyzing these metrics, we can show net earnings per driver, and for each fare.

Also within the analysis is a breakdown of time, showing utilization rates during a defined time period.

### Purpose

  The purpose of this analysis is to identify trends within each of the three identified city types, Urban, suburban, and rural. this allows for identification of trends as to the fares that each type of environment is earning.

### Technical Analysis

  In order to achieve the desired breakdown, two CSV files were utilized:
    - city_data.csv which identifies the city name, the type of city, number of drivers in each.
    - ride_data.csv which breaks down the individual rides which includes, ride id, fare, city, and date.

   Merging the two datasets allows for the ride data to be built into one unified dataframe and subsequently broken down into a usable product. Further breaking down the dataset, a new dataframe was built to show the five previously identified (review under analysis above) data points, the result is shown in fig 1. below.
    

![FIG 1.](https://github.com/ChrFoley/PyBer_analysis/blob/master/Analysis/Summary_breakdown.PNG) 

   Looking at the totals for rides, drivers, and fares, it is seen that urban areas had much higher total, with suburban in the middle, and rural areas with the least utilization. This is not unexpected as urban and suburban areas have higher population densities. Conversely looking at the averages rural rides earned a higher fare, and the average per driver was higher. This could be due to multiple reasons including the length of the ride, or the cost per mile of the fare. 
   
   The chart (fig 2.) below breaks down the ride share services offered by PyBer from the beginning of January 2019, through the end of April 2019, looking at the same three city types, urban, suburban and rural. 
 
 ![FIG 2.](https://github.com/ChrFoley/PyBer_analysis/blob/master/Analysis/PyBer_Challenge_fare_summary.png) 
 
   Easily seen in this chart is the fact that each city type shows correlation with population density and the amount earned in total fares. for both the urban and suburban types there is a discernible increase throughout the time period, while ride totals in the rural areas remained relatively constant. 
     

### Results

   results from this initial data analysis show that while there are lower densities of rides and drivers in rural areas fares and drivers fare averages where significantly higher in these rural areas. This primarily shows  Driver density does not mean that there is higher rates for fares or driver fares. Ultimately to determine each profit margin, the data set needs to be expanded and more data added including mileage per ride, time a driver is dedicated, and time a driver is idle or not being utilized.

### Challenges and Difficulties Encountered

* Programming
    Merging data frames has become relatively simple in execution. the hurdle is simply figuring out how the data should be merged, then grouped. overall this was a great exercise for repetition of those skills. 
    
    Creation of the chart didn’t seem daunting at first, and took multiple attempts. setting the indexes etc. were not inherent, but through the documentation, stack overflow they were solved.

* Data analysis

    understanding the boundaries of the data and the skills that have been taught the data set was fine. but a true analysis of the P/L utilization, profit for time dedicated is not possible. that said the exercise was great in regards to repetition.


## Recommendations and Next Steps

### Recommendations for Future Analysis

  Look at utilization rates, how often each driver is active
  look at the population, what percent uses ride share, drivers as a percent of population
  look at the cost of the fare, compared to miles traveled
  look at daily times to see when the ride service was utilized most
  Look at the length of time a driver was dedicated with a fare
  identify the number of repeat users and new users, including frequency of use.



