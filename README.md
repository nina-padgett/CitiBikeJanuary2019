# Citi Bike: NYC January 2019

Among the expansive public transportation network of subways and buses, New York City also offers its residents and visitors a public bike share system known as Citi Bike. Citi Bike collects data of each of their bikes, including start and end points, duration of use, distance traveled, gender and age. This data is collected monthly and provided to the public at:

https://ride.citibikenyc.com/system-data. 

There were a few abnormalities in the data that were removed prior to analyzing the data in Tableau. For example, in 2019, the oldest person living in the United States was 114 years old, so I removed birth years 1886-1901. This removed "riders" oldler than 114. I dropped of all of the NULL values in the 'start station id' column, and I also dropped the trip distances equivalent to zero. These "rides" may have been created due to false starts. 

Once the data was cleaned, I uploaded the new .csv to Tableau. Visualizations were developed and split into two categories: Trip Statistics and Demographic Statistics. I found the total trips taken in January was 951,003. Being an outsider, nearly one million trips may sound like a large number. Considering January is one of the coldest months of the year and NYC had a population of nearly 8.5 million people in 2019 according to the U.S. Census Bureau, this amount was low. Many of these riders either began or ended their trip at the Pershing Square North station. This station is just outside Grand Central Station. The average distance traveled was one mile. The average trip duration amounted to 12 minutes and 41 seconds. And 96% of Citi Bike's riders are subscribers. 

In terms of demographics, I found that the average consumer age was 39 years old. Male versus female ridership age was nearly evenly split. The percentage of male and female riders were nearly the same as well. The number of riders who did not disclose their gender were a larger group than either male or female. The unknown group had an average age of 47.

Each of these findings are displayed in the following Tableau story. 

https://public.tableau.com/app/profile/nina.padgett/viz/CitiBikeNYCJanuary2019/Story?publish=yes
