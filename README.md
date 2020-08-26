# UFOs

This project asked that we create multiple filters for the UFO sightings database and webpage.  
the following steps were required:
 1. Create, update, and deploy JavaScript functions to provide additional table filters.
 2. Update and deploy forEach (for loop) to loop through the filters and update them with user input.
 3. Update and populate the dynamic filters and table using JavaScript and HTML.
 
 First I created a new function that saves the data elements, values, and the ids for the filters that were changed.
 Then I created an if-else statement to add filter data from input, or clear the filter if no input data is there.
 Next, I created a function named filterTable that sets the filtered data to the table, loops through all of the filters and keeps any data that matches the filter values,
 and rebuilds the table by calling the buildTable function.
 Using d3.selectAll I attached an event listener (on change event) to pick up the changes that were made to each filter.
 
 I think you will notice it works pretty well.  :)
