# UFOs
Module 11
## Challenge

### Background
The webpage and dynamic table Dana has built are working as intended, but Dana has decided she would like the table to be filtered even further. While it currently filters by the date, she would like to include the ability to filter by more column headers. The ability to pinpoint a search by date and country, for example, would go a long way in providing more in-depth analysis of UFO sightings.

### Objectives
The goals of this challenge are for you to:

- Create, update, and deploy JavaScript functions to provide additional table filters.
- Update and deploy forEach (for loop) to loop through the filters and update them with user input.
- Update and populate the dynamic filters and table using JavaScript and HTML.

### Instructions
Include five total filters in the table:

Date
City
State
Country
Shape
To create these additional filters, keep the following points in mind:

You will need to create a new function that will replace your handleClick(); function. This function saves the element, value, and the id of the filter that was changed.
Create an if-else statement to add filter data from input, or clear the filter if no input data exists.
Additionally, create a function named filterTable(); that will perform the following actions:
Set the filtered data to the table.
Loop through all of the filters and keep any data that matches the filter values.
Rebuild the table by calling the buildTable(); function created earlier.
Finally, using d3.selectAll();, attach an event listener to pick up changes that are made to each filter.

### Analysis

#### Final Code
