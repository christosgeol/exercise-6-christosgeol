# Exercise 6 - Data analysis with Pandas

In this week's exercise we will continue developing our skills using Pandas to analyze climate data.

After making your changes, you will need to upload your changes to GitHub.
The answers to the questions in this week's exercise should be given by modifying the document in the requested places.

If you are uncertain about **the style of your code**, take a look at the **[PEP 8 - Style guide for Python code](https://www.python.org/dev/peps/pep-0008/)**.  

 - **Exercise 6 is due by 16:00 on 17.10.**
 - Don't forget to check out the [hints for this week's exercise](https://geo-python.github.io/2018/lessons/L6/exercise-6-hints.html) if you're having trouble.
 - Scores on this exercise are out of 20 points.
 - There are altogether 4 problems that you should solve. The fifth problem is optional (Problem 2.1) for more advanced students (does not affect grading)

## Data

For problems 1-3 in this exercise we will be using climate data from the Helsinki-Vantaa airport station.
For these problems, we have daily observations obtained from the [NOAA Global Historical Climatology Network](https://www.ncdc.noaa.gov/cdo-web/search?datasetid=GHCND).
The file was downloaded using the "Custom GHCN-Daily Text" output format, including following attributes:

| Attribute                | Description                      |
|--------------------------|----------------------------------|
| `STATION`                | Unique ID of the weather station |
| `ELEVATION`              | Elevation of the station         |
| `LATITUDE` , `LONGITUDE` | Coordinates of the station       |
| `DATE`                   | Date of the measurement          |
| `PRCP`                   | Precipitation                    |
| `TAVG`                   | Average temperature              |
| `TMAX`                   | Maximum temperature              |
| `TMIN`                   | Minimum temperature              |

The file for this problem is exactly as available from the NOAA website. You can take a [look of the data](data/1091402.txt).

**Note**: once again that temperatures in this dataset are given in degrees Fahrenheit.

Additional information about the data format can be found in the [hints for Exercise 6](https://geo-python.github.io/2018/lessons/L6/exercise-6-hints.html).

## Problems

This week we have 3 problems + 1 optional problem.

 - Start working with Exercise 6 by opening [Exercise-6-problems-1-3.ipynb](Exercise-6-problems-1-3.ipynb)
 - Start working with optional problem by opening [Exercise-6-problem-4.ipynb](Exercise-6-problem-4.ipynb)
