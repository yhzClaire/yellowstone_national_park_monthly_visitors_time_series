# yellowstone_national_park_monthly_visitors_time_series
Time Series Analysis on Yellowstone National Park Monthly Visitors

See [R Markdown file of this project](https://yzclaire.github.io/yellowstone_national_park_monthly_visitors_time_series/)

# Problem Statement 
To identify patterns and trends of monthly visitors to Yellowstone National Park and forecast next 12-month visitors

I was very lucky to have a chance to visit the Yellowstone National Park with a friend during the week of July 4th, 2019. I had such a wonderful experience visiting Park. I remember how much I enjoyed walking around the park and seeing those beautiful and colorful hot springs and geysers basins, and how excited I was when we  run into our natural friends, bisons and deers, multiple times. 

The park is open to the public 24/7 all year round. Every year there are more than 4 millions visitors to the Park, and number is growing year by year(might not held true for 2020 due to Covid). It would be great if we can make up-to-date forecast of visitor volumn to help the park service team to better plan and allocate resources. Being able to predict visitor volumn will help us not only plan for construction and/or maintaining of roads, lodges and campgrouds, but also reserve time for recovery of the Park. Ultmiately we hope to preserve the ecosystem (the natures and wildlife) and sustain the beauty of the Park to all visitors for many generations to come. I had a chance to work with a team to perform time series analysis on number of monthly visitors to Yellowstone National Park and build machine learning models to forecast next 12 month's number of visitors.

# Hypothesis:
* There are time-related trends in the number of visitors to Yellowstone National Park.
* Number of visitors to YNP might also affected by temperature and oil price.

# Data Source:
* Monthly Visitors to Yellowstone Nation Park: [Integrated Resource Management Applications (IRMA)](https://irma.nps.gov/STATS/SSRSReports/Park%20Specific%20Reports/Recreation%20Visitors%20By%20Month%20(1979%20-%20Last%20Calendar%20Year)?Park=YELL)
* Month Temperature: [National Center for Environmental Information ](https://www.ncdc.noaa.gov/cdo-web/)
* Gas Price: [U.S. Energy Information Administration](https://www.eia.gov/totalenergy/data/browser/index.php?tbl=T09.04#/?f=M&start=197911&end=202001&charted=5-10-11)
