# UFOs
## Overview of Project
In this project, we were tasked with using HTML and JavaScript to create an interactive webpage that allows users to filter (fictional) UFO sightings stored in a database. The user can filter based on date, city, state, country and shape of what was observed. <br/>

## Results
The user can search the database using five different search criteria: date, city, state, country, and shape of what was observed.  This can be done by using by scrolling down and using the text entry containers on the left-hand side of the page. It should be noted that the entries are case-sensitive and all entries should be lowercase. Also, the text inpout fields have initial "placeholder" values that are not invcluded in the filter. <br/>
Once the page is first loaded, all of the listings in the databse can be seen, as shown below.<br/>
<br/>
![](./page%20images/noFilter.PNG) <br/>
<br/>
Using the text input fields for each data type, the user can filter the database.  Once a desired value is typed into the text input field, hitting enter or clicking on another field will filter the data. Shown below are the results of using the filters to show only the instances in the database where the shape seen was listed as "other".<br/>
<br/>
![](.//page%20images//otherFilter.PNG) <br/>
<br/>
The user can also use multiple filters to further narrow their search of the UFO sighting database. Below shows the results of filtering the databse to show only those entries with a date of 1/2/2010 and "sphere" shape.<br/>
<br/>
![](.//page%20images//dateShapeFilter.PNG) <br/>
<br/>
## Summary
One drawback of the page is the fact that the filter inputs must be lowercase and will not work correctly with uppercase letters. This could be somewhat confusing for a user, as it seems reasonable that entering in "Atlanta" for the city should return the same entries as entering in "atlanta". One recommendation would be fix that issue so that the page would be overall more user-friendly. Another recommendation would perhaps be to add an interactive map so that users could filter the data and then see where on the map the entries lie. Are UFOs being sighted more in some areas than others?
