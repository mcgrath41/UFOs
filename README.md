# UFOs

## Project Overview

### Purpose
Use JavaScript, HTML, and CSS to create a custom webpage that showcases different UFO sightings around the world.  

### Resources ###
- Data Source: data.js
- Software: Visual Studio Code 1.60.1, JavaScript, HTML, & CSS

## Analysis ##

### Results ###
In addition to the date, users can now filter for the city, state, country, and shape. 

As an example, the user may still filter only by date if desired:
![](/Resources/Date_filter.png)

In addition, the user can now filter on any of the other criteria listed underneath the "Enter Date" box. The example below shows the results when filtering on sightings in the state of Texas (State = "tx").
![](/Resources/State_filter.png)


The user may reset all filters either by deleting any entries in the filter boxes, or by selecting "UFO Sightings" at the top left of the page as seen in the screen shot below: 
![](/Resources/Reset_filter.png)



### Summary ###
The added fitering options appear to function as expected. One drawback to the current webpage, however, is that the user does not know if any selections on which to filter exist in the data set or if the correct format was entered.  In the next phase of development, it is recommended to:
1. Include a list of all unique values inside each parameter field button, one of which can be entered by the user prior to filtering. 
2. Add a data validation to flag or report as an error when an incorrect format has been entered (e.g. "TX" instead of "tx" for filtering on sightings in the state of Texas).
3. The dataset is limited and static; explore potential web scraping using python & flask.  

