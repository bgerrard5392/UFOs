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
**UFO Sightings in New York** 

Let's say a user is looking for UFO sightings in New York, they can simply type "ny" in the state filter, press enter, then the table updates so it displays all UFO sightings that took place in ny (see below).

![ny_filter](https://user-images.githubusercontent.com/75700317/120046190-a8784a80-bfdf-11eb-9c34-7d22811946f1.png)


**Rectangular shaped UFO Sightings in AZ** 

Let's say a user wants to know if there has ever been a recatangular shaped UFO sighting in AZ. To do so they would simply enter "az" in the state filter field, "rectangle" in the shape field, then press enter to display the UFO sighting they were looking for (see below).

![rectangle_az](https://user-images.githubusercontent.com/75700317/120046728-d14d0f80-bfe0-11eb-95ab-1a5488b4149b.png)









## Summary
This webpage turned out to be effective and easy to use. One drawback I found that could be improved upon is it's filter refresh capabilities. There currently is no refresh option if you look to make multiple searches. After performing one search, the only way to reload the entire table is by refreshing the entire webpage. This is an action that can be upgraded by simply adding a refresh button to the java script. That was a user can make multiple searches with ease. 


To imrpove the capabilties of this webpage in the future I'd recommend the following: 

1) Update the data set to include UFO sightings from around the world. We already built a "country" filter option that is currently redundant b/c this data only contains US sightings. By adding international data to this dataset, this will enhance the experience for users. 
2) Drop down filter features - giving the users a view of the filter criteria options will make filtering exponentially easier for the user. 
3) Export capability - having the option to export a filtered data table is a huge feature that enables the user to easily share the data they were looking for.  



