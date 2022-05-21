# World Weather Analysis

## Overview
The purpose of this assignment is to use API access to two websites in order to:

    - receive a list of hotels in certain cities that fit our temperature requirements
    - create a visual map which displays the hotel, city, and weather information according to our temperature criteria
    - create an itinerary between 4 locations

## Challenges
Certain issues I ran into while completing the assignment:

    - Cleaning up as much data in the CSV file and dropping all the rows where there were no hotel names. I have tried to first replace the "None Type" values in the cells with np.nan and the apply the dropna function, but program refuses to apply the replacement.

    - API calls for info on 2000 cities can take a while. It is important to make sure that the code runs properly on fewer api calls (like 100 api calls) in order to quickly check for results.

    - Incorrectly accessing an attribute within a JSON file can return an error from the request and cause the computer to execute the "except" block of code in the "try-except" block.