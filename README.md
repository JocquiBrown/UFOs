# UFOs
UFO Sightings Web App: [UFO Sightings](file:///C:/Users/jocqu/Class/UFOs/index.html).

## Overview of Project
- The purpose of this project is to provide a more in-depth analysis of UFO sightings, by allowing users to filter for multiple criteria; including date, city, state, country, and the shape of the sighting. Furhter exploration into drawbacks of the features as well as reccommendations for development will also be provided.

## Results
- Using the Search Criteria on the Webpage

### 1. Navigate to the Webpage
![UFO_Sightings_Challenge_Screenshot_1](https://user-images.githubusercontent.com/120291854/230747081-3af83349-1830-4fa1-9919-7a13e2ff5f70.png)

- The link at the top of this document takes users the new UFO Sightings Webpage, while the image above shows us what the user will see on the main page.

### 2. Identify the Table 
![UFO_Sightings_Challenge_Screenshot_2](https://user-images.githubusercontent.com/120291854/230747178-94344265-0ad9-4b60-b3ef-5768546b7669.png)

- If we zoom in on the bottom right portion of the main page we can see the table of UFO sightings.

### 3. Idnetify the Filter Criteria for Searches
![UFO_Sightings_Challenge_Screenshot_3](https://user-images.githubusercontent.com/120291854/230747193-b9226cd1-1aff-4775-9933-bbd2cfec1d77.png)

- If we zoom in on the bottom left section of the main page we find the filters section. This is where users will input search criteria for UFO sightings. Users can filter the data in the table by date, city, state, country, and shape of the UFO sighting. Placeholder values are also provided in each field as a formatting aid.

### 4. Performing a Search for One Criteria
![UFO_Sightings_Challenge_Screenshot_4](https://user-images.githubusercontent.com/120291854/230747203-4640639b-c117-4e5a-aa0b-f75d4d44d739.png)

- In the image above, the table is filtered by city. The city of San Diego has been entered in the search field for cities and the output is a new, filtered table for all sightings in San Diego. All the user is required to do is enter the name of a city in the format provided by the placeholder and then hit "enter". The same holds true for the other search fields.

### 5. Performing a Search with Multiple Criteria
![UFO_Sightings_Challenge_Screenshot_5](https://user-images.githubusercontent.com/120291854/230748689-4960c2bc-3a01-400d-9b5c-ccc1622a433d.png)
![UFO_Sightings_Challenge_Screenshot_6](https://user-images.githubusercontent.com/120291854/230748692-50a661ba-971d-4616-affd-0187de4ac24d.png)

- The table can even be filtered for multiple search criteria at once! In the first image we have filtered the table for all UFO sightings in the state of Florida. However, in the second image we have an additional criteria specifically for sphere-shaped sightings in the state of Florida. The output is a table containing only UFO sightings in Florida where a spherical object was observed.

## Summary
- One drawback of this new design is that there is currently no way to filter the data by multiple of the same criteria. For example, there is no way for the user to search for all UFO sightings in both Florida and Texas. 

- One suggestion we could implement to improve the usability of the search filters, would be to include search criteria for duration and comments. For Duration, we could have multiple single-select options for the user that each provide a time range. For comments, we could provide a field for keywords that the user can input. The resulting table would contain all instances of the keyowrd the user input.

- Another improvement wouild be to edit the date section to allow for users to filter by a range of dates, rather than a specific date. For example, we could allow the user to search for all dates before or after the entered date by adding buttons for "before" and "after" or making these two separate fields next to each other. There are a plethora of options when it comes to builing optimal filter functionalities.
