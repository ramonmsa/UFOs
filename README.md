# UFOs Analysis
## Overview of Project

The purpose of this project is to provide a webpage containing a dynamic table where the users can filter the UFO sightings by multiple criteria at the same time. 

The data may be filtered by: 
- Date
- City
- State 
- Country 
- Shape

## Results

### Filter functionality 

As it can be observed, the filter bar does not contain any button to apply the search, instead the filter in the webpage works by an event listener which identify any change in the value of a field in the search bar. 

![Search Bar](https://raw.githubusercontent.com/ramonmsa/UFOs/main/Resources/search_bar.PNG "Search Bar" ) *Search Bar*

### How to use the filter and perform a search
- In each input field enter the information wanted to search for
- After typing the information in a field, press the __*Tab*__ key in order to the cursor to jump to the next input field.
  - By doing this, the search engine will return into the table the data filtered by the information inserted .
- When there is no more input field to jump to, simply press the __*Enter*__ key to apply the changes in the filter, then the table will reflect the information entered in fields from the search bar 

![Usage of The Search Bar](https://raw.githubusercontent.com/ramonmsa/UFOs/main/Resources/usage_search_bar.PNG " Usage of The Search Bar" )
*Usage of The Search Bar*


## Summary

A design decision to be reconsidered is the __*Filter Search*__ to be presented in this design as a side bar which take out horizontal space from the data table.

In addition, there are two features that could be included in order to provide a better user experience: 
 - To include input controls that could let the user easily select the date and select the word from a preloaded list as the user types.
 - To implement pagination in the data table when the search returns a large amount of data.

