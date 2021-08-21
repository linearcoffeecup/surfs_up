# surfs_up

# Overview

For this project features were exercised which combined Python with the SQLite database capabilities.  Through "sqlalchemy" it was possible to combine datbase queries with dataframes, series, statistical analysis, and plotting.  The SQLite features "create_engine" and "session" make the link between Python and the database.  This link can be used for databases other than SQlite.

## Insights

* One difference between June and December temperatures is that the temperature of 71 degrees occurs at the 25 percentile for June and at the 50 percentile for December.  This means that there are about twice as many days with this temperature in June compared to December.

* Another difference is that December has a smaller number of temperature measurements and a slightly greater standard deviation.  Perhaps temperatures are not recorded as frequently in December as in June.

* Also, the obvious difference is that December temperatures are lower than June temperatures.  

## Summary

There is no significant variation in temperature data.  This is further evidenced by looking at the mode using the scipy.stats for which the mode was the same as the median for both months which occurred the same number of times.  In addition, a box plot comparison of temperature versus month shows no variation.  Each month has 8 outlier temperatures.  


