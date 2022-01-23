# UFOs
## Overview
The objective is to build a JavaScript code that can receive input from an HTML webpage and filter a set of UFO sighting data based on multiple criteria, such as city, state, country, and shape.

## Results
When the web app is launched, a fully unfiltered view of the data table is visible at the bottom of the page. There are five input boxes that allow filtering by date, city, state, country, and shape of the UFO. In a previous iteration of this web app, there was only one filter option for the UFO Sightings table by Date. 

![results_1.png](https://github.com/rptseng/UFOs/blob/main/images/results_1.png)

Using the input boxes, the user can specify the values for the IDs they'd like to filter on. Below is an example of the table being filtered on two ID's simultaneously, the State "fl" and the shape "unknown".

![results_3.png](https://github.com/rptseng/UFOs/blob/main/images/results_3.png)

## Summary
Some drawbacks to this webpage is there is currently no instruction to indicate that pressing "Enter" is required to submit changes to the filters, and the range of the available data set is not clear.

Two additional recommendations to develop this page further could include:
- Printing the list of current filter settings somewhere on the page when "Enter" is pressed so it is clear what data is being presented in the table.
- Changing the filter input boxes into drop-down lists that include the range of values in each of the IDs. To somebody unfamiliar with the data set, they might not be able to effectively filter for all of the data they want to see.