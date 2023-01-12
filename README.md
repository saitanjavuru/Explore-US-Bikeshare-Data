# Explore US Bikeshare Data

Udacity Programming for Data Science with Python - Python Project

### Overview
In this project I used Python and Python libraries such as NumPy and pandas to explore data related to bike share systems for three major cities in the United States - Chicago, New York City, and Washington. I wrote code to import the data and answer interesting questions about it by computing descriptive statistics. The script also takes in raw input to create an interactive experience in the terminal to present these statistics.

### Files used
The csv data sets I used (chicago.csv, new_york_city.csv, and washington.csv) were provided by Motivate, a bikeshare system provider for many major cities in the United States.

### The Datasets
Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core **six(6)** columns:
* Start Time (e.g., 2017-01-01 00:07:57)
* End Time (e.g., 2017-01-01 00:20:53)
* Trip Duration (in seconds - e.g., 776)
* Start Station (e.g., Broadway & Barry Ave)
* End Stattion (e.g., Sedgwick St & North Ave)
* User Type (Subscriber or Customer)

The Chicago and New York City files also have the following two columns:
* Gender
* Birth Year

### Statistics Computed
1. Popular times of travel (i.e., occurs most often in the start time)
* most common month
* most common day of week
* most common hour of day

2. Popular stations and trip
* most common start station
* most common end station
* most common trip from start to end (i.e., most frequent combination of start station and end station)

3. Trip duration
* total travel time
* average travel time

4. User info
* counts of each user type
* counts of each gender (only available for NYC and Chicago)
* earliest, most recent, most common year of birth (only available for NYC and Chicago)