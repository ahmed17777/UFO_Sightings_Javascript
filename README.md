# UFO Sightings with Javascript 
 
![ITUDF2YZUEDESTWVW1GL](https://user-images.githubusercontent.com/45697471/117879766-557b6500-b275-11eb-8dea-e05b2332a576.jpg) 
 
Syed Ahmed 

May 11, 2021 

## Overview 

In this project, I will be creating a webpage and dynamic table using Javascript and Bootstrap that provides an in-depth analysis of UFO sightings by allowing users to filter for multiple search criteria using a dynamic table that uses event listeners to update search results when they are inputted by the user. 

## Results 

After creating the intial webpage in the module, the first task at hand was to add the new search parameters that will filter results in our table. I also added the Bootstrap from class "form-control" to enhance styling. 

![1](https://user-images.githubusercontent.com/45697471/117881545-590feb80-b277-11eb-98d1-be8640abbfe6.png)


From here, once the user inputs search parameters into the search bar, the code stored in the app.js file uses an event listener to detect changes to each filter. The updateFilters() function saves the element, value, and the id of the filter that was changed. From here the filterTable() function loops through all of the filters and keeps any data that matches the filter values. Finally, as a result of this, the webpage filters the table based on user input. 

![1](https://user-images.githubusercontent.com/45697471/117882641-8d37dc00-b278-11eb-8f42-a479ccaf5bc3.png)

As we can see in the following screenshot, once the search parameters are entered, the table is filtered based on those parameters. 

![2](https://user-images.githubusercontent.com/45697471/117883091-fcadcb80-b278-11eb-8f9f-2afac3b3f1d0.png)

## Summary 

One drawback of this webpage would be that it can only return results for data that is stored in the data.js file. From what we can see, the data only includes UFO sightings in the US in the year 2010. This means the data does not include any other sightings that might have taken place in any other country or in a different year. Some recommendations for futher development would include: 
- Incorporating a message when the user inputs search parameters that are outside the values stored in the dataset, instead of having the table just return no results.
- A link to an article, or an image of the UFO sighting could be incorporated into the table as well. 


