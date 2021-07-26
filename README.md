# Bike Sharing Analysis

## Project Overview
Kate has recruited me to analyze Citibike data in New York City, dated from August 2019, to best assess how to best deploy the same level of amenities in Des Moines, IA, namely bike-sharing services.

## Resources
- Data Sources: 201908-citibike-tripdata.csv
- Software: Python 3.9.4 via Anaconda Jupyter Notebook, Tableau Desktop Public Edition 2021.2.0 (20212.21.0605.1023) 64-bit

## Results
What I was able to discover was the following:
-Most Citibike activity as of August 2019 is concentrated in the central business district, which could be due to a decision to deploy Citibike in that general area first before radiating outward to further areas of New York City, as evidenced by its heavy concentration all around the southern one-third of Manhattan (south of 59th St.,) moderate concentration along the middle one-third of Manhattan (between 59th St. and 125th St.,) and nothing north of that point save for faint concentrations found in the Bronx.  Concentrations of medium intensity were found all along Williamsburg and in Downtown Brooklyn along Brooklyn, as well as lower-concentration areas as far southeast as Park Slope, as far northeast within Brooklyn as Bushwick and a few just into Ridgewood, Queens, and as far north as along Long Island City and Astoria in Queens.  Citibike usage of similar low density was deteceted on Governors Island in the borough of Manhattan as well.
-The majority of Citibike users used their bicycles within 15 minutes.
-An overwhelming number of Citibike users are male.  At its peak, over 108,087 male users used Citibike for 5 minutes, compared to 34,151 female users for 6 minutes.
-Peak hours for Citibike usage fell between 7 AM and 10 AM and between 4 PM and 8 PM on weekdays, between 10 AM and 7 PM on Saturdays, and between 12 PM and 6 PM on Sundays, but a noticeable drop in activity during Wednesday afternoons was found.
-Rates of Citibike usage by gender during the day were observed to be about the same, notwithstanding differences in absolute numbers.
-Out of a quadrant matrix arrayed by gender and user type, male subscribers were observed to be the most frequent users of the Citibike service.  Female customers, by contrast, were the least frequent users of the Citibike service.

These results were obtained from the following series of graphs shown here:
[Link to Tableau dashboard](https://public.tableau.com/app/profile/jose.pascual3206/viz/CitibikeAnalysis_16272662260130/CitibikeAnalysis?publish=yes)

## Challenge Summary
My conclusion is that while the current usage of Citibike is due to New York City's status as the largest city in the country but tempered by the lack of universal access throughout the city within the timeframe analyzed, we can nonetheless scale downward to better model the needs of Des Moines.  To that end, I find that we can deploy bicycle access to Des Moines, provided that it be deployed along similar per-capita rates as that as New York City, which would equate to about 1/40th as many bicycles to be deployed in Des Moines as has been deployed as New York City as a baseline, then adjusted in response to actual usage.  Also, subscription packages should be deployed and promoted to further stimulate usage, as well as aiming advertising at a male demographic to best guarantee success of this service.  In short, provided that it is scaled properly, extending bike-sharing services to Des Moines is an initiative worth pursuing.
