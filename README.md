# Module 11 Challenge: UFO Analysis
We come in peace! This is my module on UFO sightings.

1. Overview of the analysis:

The purpose is well defined (2 pt)
2. Results:

There is a description of how to perform a search, with images. (4 pt)
3. Summary:

The summary addresses one drawback of this webpage (2 pt)
The summary addresses two additional recommendations for further development (4 pt)



## Project Overview
In this module I created a web page for a Data Journalist named Dana using JavaScript's visual functionality to provided a dynamic analysis on UFO sightings around the world. 

With Java Script I was able to build a table where users can filter the UFO sightings data by date, city, state, country and type of sigthting. From there I created an HTML page where I display Dana's article on UFO sightings as well as the table with the easy to use filter.  


## Results
The websites landing page has 3 main attributes:

 - Dana's UFO article 
 - The complete unfiltered data
 - The filter Search box consisting of Date, City, State, Country filter options 

Each filter option contains a "placeholder" or example criteria so the user knows the purpose and functionality of each filter. When you enter criteria into the filters and hit enter, the table adjusts for the search results. I've included examples below on how to operate the filter.

### Filter Examples:
Let's say a user is looking for UFO sightings in New York, they can simply type "ny" in the state filter, press enter, then the table updates so it displays all UFO sightings that took place in ny. 

![ny_filter](https://user-images.githubusercontent.com/75700317/120046190-a8784a80-bfdf-11eb-9c34-7d22811946f1.png)



Let's say a user wants to know if there has ever been a recatangular shaped UFO sighting in AZ. 
![bonita_oval](https://user-images.githubusercontent.com/75700317/120046343-f1300380-bfdf-11eb-9b15-7564997a50ef.png)




Each catergory has an example of the criteria it is looking for. When you enter a certain criteria into one of the catergories and press the enter key, the table will adjust to show you the results for the criteria you entered. For example, if we add "el cajon" into our search, 5 results will appear when I press enter. 





Below is a summary of June's tempature statistics

![June_Temps](https://user-images.githubusercontent.com/75700317/118911505-4723ed80-b8f4-11eb-9ecd-077062801702.png)

Below is a summary of December's temperature statistics

![December_Temps](https://user-images.githubusercontent.com/75700317/118911439-2fe50000-b8f4-11eb-87cc-75478ceeac53.png)




## Summary
One drawback of this design is that the search criteria must match exactly to the data. For example, when the search criteria "ca" is entered there are many results, but if "CA" is entered, then no results populate. It also may be a good idea to add examples or a key of shape examples, as this criteria is not as clear as a date, city or state. 

Two recommendations I would make for further development would be:
1) All of the sightings in our data are from the US, so I would remove that search criteria and replace it with duration. People interested in UFO sightings would probably like to see if the durations in certain areas are similar to one another, and how the duration in one location or on a specific date vary from other locations and dates. 
2) Another development I would look into, is making the text entered different than the example text. This way you still have the example text if you would like to enter another search criteria, but you still identify the criteria you have already entered. Currently all the text looks the same when entered, so it can be difficult to know what the results are filtered on.



The average temperatures between December and June differ by only 4 degrees (75 degrees in June and 71 in December). There is very little fluctuation between the two which leads me to believe that both months are safe to run the shop. In summary, the weather in December and June exhibit similar behavior - the high points in December are relatively close to the weather experienced in June but the low points are significantly lower in December. 

## Additional Queries 
One addition query I would run would include the difference in precipitation between June and December. I would be very interested to see how the precipitation highs and lows track against the highs and lows of rain, is there any difference? Could this help better determine when the Surf n' Shake shop should run? That analysis would provide a "tidal wave" of insights :)

