# Overview of Project: 
The purpose is to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. We have been given the data in data.js file.

# Results: 
Taking example in the image below, we chose 1/13/2010 as one search criteria. As soon as I get out of the input box, the results are fetched.
![date_search](https://github.com/Meghajain84/UFOs/blob/main/static/images/date_search.PNG)

We can further refine search by inputting other search criteria.
![date_city_search](https://github.com/Meghajain84/UFOs/blob/main/static/images/date_city.PNG)

If you want to remove some search criteria, just remove the value from respective input box.

Also whatever we input, it have to be exact match as seen in example above for city.

# Summary: 
## Drawback of this new design:
It doesn't let the user fill input for their choice of search criteria in one go. Unnecessaily system resources are wasted to fetch rows whenever an input is put in a search criteria.

## Two recommendations:
* Use javascript to validate the input like date should be in certain format, and city, state, country and shape should only have alphabets. If not the user should be prompted to renter in required format.

* Another search criteria could be added based on duration.
