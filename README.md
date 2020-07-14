# SQLAlchemy Exercise - Weather in Hawaii

This exercise is a climate analysis on the Honolulu area.

![View of Honolulu, image retrived from Royal Hawaiian Movers on 07/13/2020](https://www.royalhawaiianmovers.com/wp-content/uploads/2016/01/honolulu-pano-downtown-blog.jpg)

## Data

The dataset can be found [here](hawaii.sqlite) and it contains 2 tables, called Measurements and Stations. This SQLite file contains information from 2010-01-01 to 2017-08-23 for 9 stations.

### Objective

* Analize the last 12 months of precipitation data.
  * Plot data.
  * Describe it.
* Analize the stations information.
  * List of stations with data points.
  * Information about the most active station.
  * Plot histogram with data from the most active station.
* Vacation exploration.
  * Generate function to retrive min, max and average temperatures from vacation start and end dates.
  * Plot results
  * Generate table with station information from last year vacation dates.
  * Calculate the daily normals of the trip with min, mean, and max temperature.
  * Plot results
* Create an API endpoint to call some of the previous queries.

## Results

* Analize the last 12 months of precipitation data.
  * Plot data.

    ![prcp last 12 months](images/prcp_12months.png)

  * Describe it.

    ![description prcp last 12 months](images/prcp_desc.png)

* Analize the stations information.
  * List of stations with data points.

    ![Stations by data points](images/data_stations.png)

  * Information about the most active station.

    ![Most active](images/most_active.png)

  * Plot histogram with data from the most active station.

    ![Histogram with Most active](images/histogram.png)

* Vacation exploration.
  * Generate function to retrive min, max and average temperatures from vacation start and end dates.

    ![Vacation](images/func_vac.png)

  * Plot results

    ![Trip values](images/trip.png)

  * Generate table with station information from last year vacation dates.

    ![Last year](images/last_year.png)

  * Calculate the daily normals of the trip with min, mean, and max temperature.

    ![normal](images/normal.png)

  * Plot results

    ![Plot normal trip](images/normal_plot.png)

* Create an API endpoint to call some of the previous queries.

  ![Deployed site](images/deployed_site.gif)

### Copyright

View of Honolulu, image retrived from Royal Hawaiian Movers on 07/13/2020.
