# UFOs
## Overview of Project: the purpose of this analysis.
The purpose of this project is to learn how to take data that is stored as a JavaScript array or list and to also, create a clean webpage that contains a dynamic table of UFO sighting data that organizes and displays the information. The results can be filtered by the end user based on the user's input with various criterias and instantly see the table. We've designed this table using Javascript as the primary coding language. Finally, we use HTML, Bootstrap and CSS to read the Javascript code and create a webpage that is easy to view, includes filters, images, and a synopsis of the topic.

#### Resources
- Data Source: data.js
- Software: E6+, Javascript, HTML, CSS, Bootstrap, D3

## Results:
This webpage helps users access information of reported sightings and see the data. 

This webpage includes:
- A description or summary of the topic
- A table to display all of the information from the data source
- Search filters that will allow for visitors to update the table based on the search criteria they enter.

![UFOs](https://user-images.githubusercontent.com/33900637/152670333-c8ec8563-8625-4e90-b042-76b2a644e265.png)

In the above photo, you will notice there's a "Filter Search" section. The user will be able to enter date, location, and/or descriptive data to filter the data table see the results that match their criteria. You can filter by one or more of the search criteria such as:
- If you search by "City", you will see that the table updated to show the reported sightings that was recorded for that specific city.
- If you add a shape, the table will update filtering further to only display the information containing that shape.
- Or if you delete your previous entries and enter "State" and "Shape", the table will update using your new criteria.

## Summary:
#### Drawback:
Unfortunately, the webpage's major drawback is that the search field is "case-sensitive". The table will not update if you do not enter exactly how the data is stored and does not allow for partial entries. This is an issue because it does not intuitively tell the user how the information should be entered other than the "default" example shown. This can impact the user experience because all of the searchable data is lowercase. For example, if a user were to enter "CA" to identify the UFO sightings in California, the filter search results are zero. Whereas, if they were to enter "ca" in lower case, there are plenty of results.

#### Recommendations for further development:
Adding additional customizations, such as click-buttons, dropdown list, and/or auto-fill that can help guide the user and make the page more interactive. A dropdown option would enhance the user experience if there were a dropdown option for "Shape" due to the broad range of descriptions. Also, adding functionality to pull the data from a live source so that new data is easily and efficiently added that includes current and archived data not limited to only the United States but even worldwide.   I believe furthering these developments will greatly improve the user's experience. 
