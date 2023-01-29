# weather_challenge
Weather challenge consists or twp programs:
WeatherPy requests weather data from public APIs for approximately 500 cities of varying distance from the equator. The data is compiled into dataframes, merged and cleaned then analyzed to provide data on how distance from the equator may effects weather patterns and attempts to draw a correlation between the two.

VacationPy draws on the dataframe of cities constructed in WeatherPy and uses that information to narrow down ideal weather conditions for vacationing. After narrowing the field of cities, the program then uses an additional API to pull the nearest hotel to the city, based on the city's geocoordinates.
