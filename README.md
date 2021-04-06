# python-api-challenge

**Background**

This project's purpose was to answer the question: What's the weather like as we approach the equator? While the initial answer is, "it gets hotter," I was tasked with proving it. 

**Tools Used**

1. Python
2. API
3. JSON

**Project Tasks**

In part one of this project (WeatherPy), I was tasked with creating a Python script to visualize the weather of 500+ cities around the world with varying distance from the equator. I started by looping through the list of cities, randomly selecting 500 of them, and performing a request for data stored at each API point before storing the data in a list. 

(insert data image)

Next I created a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

![](https://github.com/erinmann12/python-api-challenge/blob/main/WeatherPy/Images/LatTemp.png)

The next step was to run a linear regression on each relationship by separating the plots into Northern Hemisphere and Southern Hemisphere.

![](https://github.com/erinmann12/python-api-challenge/blob/main/WeatherPy/Images/SouthLatTemp.png)