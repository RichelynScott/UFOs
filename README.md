# Mod 11 – JavaScript - Dynamic Content W/ Bootstrap & CSS 
## UFOs
### Overview of Analysis 
The purpose of this analysis was to build a webpage that housed a large dataset of UFO sighting around the world. The data is displayed by a dynamic table that we even created the ability to be able to filter through this large dataset by date, city, state, country, and/or shape. The website was built using JavaScript, HTML, and Bootstrap and uses data stored in a JavaScript array to build the dynamic table that filters based upon user selected criteria of the above forementioned filters.
### Results
-With the data provided of the UFO database (data.js) the webpage created makes traversing that data much easier to digest and more visually appealing to sift through and interact with as well. Upon reaching the landing page the user is greeted by an overview of the page and its purpose with the filterable table below that.
![UFO Landing Page](https://github.com/RichelynScott/UFOs/blob/main/static/images/UFO%20Landing%20Page.png)
-The 5 filters are on the left side of the page as data displays in the remaining middle and right side of the page to the right of the filters. As mentioned earlier, you can filter by 1 field or all 5 to get the desired data to display from the data.js file. In our example below we only searched for all UFO sightings within this data that occurred on 1/6/2010, the table then returned to the user (us) the 3 UFO events that we had amongst our dataset displaying for each the date, city, state, country, shape, duration, and comments on the event. 
![UFO Filter at Work](https://github.com/RichelynScott/UFOs/blob/main/static/images/UFO%20Filter%20at%20Work.png)
Pretty nifty!
### Summary

The goal of this analysis was to build the webpage with a dynamic table that can be filtered to return JavaScript objects which contained 7 elements to be cleanly displayed in the html table. The project was a success but one drawback is the specificity of user-inputted filters required to return appropriate data. If a user misspells one of the filters, has the improper use of case (as the search/filter is case sensitive), or does not know what options they have the user will be left with a blank table as their filtered search will not match any criteria of the dataset/array/JS object. One recommendation to improve this webpage would be to make the search/filter options not case sensitive and attempt to help users with an autofill to help navigate users to appropriate data. Another recommendation would be to offer a dropdown menu along with the search function to offer users an optimal experience when attempting to search or filter the data by specific criteria. 

