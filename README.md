# Citi Bike Analysis


This research was conducted on Citi Bike Trip Data from January 2018 through June 2020.  The data files were downloaded from https://www.citibikenyc.com/system-data.

The files contained data on nearly 46.5 million trips.  This data was cleaned and summarized using Pandas and two files were generated.  One file contained information for the stations and the second file contained trip summary data.  These files were used in Tableau to create data visualizations.

Two areas were analyzed to determine trends and impacts.  Round trips, defined as trips that begin and end at the same station, were analyzed to determine popular days of the week and months of the year for round trips.  Trip duration for round trips was also compared to the duration of one way trips.  A second area of research was the impact of COVID-19 on the number of trips completed.

There were some interesting findings from the analysis.

In the time period studied, round trips only accounted for 2.5% of all trips.  Two expected findings were that each weekend day had 1.5 times more round trips than weekdays.  Not surprisingly round trips were higher from April through September.  Possible reasons for this include more time for recreation on weekends, improved weather conditions starting in April, and additional tourists visiting NYC in the summer months.

In each of the 30 months included in the research, trip duration was longer for round trips than one way trips.  This difference was higher in April through September by 9-10 minutes per trip.  During the colder months round trip duration was still longer but only by 2-3 minutes.  One way trip durations were more consistent through out the year with trips in the colder months averaging about 12 minutes and 15 minutes in the warmer months.

One other aspect of round trips is the location where they occurred.  By generating a map of all the stations and using size and color to identify the stations with the most round trips, it was clear that a few locations were very popular.  These locations were Central Park, Prospect Park, West Side Highway, Governors Island, and Liberty State Park in NJ.  Again, this suggests that round trips are mostly for recreation.

Research on the impact of COVID-19 revealed a significant decrease in the total number of trips in April of 2020 from 1.75 million to 633k.  In both 2018 and 2019, April had large increases in the number of rides compared to March so this indicates the impact of COVID-19.  In May and June of 2020 the total number of rides did increase but not to the level of prior years.

The most interesting finding was the impact of COVID-19 on round trips.  In April of 2020 there was a 42% increase in the number of round trips from 40k to 57k compared to April 2019.  In May the increase in round trips was from 45k to 120k and June went from 56k to 133k.  Trip duration increased in April - June 2020 for both one way and round trips.  One way trips were from 21 to 23 minutes and round trips were 34 to 39 minutes.  

Since tourism was not as robust as usual, the research on round trips during COVID-19 indicates that local New Yorkers were seeking recreation as a way to manage themselves during this period. Prior to April 2020, the greatest number of round trips in any month was 61k in August of 2019 and this was doubled in each of the last 2 months.  The increase in the number of round trips and the average length of each trip clearly shows a relationship.

