# Bikesharing

## Project Overview
Using the Citi Bike dataset, an analysis is performed on the feasability of applying a bike sharing program in Des Moines, Iowa. The New York City's 2019 August data is broken down into 3 main categories of the market: age, gender, and time. Based on these categories, visualizations are created using Tableau Public to suit the analyst's perspective as well as any future investors of the program. All of the charts are uploaded on the Tableau Server to be shared. 


## Resources
Data: 201908-citibike-tripdata.csv, citibike_data_converted.csv

Software: Tableau 2021.1, Jupyter Notebook 6.2.0

## Results
Interactive Charts on Tableau Server: https://public.tableau.com/profile/ryan.nasara#!/vizhome/CitiBikeAnalysis-NYC/CitibikeNYCAnalyis

- The trip duration mostly lasted less than an hour with its peak of 5 minutes per ride. Out of the 2,344,224 rides in August 146,752 lasted 5 minutes. 
- The checkout times divided by gender shows the same trend for all male and female peaking at 5 minutes per ride while the unkown category peaks at 10 minutes per ride. 
- The peaktimes for the month of August can be divided into morning and afternoon times, where the morning peak hours is between 8 to 9 am and the afternoon starts at 4 to 7pm. 
- The heatmap divided by the days and time shows the same result for the peak hours during the weekday however, during the weekend shows a more steady time between 9am all the way to 7pm. 
- The heatmap breakdown is further broken down between all genders and it shows consistency amongst the results above across the board whether it is male, female, or unknown.
- There is an overwhelming amount of Male service subscribers compared to female and unknown while unknown genders tend to be one time customer instead of a subrscriber. 
- The last dashboard of the story is a summary of the analysis between all three categories. This shows that there is a much higher number of males than all the other gender. There is a more consistent base of customers that are born after the 70's and into the 2000's however there are still spikes of older age customers that have much higher trip duration than average. The busiest day is sunday with 408,622 rides.

## Summary
The snapshot of New York City's data during August 2019 is a good start to what potentially Des Moines can be in terms of its bike sharing program. From the data, mos of New York's regular subscribers are male and are travelling during weekdays. This is suspected to be used as a mode of transportation for work rather than used by tourists to get around. This is the biggest reliable market that Des Moines can target to grow the program with especially with its fast growing city for office workers. The other target could also land for city residents goign around the city's vast cultural ammenities such as its botanical gardens, farmer's market, and sculpture parks. Although this data is a good start to what Des Moine's bike sharing program could be like, there are a few more kew information that might be useful for investors. The following analysis should be performed by gathering the average lifespan of the bike before needing a service and mapping popular bikeroutes based off of the start and end location of the rides.


To see individual worksheet:
[link to dashboard] https://public.tableau.com/profile/ryan.nasara#!/vizhome/CitiBikeAnalysis-NYC/NumberofRides
